## Problem 1: Exploratory data analysis with Pandas (65 Points)

### Tasks
In this problem you will repeat the steps in lesson 10 - 12 using a dataset of your interest. Also, you will use an additional method that we did not cover in class. The use of LLM is permitted and encouraged. Finally, you will report any useful information that you learned from your data analysis. 

### Objective
As outlined in the syllabus, this course emphasizes project-based learning and self-directed study opportunities. This problem provides you with the chance to explore a dataset of personal interest. The objectives of this problem are to:
- Facilitate your learning of Pandas by engaging with a dataset that aligns with your interests
- Provide hands-on practice to strengthen your ability to analyze tabular data
- Enhance your proficiency in accessing, manipulating, analyzing, and visualizing large datasets using Pandas

### Dataset selection

Select any dataset that you are interested in. This can be a dataset that you will use in your final project. 
Here are some datasets in case you need some suggestions. 
[Data.GOV   Database 7121 data sets for florida]
(https://catalog.data.gov/dataset/?q=florida+&sort=views_recent+desc&ext_location=&ext_bbox=&ext_prev_extent=&_vocab_category_all_limit=0)
[SOI Tax Stats - Data by Geographic Area]
(https://www.irs.gov/statistics/soi-tax-stats-data-by-geographic-area)


### Rubric 
#### 1.1 Data Exploration (50 points)
Using any (big) dataset of your interest, repeat Section 4.0 in Lessons 10 - 12 
| Task                                       | Criteria                                                            | Points |
|--------------------------------------------|---------------------------------------------------------------------|--------|
| 1. Data Collection                         | Evidence of data collection, appropriateness of dataset and citation   | 3      |
| 2. Read CSV File                           | Correctly read into DataFrame with Pandas                           | 3      |
| 3. Display DataFrame                       | Properly displayed with head/tail/info                              | 3      |
| 4. Filter Columns by Labels                | Accurate filtering, demonstrated understanding                      | 3      |
| 5. Filter Columns by Keyword               | Accurate filtering, demonstrated understanding                      | 3      |
| 6. Filter Rows by Value                    | Correct filtering by numeric and non-numeric values                 | 4      |
| 7. Datetime Index*                          | Appropriate datetime conversion and indexing, or suitable alternative operation | 4 |
| 8. Descriptive Statistics                  | Comprehensive descriptive statistics provided                       | 3      |
| 9. Resampling of Time-Series Data*          | Correct application of resampling techniques, or suitable alternative if no datetime | 4 |
| 10. Groupby                                | Correct usage of groupby for data aggregation                       | 3      |
| 11. Slicing with loc & iloc                | Accurate slicing techniques demonstrated                           | 3      |
| 12. Dicing                                 | Correct dicing of DataFrame to obtain smaller portions              | 3      |
| 13. Slicing and Dicing Together            | Effective combination of slicing and dicing to extract data         | 3      |
| 14. Datetime Column Subsetting*             | Correct subsetting using Datetime, or suitable alternative operation | 3     |
| 15. Quick Plots of Data                    | Creation of insightful plots that aid in data understanding         | 3      |
| 16. Operations on DataFrame                | Appropriate and effective operations applied to DataFrame           | 3      |
| 17. Iterating over Rows                    | (Bonus) Successful iteration over DataFrame rows for additional insights | 2 (bonus) |
| 18. Save & Load DataFrame                  | Correctly saved to and loaded from file                             | 3      |

#### 1.2 Pandas Method Exploration (5 points)
In this section, explore a Pandas method that was not covered in class but piques your interest or aligns with your dataset analysis. Demonstrate its usage with examples from your dataset. Here are some suggestions:  `.agg()` method, `.pivot_table()` methods, `.stack()` and `.unstack()`methods, `.merge()` and `.join()`methods, `.cut()` and `.qcut()` methods. `.explode()` method, `.shift()`method, `.rolling()` method, `.duplicated()` and `.drop_duplicates()` methods, and many more. 
| Task            | Criteria                                                                 | Points |
|-----------------|--------------------------------------------------------------------------|--------|
| 19. New Method  | Successful demonstration of a new Pandas method not covered in class, with clear explanation and proper application to the dataset | 5      |

#### 1.3 Information (5 points)
In this section, report any insights or useful information that you learned about your data from this analysis
| Task        | Criteria                                                             | Points |
|-------------|----------------------------------------------------------------------|--------|
| 19. Information | Insightful report detailing valuable findings from the analysis, including patterns, anomalies, or other relevant observations | 5      |

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

  
## Problem 2 - Water Quality analysis (35 points)

Red tides are caused by Karenia brevis harmful algae blooms. Plot the maximum concentration of Karenia brevis (cell counts per letter) per week for the whole dataset for the two regions of Tampa Bay and Charlotte Harbor estuary. From your plots, at which of these two areas red tides seem more frequent? 

For Karenia brevis cell count data, you can use the [current dataset](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.nodc:0120767) of Physical and biological data collected along the Texas, Mississippi, Alabama, and Florida Gulf coasts in the Gulf of Mexico as part of the Harmful Algal BloomS Observing System from 1953-08-19 to 2023-07-06 (NCEI Accession 0120767).
