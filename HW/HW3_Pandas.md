## Problem 1: Exploratory data analysis with Pandas (65 Points)

### Tasks
Perform the following tasks:
- Repeat the steps in Lessons 10 - 12 Pansas Primer using a dataset of your interest
- Apply a Pandas method that was not introduced in class in your data analysis
- Present noteworthy information uncovered from your data exploration
- Document your use of AI-LLM in debugging your code and seeking help during the process
 
### Objective
As outlined in the syllabus, this course emphasizes project-based learning and self-directed study opportunities. This problem provides you with the chance to explore a dataset of personal interest. The objectives of this problem are to:
- Facilitate your learning of Pandas by engaging with a dataset that aligns with your interests
- Provide hands-on practice to strengthen your ability to analyze tabular data
- Enhance your proficiency in accessing, manipulating, analyzing, and visualizing large datasets using Pandas

### Dataset selection
Select a dataset that aligns with the learning objectives for this assignment. When choosing a dataset, consider the following:
- **Personal Interest:** Select a dataset related to your domain of interest or your final project 
- **Size:** The dataset should contain enough rows and columns to allow you to demonstrate a variety of Pandas functionalities. As a guideline, aim for at least 50,000 rows and 5-10 columns. This is just one suggestion, but do what you want and what interests you most. 
- **Data Types:** Choose a dataset with a mix of numeric and non-numeric columns. The inclusion of datetime data and geographic data provides additional opportunities to practice Pandas time-series capabilities and geospatial features.
- **Suggested Datasets:** In case you do not have a dataset in mind, here are few suggestions: 
   - Florida public government databases: [Data.GOV   Database 7121 data sets for florida](https://catalog.data.gov/dataset/?q=florida+&sort=views_recent+desc&ext_location=&ext_bbox=&ext_prev_extent=&_vocab_category_all_limit=0)
   - Tax data: [SOI Tax Stats - Data by Geographic Area](https://www.irs.gov/statistics/soi-tax-stats-data-by-geographic-area)

The instructor is available to provide guidance if you need help selecting an appropriate dataset. Reach out with any questions!

### Rubric 
#### 1.1 Data exploration (50 points)
Using any (big) dataset of your interest, repeat Section 4.0 in Lessons 10 - 12 
| Task                                       | Criteria                                                            | Points |
|--------------------------------------------|---------------------------------------------------------------------|--------|
| 1. Data Collection                         | Appropriateness of dataset and citation                             | 5      |
| 2. Read CSV File                           | Correctly read into DataFrame with Pandas                           | 1      |
| 3. Display DataFrame                       | Properly displayed with head/tail/info                              | 2      |
| 4. Filter Columns by Labels                | Accurate filtering, demonstrated understanding                      | 3      |
| 5. Filter Columns by Keyword               | Accurate filtering, demonstrated understanding                      | 3      |
| 6. Filter Rows by Value                    | Correct filtering by numeric and non-numeric values                 | 3      |
| 7. Datetime Index*                          | Appropriate datetime conversion and indexing, or alternative if no datetime | 3 |
| 8. Descriptive Statistics                  | Comprehensive descriptive statistics provided                       | 3      |
| 9. Resampling of Time-Series Data*          | Correct application of resampling techniques, or alternative if no datetime | 3 |
| 10. Groupby                                | Correct usage of groupby for data aggregation                       | 3      |
| 11. Slicing with loc & iloc                | Accurate slicing techniques demonstrated                           | 3      |
| 12. Dicing                                 | Correct dicing of DataFrame to obtain smaller portions              | 3      |
| 13. Slicing and Dicing Together            | Effective combination of slicing and dicing to extract data         | 3      |
| 14. Datetime Column Subsetting*             | Correct subsetting using Datetime, or alternative if no datetime | 3     |
| 15. Quick Plots of Data                    | Creation of insightful plots that aid in data understanding         | 3      |
| 16. Operations on DataFrame                | Appropriate and effective operations applied to DataFrame           | 3      |
| 17. Iterating over Rows                    | (Bonus) Successful iteration over DataFrame rows for additional insights | 1 (bonus) |
| 18. Save & Load DataFrame                  | Correctly saved to and loaded from file                             | 3      |

#### 1.2 New Pandas method exploration (5 points)
Explore a Pandas method that was not covered in class but piques your interest or aligns with your dataset analysis. Demonstrate its usage with examples from your dataset. Here are some suggestions:  `.agg()` method, `.pivot_table()` methods, `.stack()` and `.unstack()`methods, `.merge()` and `.join()`methods, `.cut()` and `.qcut()` methods. `.explode()` method, `.shift()`method, `.rolling()` method, `.duplicated()` and `.drop_duplicates()` methods, and many more. 
| Task            | Criteria                                                                 | Points |
|-----------------|--------------------------------------------------------------------------|--------|
| 19. New Method  | Successful demonstration of a new Pandas method not covered in class, with clear explanation and proper application to the dataset | 5      |

#### 1.3 Information Discovries (5 points)
In this section, report any valuable information and findings derived from your data analysis.
| Task        | Criteria                                                             | Points |
|-------------|----------------------------------------------------------------------|--------|
| 19. Dtion | Clear and informative report outlining valuable findings from the analysis, including patterns, anomalies, or other relevant observations | 5      |

These two figures will help you to understand the data-information-knowledge-wisdom hierarchy at the science-policy interface. 

![Image1](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEio6V0Xfqp86y2Jvzbmi5p8EQFtGTZtt65jGMEysrnAhqX7d7taK5dwzB6-fLx3Rdmdqm4nkSuKU4uSzjTeneGFCC_G1MwQFu4NN1_OWDYkjLgFhZhcwod5rJfPtDOrfr_Z35h8HKf_eA8jbO6NdTpGLbvswpm1oJCVAL5YakduNO2CnEx5zd4S4hUY/s850/DKIW.JPG)   
Image Credit: [Cannas et al. 2019](https://doi.org/10.1093/af/vfz005)
  
![Image2](https://ars.els-cdn.com/content/image/1-s2.0-S1364815216304194-gr1_lrg.jpg)    
Image Credit: [Lokers et al. 2016](https://doi.org/10.1016/j.envsoft.2016.07.017)

#### 1.4 LLM Usage (5 points)
This section highlights the integration of advanced AI technologies in data analysis workflows and showcases your ability to leverage cutting-edge tools for effective problem-solving. In this section, document the specific instances where you utilized a Large Language Model (LLM) such as GPT-3.5 for problem-solving during this assignment and discuss your overall experience of using LLM. 
| Task        | Criteria                                                                                     | Points |
|-------------|----------------------------------------------------------------------------------------------|--------|
| 20. LLM Usage | Thorough documentation of LLM usage in the analysis process, including specific examples and reflection on the experience | 5      |

**Additional Notes:**
- Students should adhere to best practices in coding and data analysis.
- Comments and documentation in the code are expected to explain the steps and logic.
- Graders should consider the clarity and thoroughness of the student's approach and explanations.
- Points may be deducted for incorrect applications, lack of explanations, or failure to meet the criteria as outlined.
- For tasks with alternative operations (marked with an asterisk), in case your dataset does not contain datetime data, students should be graded on the relevance and appropriateness of the selected operation to their dataset.

  
## Problem 2 - Water quality analysis (35 points)

Red tides are caused by Karenia brevis harmful algae blooms. Plot the maximum concentration of Karenia brevis (cell counts per letter) per week for the whole dataset for the two regions of Tampa Bay and Charlotte Harbor estuary. From your plots, at which of these two areas red tides seem more frequent? 

For Karenia brevis cell count data, you can use the [current dataset](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.nodc:0120767) of Physical and biological data collected along the Texas, Mississippi, Alabama, and Florida Gulf coasts in the Gulf of Mexico as part of the Harmful Algal BloomS Observing System from 1953-08-19 to 2023-07-06 (NCEI Accession 0120767).
