# [Homework 3](https://aselshall.github.io/eds/HW/HW3)

## Late Submission Policy
- If you encounter challenges that may affect your ability to submit on time, please communicate with the instructor as early as possible to explore possible accommodations
- Deadline maybe extended for execused absences
- Absence excuse requires written documentation from a certified medical professional, faculty member, administration, coach, or athletic director
- Unexecused late submissions received after the deadline will incur a penalty of 20% per day of the total possible points
- Once the solutions and grades are posted, late unexecused submissions will not be accepted, and a score of zero will be assigned

## Problem 1: Exploratory data analysis with Pandas (100 points)
- This problem is worth 100 points for undergraduate students.
- For graduate students, the final score will be scaled to 90 points. For example, if you scored 90/100, your adjusted score for this problem will be 81/90.

### Tasks
Perform the following tasks:
1. Repeat the steps in Lessons 10 - 14 Pansas Primer using a dataset of your interest
2. Apply a Pandas method that was not introduced in class in your data analysis
3. Present noteworthy information uncovered from your data exploration
4. Document your use of AI-LLM in improving your learning and productivity  
 
### Learning objectives
As outlined in the syllabus, this course emphasizes project-based learning and self-directed study opportunities. This problem provides you with the chance to explore a dataset of personal interest. The objectives of this problem are to:
- Facilitate your learning of Pandas by engaging with a dataset that aligns with your interests
- Enhance your proficiency in accessing, wrangling, analyzing, and visualizing large `csv` datasets
- Provide hands-on practice to strengthen your ability to analyze tabular data with mixed data types
- Engage in critical thinking to extract useful infromation from raw data 
- Practice articulating your findings clearly and concisely using visualizations or narrative explanations
- Improve your skills in using AI-LLM for independent and self-directed learning
 
### Dataset selection
Select a dataset that aligns with the learning objectives for this assignment. When choosing a dataset, consider the following:
- **Personal Interest:** Select a dataset related to your domain of interest or your final project 
- **Size:** The dataset should contain enough rows and columns to allow you to demonstrate a variety of Pandas functionalities. As a guideline, aim for at least 50,000 rows and 5-10 columns. This is just one suggestion, but do what you want and what interests you most. 
- **Data Types:** Choose a dataset with a mix of numeric and non-numeric columns. The inclusion of datetime data and geographic data provides additional opportunities to practice Pandas time-series capabilities and geospatial features.
- **Data Theme:** Select a dataset from topics including but not limited to environmental science, water resources, climate change, economics, demographics, public health, social media, and social sciences, preferably with an environmental and water resources relevance.
- **Suggested Datasets:** In case you do not have a dataset in mind, here are few suggestions: 
   - Florida public government databases: [Data.GOV   Database 7121 data sets for florida](https://catalog.data.gov/dataset/?q=florida+&sort=views_recent+desc&ext_location=&ext_bbox=&ext_prev_extent=&_vocab_category_all_limit=0)
   - Tax data: [SOI Tax Stats - Data by Geographic Area](https://www.irs.gov/statistics/soi-tax-stats-data-by-geographic-area)
   - Kaggle Open Datasets and Machine Learning Projects: [Kaggle csv data](https://www.kaggle.com/datasets?fileType=csv)

The instructor is available to provide guidance if you need help selecting an appropriate dataset. Please reach out with any questions!

### Rubric 
#### Task 1. Data exploration (85 points)
Using any (big) dataset of your interest, repeat Section 4.0 in Lessons 10 - 14

| Task | Criteria | Points |
|------|----------|--------|
| 1. Data Selection | Appropriateness of dataset and proper citation | 8|
| 2. Read CSV File | Correctly read into DataFrame with Pandas | 1 |
| 3. Display DataFrame | Properly displayed with head/tail/info | 1 |
| 4. Filter Columns by Labels | Accurate filtering, demonstrated understanding | 5 |
| 5. Filter Rows by Keyword | Accurate filtering, demonstrated understanding | 5 |
| 6. Filter Rows by Value | Correct filtering by numeric and non-numeric values | 5 |
| 7. Datetime Index* | Appropriate datetime conversion and indexing, or alternative if no datetime | 5 |
| 8. Descriptive Statistics | Comprehensive descriptive statistics provided | 5 |
| 9. Resampling of Time-Series Data* | Correct application of resampling techniques, or alternative if no datetime | 5 |
| 10. Groupby | Correct usage of groupby for data aggregation | 5 |
| 11. Slicing with loc & iloc | Accurate slicing techniques demonstrated | 5 |
| 12. Dicing | Correct dicing of DataFrame to obtain smaller portions | 5 |
| 13. Slicing and Dicing Together | Effective combination of slicing and dicing to extract data | 5 |
| 14. Datetime Column Subsetting* | Correct subsetting using Datetime, or alternative if no datetime | 5 |
| 15. Quick Plots of Data | Creation of insightful plots that aid in data understanding | 5 |
| 16. Operations on DataFrame | Appropriate and effective operations applied to DataFrame | 5 |
| 17. Iterating over Rows | (Bonus) Successful iteration over DataFrame rows for additional insights | 1 (bonus) |
| 18. Save & Load DataFrame | Correctly saved to and loaded from file | 5 |

#### Task 2. New Pandas method exploration (5 points)
Explore a Pandas method that was not covered in class but piques your interest or aligns with your dataset analysis. Demonstrate its usage with examples from your dataset. Here are some suggestions:  `.agg()` method, `.pivot_table()` methods, `.stack()` and `.unstack()`methods, `.merge()` and `.join()`methods, `.cut()` and `.qcut()` methods. `.explode()` method, `.shift()`method, `.rolling()` method, `.duplicated()` and `.drop_duplicates()` methods, and many more. 

| Task | Criteria | Points |
|------|----------|--------|
| 19. New Method | Successful demonstration of a new Pandas method not covered in class, with clear explanation and proper application to the dataset | 5 |

#### Task 3. Information discovries (5 points)
Report any valuable information and findings derived from your data analysis.

| Task | Criteria | Points |
|------|----------|--------|
| 20. Information Discoveries | Clear and informative report outlining valuable findings from the analysis, including patterns, anomalies, or other relevant observations | 5 |


#### Task 4. GenAI usage (5 points)
Highlight the integration of  GenAI in data analysis workflows and showcases your ability to leverage GenAI tools for effective problem-solving. In this section, document the specific instances where you utilized GenAI (e.g., ChatGPT, Gemini, Claude) for problem-solving during this assignment and discuss your overall experience of using GenAI. 

| Task | Criteria | Points |
|------|----------|--------|
| 21. GenAI Usage | Thorough documentation of GenAI usage in the analysis process, including specific examples and reflection on the experience | 5 |


**Additional Notes:**
- Students should adhere to best practices in coding.
- Comments and documentation in the code are expected to explain the steps and logic.
- Grade will be based on the clarity and thoroughness of the student's approach and explanations
- Points may be deducted for incorrect applications, lack of explanations, or failure to meet the criteria as outlined.
- Tasks with alternative operations (marked with an asterisk) is for the case that your dataset does not contain datetime data. Students should be graded on the relevance and appropriateness of the alternative selected operation to their dataset.

**Additional Information:**   
   
For Task 3. Information discovries (5 points), if you are interested, you can learn about [data-information-knowledge-wisdom hierarchy](https://aselshall.github.io/eds/HW/data_hierarchy) at the science-policy interface. 

  
## Problem 2 - Water quality analysis (10 points) 
- Mandatory for graduate students
- Optional for undergraduates for 10 bonus points

### Dataset
Red tides are caused by Karenia brevis harmful algae blooms. For Karenia brevis cell count data, you can use the [current dataset](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.nodc:0120767) of Physical and biological data collected along the Texas, Mississippi, Alabama, and Florida Gulf coasts in the Gulf of Mexico as part of the Harmful Algal BloomS Observing System from 1953-08-19 to 2023-07-06 (NCEI Accession 0120767). For direct data download, you can use this [data link](https://www.nodc.noaa.gov/archive/arc0069/0120767/7.7/data/0-data/habsos_20230714.csv) and this [data documentation link](https://www.nodc.noaa.gov/archive/arc0069/0120767/7.7/data/0-data/Support%20Documents/).  Alternatively, FWRI documents Karenia brevis blooms from 1953 to the present. The dataset has more than 200,000 records is updated daily. To request this dataset email: HABdata@MyFWC.com. To learn more about this data, check the [FWRI  Red Tide  Red Tide Current Status](https://myfwc.com/research/redtide/statewide/).

### Study areas
Conduct your analysis in Tampa Bay and Charlotte Harbor estuary. For Tampa Bay, restrict the Karenia brevis measurements from 27° N to 28° N and 85° W to coast. For Charlotte Harbor estuary, restrict the Karenia brevis measurements from 25.5° N to less than 27° N and 85° W to coast.

### Problem statement

**Task 1:** Plot the maximum cellcount of Karenia brevis (cell counts per letter) per week for the whole dataset for each of the regions of Tampa Bay and Charlotte Harbor estuary.
 
**Task 2:** FWRI classifies Karenia brevis abundance based on cell counts as described [here](https://myfwc.com/research/redtide/statewide/) as follows:   
<table>
  <thead>
    <tr>
      <th>Index</th>
      <th>Description</th>
      <th>K. brevis abundance</th>
      <th>Possible effects (K. brevis only)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>NOT PRESENT- BACKGROUND</td>
      <td>background levels of 1,000 cells or less</td>
      <td>no effects anticipated</td>
    </tr>
    <tr>
      <td>1</td>
      <td>VERY LOW</td>
      <td>> 1,000 - 10,000 cells/L</td>
      <td>possible respiratory irritation; shellfish harvesting closures when cell abundance equals or exceeds 5,000 cells/L</td>
    </tr>
    <tr>
      <td>2</td>
      <td>LOW</td>
      <td>> 10,000 - 100,000 cells/L</td>
      <td>respiratory irritation; shellfish harvesting closures; possible fish kills; probable detection of chlorophyll by satellites at upper range of cell abundance</td>
    </tr>
    <tr>
      <td>3</td>
      <td>MEDIUM</td>
      <td>> 100,000 - 1,000,000 cells/L</td>
      <td>respiratory irritation; shellfish harvesting closures; probable fish kills; detection of surface chlorophyll by satellites</td>
    </tr>
    <tr>
      <td>4</td>
      <td>HIGH</td>
      <td>> 1,000,000 cells/L</td>
      <td>as above, plus water discoloration</td>
    </tr>
  </tbody>
</table>

Given the data in the above table, plot a histogram for each region to show the frequencies of the maximum cellcount per week according to the above classification. The histogram should only include 4 bins for the cases of 'very low', 'low', 'medium', and 'high'.
  
Here is one solution strategy that you can follow. 

(1) After you read and clean your data into DataFrame let use say `df` as you did in task 1, create a new column `BLOOM_CLASS`. Given the above table do bloom classifcation (i.e., 'no bloom', 'very low bloom', 'low bloom', 'medium bloom', and 'hig bloomh') for the whole dataset. For example, if the max cellcount in row 1 in the table below is 388400000 cells/L , then according to the table above this is a HIGH bloom, and then the first rows in `BLOOM_CLASS` will have the values of 4 (i.e., the index value in the table above). If the max concentration in a given row is 0 then the index will 0 and that row under `BLOOM_CLASS` will have a value of 0. Here is an example, of how your DataFrame `df` will look like:

|         | STATE_ID | DESCRIPTION                                           | LATITUDE | LONGITUDE | CELLCOUNT | REGION     | BLOOM_CLASS |
|---------|----------|-------------------------------------------------------|----------|-----------|-----------|------------|-------------|
| 2022-11-30 18:50:00 | FL       | Bay Dock (Sarasota Bay)                              | 27.331600| -82.577900| 388400000 | Tampa Bay  | 4           |
| 1994-12-09 20:30:00 | FL       | Bay Dock (Sarasota Bay)                              | 27.331600| -82.577900| 358000000 | Tampa Bay  | 4           |
| 1996-02-22 00:00:00 | FL       | Siesta Key; 8 mi off mkr 3A at 270 degrees           | 27.277200| -82.722300| 197656000 | Tampa Bay  | 4           |
| 2005-10-10 21:21:00 | TX       | Windsurfing Flats, Pinell Property, south Padr...    | 26.162420| -97.182580| 40000     | Other      | 2           |
| 2019-01-02 20:30:00 | FL       | Lido Key, 2.5 miles WSW of                            | 27.300000| -82.620000| 186266667 | Tampa Bay  | 4           |
| ...     | ...      | ...                                                   | ...      | ...       | ...       | ...        | ...         |
| 2020-08-25 00:00:00 | MS       | 5-9A                                                  | 30.361850| -88.850067| 0         | Other      | 0           |
| 2020-09-30 00:00:00 | MS       | Katrina Key                                           | 30.356869| -88.839592| 0         | Other      | 0           |
| 2021-01-25 00:00:00 | MS       | Sample* Long Beach                                    | 30.346020| -89.141030| 0         | Other      | 0           |
| 2021-11-15 00:00:00 | MS       | 10-Jun                                                | 30.343900| -88.602667| 0         | Other      | 0           |
| 2021-12-21 00:00:00 | MS       | 10-Jun                                                | 30.343900| -88.602667| 0         | Other      | 0           |

205552 rows × 7 columns

This is similar to Exercise 4. In  exercise 4 you created an new column `REGION` and did a mask and dicing to fill-in this new column with values (i.e, 'Tampa Bay',  'Charlotte Harbor', and 'Other') based on the latitude and longitude mask. You can do the same here. Create a new column `BLOOM_CLASS`, and do a mask and dicing to fill-in new columns with values of 0, 1, 2, 3, or 4 based on brevis abundance mask given the ranges in the table above.

(2) As a copy from your original DataFrame `df`, create two new DataFrames, one for each region as follows: `charlotte_harbor_hist_data` and  `tampa_bay_hist_data`. You can use these DataFrames to do resampling for each regions

(3) Resample your cellcount to find the maximum cell count per week. Remember from class that you can only do resample with numeric columns, so make sure that you only select the `BLOOM_CLASS` column. It is always a good idea to do sorting before resampling. Then after you do sorting and weekly resample, your data should look like this for Charlotte Harbor, for example,

| SAMPLE_DATE    | BLOOM_CLASS |
|----------------|-------------|
| 1953-08-23     | 3.0         |
| 1953-08-30     | 0.0         |
| 1953-09-06     | NaN         |
| 1953-09-13     | NaN         |
| 1953-09-20     | NaN         |
| ...            | ...         |
| 2023-06-04     | 0.0         |
| 2023-06-11     | 0.0         |
| 2023-06-18     | 0.0         |
| 2023-06-25     | 0.0         |
| 2023-07-02     | 0.0         |

3646 rows × 1 columns

(4) Create a histogram plot for only index values 1 to 4 in your `BLOOM_Class` column for each region. You can have one figure for each region. 

Hints:
- For task 1: Check Exercise 4 on Canvas under the Pandas module
- For task 2: You can follow the above solution strategy

### Final answer
This is a solution:
![histogram1953](https://github.com/aselshall/eds/assets/40507239/1f8cbc94-c6f6-40b4-ad8d-d549273d1739)
  
This is an extra figure in case your are curious about the last 10 years:
![histogram](https://github.com/aselshall/eds/assets/40507239/6b48bd63-0c8c-4091-ade6-3fd6df1c1ac2)

### Rubric
The student's performance on this homework problem will be evaluated based on the ability to collect and organize the data, perform data analysis and visualization, interpret the results, and communicate the findings in a clear and concise manner as follows.
1. Data Collection and Preparation (1 points)
   - Correctly downloaded and imported the dataset from the provided data link or requested the dataset from FWRI as instructed.
   - Successfully filtered and subsetted the data for Tampa Bay and Charlotte Harbor estuary regions based on the provided latitude and longitude constraints.
2. Data Analysis and Visualization (6 points)
   - Accurately extracted the maximum concentration of Karenia brevis cell counts per week from the dataset for both Tampa Bay and Charlotte Harbor estuary.
   - Created a clear and informative plot(s) of the maximum concentration of Karenia brevis cell counts per week for the whole dataset and for each region.
   - Accurately classified the bloom  per week for for both Tampa Bay and Charlotte Harbor estuary. 
   - Created a clear and informative histogram plot(s) for the bloom impact per week for each region.
3. Interpretation and Conclusion (1 points)
   - Provided a brief interpretation of the plots, including any noticeable patterns, trends, or anomalies between the two regions.
   - Discussed relevant assumptions or limitations. 
4. Code Quality and Documentation (2 points)
   - Submitted a well-structured and commented Python code, demonstrating a good understanding of Pandas and good coding practices
   - Proper citation of the used AI-LLM and data source.
    
    
