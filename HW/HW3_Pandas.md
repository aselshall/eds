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
- Enhance your proficiency in accessing, manipulating, analyzing, and visualizing large datasets in `csv` format using Pandas

### Dataset selection
Select a dataset that aligns with the learning objectives for this assignment. When choosing a dataset, consider the following:
- **Personal Interest:** Select a dataset related to your domain of interest or your final project 
- **Size:** The dataset should contain enough rows and columns to allow you to demonstrate a variety of Pandas functionalities. As a guideline, aim for at least 50,000 rows and 5-10 columns. This is just one suggestion, but do what you want and what interests you most. 
- **Data Types:** Choose a dataset with a mix of numeric and non-numeric columns. The inclusion of datetime data and geographic data provides additional opportunities to practice Pandas time-series capabilities and geospatial features.
- **Suggested Datasets:** In case you do not have a dataset in mind, here are few suggestions: 
   - Florida public government databases: [Data.GOV   Database 7121 data sets for florida](https://catalog.data.gov/dataset/?q=florida+&sort=views_recent+desc&ext_location=&ext_bbox=&ext_prev_extent=&_vocab_category_all_limit=0)
   - Tax data: [SOI Tax Stats - Data by Geographic Area](https://www.irs.gov/statistics/soi-tax-stats-data-by-geographic-area)

The instructor is available to provide guidance if you need help selecting an appropriate dataset. Please reach out with any questions!

### Rubric 
#### Task 1. Data exploration (50 points)
Using any (big) dataset of your interest, repeat Section 4.0 in Lessons 10 - 12 
<table>
    <thead>
        <tr>
            <th>Task</th>
            <th>Criteria</th>
            <th>Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1. Data Collection</td>
            <td>Appropriateness of dataset and citation</td>
            <td>5</td>
        </tr>
        <tr>
            <td>2. Read CSV File</td>
            <td>Correctly read into DataFrame with Pandas</td>
            <td>1</td>
        </tr>
        <tr>
            <td>3. Display DataFrame</td>
            <td>Properly displayed with head/tail/info</td>
            <td>2</td>
        </tr>
        <tr>
            <td>4. Filter Columns by Labels</td>
            <td>Accurate filtering, demonstrated understanding</td>
            <td>3</td>
        </tr>
        <tr>
            <td>5. Filter Columns by Keyword</td>
            <td>Accurate filtering, demonstrated understanding</td>
            <td>3</td>
        </tr>
        <tr>
            <td>6. Filter Rows by Value</td>
            <td>Correct filtering by numeric and non-numeric values</td>
            <td>3</td>
        </tr>
        <tr>
            <td>7. Datetime Index*</td>
            <td>Appropriate datetime conversion and indexing, or alternative if no datetime</td>
            <td>3</td>
        </tr>
        <tr>
            <td>8. Descriptive Statistics</td>
            <td>Comprehensive descriptive statistics provided</td>
            <td>3</td>
        </tr>
        <tr>
            <td>9. Resampling of Time-Series Data*</td>
            <td>Correct application of resampling techniques, or alternative if no datetime</td>
            <td>3</td>
        </tr>
        <tr>
            <td>10. Groupby</td>
            <td>Correct usage of groupby for data aggregation</td>
            <td>3</td>
        </tr>
        <tr>
            <td>11. Slicing with loc & iloc</td>
            <td>Accurate slicing techniques demonstrated</td>
            <td>3</td>
        </tr>
        <tr>
            <td>12. Dicing</td>
            <td>Correct dicing of DataFrame to obtain smaller portions</td>
            <td>3</td>
        </tr>
        <tr>
            <td>13. Slicing and Dicing Together</td>
            <td>Effective combination of slicing and dicing to extract data</td>
            <td>3</td>
        </tr>
        <tr>
            <td>14. Datetime Column Subsetting*</td>
            <td>Correct subsetting using Datetime, or alternative if no datetime</td>
            <td>3</td>
        </tr>
        <tr>
            <td>15. Quick Plots of Data</td>
            <td>Creation of insightful plots that aid in data understanding</td>
            <td>3</td>
        </tr>
        <tr>
            <td>16. Operations on DataFrame</td>
            <td>Appropriate and effective operations applied to DataFrame</td>
            <td>3</td>
        </tr>
        <tr>
            <td>17. Iterating over Rows</td>
            <td>(Bonus) Successful iteration over DataFrame rows for additional insights</td>
            <td>1 (bonus)</td>
        </tr>
        <tr>
            <td>18. Save & Load DataFrame</td>
            <td>Correctly saved to and loaded from file</td>
            <td>3</td>
        </tr>
    </tbody>
</table>

#### Task 2. New Pandas method exploration (5 points)
Explore a Pandas method that was not covered in class but piques your interest or aligns with your dataset analysis. Demonstrate its usage with examples from your dataset. Here are some suggestions:  `.agg()` method, `.pivot_table()` methods, `.stack()` and `.unstack()`methods, `.merge()` and `.join()`methods, `.cut()` and `.qcut()` methods. `.explode()` method, `.shift()`method, `.rolling()` method, `.duplicated()` and `.drop_duplicates()` methods, and many more. 
<table>
    <thead>
        <tr>
            <th>Task</th>
            <th>Criteria</th>
            <th>Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>19. New Method</td>
            <td>Successful demonstration of a new Pandas method not covered in class, with clear explanation and proper application to the dataset</td>
            <td>5</td>
        </tr>
    </tbody>
</table>

#### Task 3. Information discovries (5 points)
In this section, report any valuable information and findings derived from your data analysis.
<table>
    <thead>
        <tr>
            <th>Task</th>
            <th>Criteria</th>
            <th>Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>20. Infromation Discovries</td>
            <td>Clear and informative report outlining valuable findings from the analysis, including patterns, anomalies, or other relevant observations</td>
            <td>5</td>
        </tr>
    </tbody>
</table>

#### Task 4. LLM usage (5 points)
This section highlights the integration of advanced AI technologies in data analysis workflows and showcases your ability to leverage cutting-edge tools for effective problem-solving. In this section, document the specific instances where you utilized a Large Language Model (LLM) such as GPT-3.5 for problem-solving during this assignment and discuss your overall experience of using LLM. 
<table>
    <thead>
        <tr>
            <th>Task</th>
            <th>Criteria</th>
            <th>Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>21. LLM Usage</td>
            <td>Thorough documentation of LLM usage in the analysis process, including specific examples and reflection on the experience</td>
            <td>5</td>
        </tr>
    </tbody>
</table>

**Additional Notes:**
- Students should adhere to best practices in coding and data analysis.
- Comments and documentation in the code are expected to explain the steps and logic.
- Graders should consider the clarity and thoroughness of the student's approach and explanations.
- Points may be deducted for incorrect applications, lack of explanations, or failure to meet the criteria as outlined.
- For tasks with alternative operations (marked with an asterisk), in case your dataset does not contain datetime data, students should be graded on the relevance and appropriateness of the selected operation to their dataset.

**Additional Information:**   
   
For Task 3. Information discovries (5 points), these two figures will help you to understand the data-information-knowledge-wisdom hierarchy at the science-policy interface. 
  
![Image1](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEio6V0Xfqp86y2Jvzbmi5p8EQFtGTZtt65jGMEysrnAhqX7d7taK5dwzB6-fLx3Rdmdqm4nkSuKU4uSzjTeneGFCC_G1MwQFu4NN1_OWDYkjLgFhZhcwod5rJfPtDOrfr_Z35h8HKf_eA8jbO6NdTpGLbvswpm1oJCVAL5YakduNO2CnEx5zd4S4hUY/s850/DKIW.JPG)   
Image Credit: [Cannas et al. 2019](https://doi.org/10.1093/af/vfz005)
  
![Image2](https://ars.els-cdn.com/content/image/1-s2.0-S1364815216304194-gr1_lrg.jpg)    
Image Credit: [Lokers et al. 2016](https://doi.org/10.1016/j.envsoft.2016.07.017)

  
## Problem 2 - Water quality analysis (35 points)

Red tides are caused by Karenia brevis harmful algae blooms. Plot the maximum concentration of Karenia brevis (cell counts per letter) per week for the whole dataset for the two regions of Tampa Bay and Charlotte Harbor estuary. For Tampa Bay, restrict the Karenia brevis measurements from 27° N to 28° N and 85° W to coast. For Charlotte Harbor estuary, restrict the Karenia brevis measurements from 25.5° N to less than 27° N and 85° W to coast.

For Karenia brevis cell count data, you can use the [current dataset](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.nodc:0120767) of Physical and biological data collected along the Texas, Mississippi, Alabama, and Florida Gulf coasts in the Gulf of Mexico as part of the Harmful Algal BloomS Observing System from 1953-08-19 to 2023-07-06 (NCEI Accession 0120767). For direct data download, you can use this [data link](https://www.nodc.noaa.gov/archive/arc0069/0120767/7.7/data/0-data/habsos_20230714.csv) and this [data documentation link](https://www.nodc.noaa.gov/archive/arc0069/0120767/7.7/data/0-data/Support%20Documents/).  Alternatively, FWRI documents Karenia brevis blooms from 1953 to the present. The dataset has more than 200,000 records is updated daily. To request this dataset email: HABdata@MyFWC.com. To learn more about this data, check the [FWRI  Red Tide  Red Tide Current Status](https://myfwc.com/research/redtide/statewide/).
