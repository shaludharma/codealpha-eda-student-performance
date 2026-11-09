# Student Performance - Exploratory Data Analysis (EDA)

This project is part of my **CodeAlpha Data Analytics Internship**.
I performed Exploratory Data Analysis on the Students Performance in Exams dataset to understand how different factors relate to student scores.

## Dataset
- 1000 students, 8 columns
- Columns: gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score

## Tools Used
- Python
- pandas
- Google Colab

## Steps Performed
1. Loaded the dataset and viewed the first rows (`head`)
2. Checked the shape, data types and summary statistics (`shape`, `info`, `describe`)
3. Checked for missing values and duplicate rows
4. Compared average scores using `groupby` (gender, test preparation course, lunch)

## Key Findings
- The dataset is clean: no missing values and no duplicate rows
- Average scores: Math 66.09, Reading 69.17, Writing 68.05
- Male students scored higher in math; female students scored higher in reading and writing
- Students who completed the test preparation course scored higher on average in all three subjects

## How to Run
1. Open the notebook in Google Colab
2. Upload `StudentsPerformance.csv`
3. Run all cells
