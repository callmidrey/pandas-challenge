# pandas-challenge

My Pandas challenge- Module 4 Challenge 
Data Cleaning and Preparation:

The analysis began with a dataset containing information about schools and students, including data on student scores in math and reading, school budgets,cshool types, and sizes in two different datasets that was merged into a single dataframe. The dataset was pretty clean with no missing values and the datatypes was in sync with the format required for analysis. Little cleaning was done.

-District Summary:
A snapshot was given about the entire 15 schools in the district. It showed that roughly about 39,170 students were enrolled and the average scores for math and reading were above 70%. however, the overall passing percentage was less than 70%.

-School Summary:
A school summary was created, which zoomed into the individual schools in the district and the type of school it was, Average math and reading scores for each school, Percentage of students passing math and reading, Per student budgets as well as the scores and passing percentages for each schoolin both reading and maths.
Top and Bottom Performing Schools:The top 5-performing and bottom 5-performing schools were identified based on the overall passing rate, and their details were displayed. `Refer to Resources for output`

-Math and Reading Scores by Grade: Math and reading scores were analyzed by grade level (9th, 10th, 11th, and 12th). Average scores were calculated for each grade and displayed in separate DataFrames.`Refer to Resources for output`
-Scores by School Spending: Schools were categorized into spending ranges per student. The analysis included. `Refer to Resources for output`
-Scores by School Type:Schools were grouped by type (Charter or District).

Key Findings:
    1. Charter schools generally outperformed District schools in terms of average scores and passing rates.`Refer to Resources folder for type_output` 
    2 Smaller schools (with fewer students) tended to have higher overall passing rates compared to larger schools.`Refer to Resources folder for sizs_output`
    3.Schools with lower per student budgets often had higher overall passing rates, suggesting that increased funding does not                      necessarily correlate with better academic performance.` refer to resources for per_school_summary`

Limitations:
The data obtained was limited and as such, there may be other factors that might affect performance such as teacher to student ratio, availability of teaching and learning materials as well as the population density of the area inwhich the school is located, just to mention a few. 

Conclusion:
These analyses provide insights into school performance and can inform decisions related to school funding, resource allocation, and strategies for improving student outcomes.