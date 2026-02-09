📌 Project Description

This experiment demonstrates the use of data visualization techniques using R and ggplot2 to analyze the internal assessment performance of first-year engineering students. The project focuses on visually interpreting academic performance across multiple subjects using indicators such as internal test scores, assignment marks, and final grades.

The visualizations implemented help in:

Understanding subject-wise academic performance

Identifying performance trends across internal assessments

Analyzing grade distribution among students

Highlighting subjects with lower overall performance

📂 Dataset Used

File Name: 1.student_performance.csv

Expected Columns:

Roll_Number

Subject

Internal_Test_1

Internal_Test_2

Assignment_Marks

Final_Grade

🛠 Libraries Required

The following R libraries are used in this experiment:

library(ggplot2)
library(dplyr)
library(tidyr)

⚙️ Steps Performed
1. Load Required Libraries

All necessary libraries for data manipulation and visualization are loaded using the library() function.

2. Import Dataset

The dataset is imported into R using the read.csv() function.

3. Data Preprocessing

A new column Average_Marks is calculated by averaging:

Internal Test 1 marks

Internal Test 2 marks

Assignment marks

4. Data Visualization
a) Bar Chart – Subject-wise Average Marks

Displays the average internal marks for each subject

Helps identify subjects with lower overall performance

b) Line Chart – Performance Trend Across Tests

Shows the trend of average performance across internal assessments

Useful for analyzing improvement or decline

c) Pie Chart – Grade Distribution

Represents the distribution of final grades

Provides a clear overview of academic outcomes

📊 Output Generated

Bar chart showing subject-wise average marks

Line chart illustrating performance trends across tests

Pie chart representing grade distribution

(Screenshots of code and outputs are included separately.)

✅ Conclusion

The visualization techniques used in this experiment effectively highlight subject difficulty, performance trends, and overall grade distribution. Such analysis helps academic institutions identify weak areas and improve teaching and evaluation strategies.
