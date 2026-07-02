# Student Performance Analysis

## Project Overview
This project analyzes **student performance data** to understand which factors affect academic scores, identify **at-risk students**, and provide actionable recommendations that can help improve outcomes in the next academic year.

The analysis was completed as part of **Project 02 – Student Performance Analysis** from the **Pluto Academy Data Analytics Internship Program**. The project focuses on exploratory data analysis (EDA), factor analysis, at-risk student segmentation, and reporting insights in a clear and structured format.

---

## Problem Statement
A school principal wants to understand:
- which factors affect student grades,
- whether test preparation improves performance,
- how parental education influences scores,
- which student groups are more at risk academically,
- and what actions the school can take to improve student outcomes.

This project answers those questions using student exam performance data.

---

## Dataset
The dataset used is **Students Performance in Exams**, which contains **1000 student records** and **8 columns** related to demographics, parental background, preparation habits, and subject scores.

### Key Features in the Dataset
- **gender**
- **race/ethnicity**
- **parental level of education**
- **lunch**
- **test preparation course**
- **math score**
- **reading score**
- **writing score**

---

## Project Objectives
The main objectives of this project were to:

1. Explore and clean the dataset
2. Analyze factors affecting student performance
3. Create visualizations to support findings
4. Identify and segment **at-risk students**
5. Prepare a principal-style report with actionable recommendations

---

## Tools & Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## Files in This Repository
- **`Student_performance.ipynb`** → Jupyter notebook containing the full analysis and visualizations  
- **`StudentsPerformance(1).csv`** → dataset used for the project  
- **`README.md`** → project documentation  

---

## Analysis Performed

### 1. Data Exploration & Cleaning
- Loaded the dataset and checked shape, data types, and null values
- Understood the meaning of each column
- Created summary observations of the dataset
- Prepared the data for analysis

### 2. Factor Analysis
The notebook answers the following questions:
- Does **parental level of education** affect student scores?
- Do students who complete the **test preparation course** score higher?
- What is the correlation between **math, reading, and writing scores**?
- Which **gender** performs better in which subject?
- What is the **distribution of total scores**?

### 3. Visualizations
The project includes multiple charts to support analysis, such as:
- **Box plot** – scores by parental education
- **Bar chart** – test preparation comparison
- **Correlation heatmap**
- **Grouped bar chart** – gender vs subject performance
- **Histogram** – total score distribution
- **Scatter plot** – reading score vs math score

### 4. At-Risk Student Segmentation
Students were classified as **at-risk** based on low academic performance (for example, scoring below a chosen threshold in one or more subjects).  
The project then identifies:
- total number of at-risk students
- groups with the highest at-risk percentage
- possible reasons behind poor performance

### 5. Principal’s Report
A report-style summary was created in the notebook containing:
- an executive summary
- key findings
- actionable recommendations for the school

---

## Key Insights
Some of the major insights from the analysis include:

- **Test preparation course completion is associated with better academic performance**, especially across reading and writing scores.
- **Parental level of education shows a noticeable relationship with student scores**, indicating the importance of academic environment and support at home.
- **Reading and writing scores are strongly positively correlated**, suggesting that students who perform well in one language-based subject often perform well in the other.
- **Performance differs across student groups**, including gender and other background-related categories.
- A meaningful share of students can be classified as **at-risk**, making early intervention important.

---

## Business / School Recommendations
Based on the analysis, the following recommendations can help improve student outcomes:

1. **Encourage structured test preparation programs**  
   Students who completed test preparation tend to perform better, so the school should expand access to prep support.

2. **Provide targeted support to at-risk students**  
   Students with consistently low scores should be identified early and offered extra classes, mentoring, or academic counseling.

3. **Use parent engagement and awareness programs**  
   Since parental education appears to influence student outcomes, schools can strengthen communication with parents and involve them more in academic planning.

---

## Most Impactful Recommendation
The most impactful recommendation is to **identify at-risk students early and provide targeted academic support**. This is important because it directly addresses students who are most likely to struggle and helps prevent long-term academic decline. With focused intervention such as remedial sessions, mentoring, and test preparation support, the school can improve both student confidence and performance.

---

## Project Workflow
1. Imported libraries and loaded the dataset  
2. Explored data structure, types, and missing values  
3. Performed factor-based analysis on student performance  
4. Built visualizations to compare groups and understand score patterns  
5. Segmented at-risk students  
6. Summarized findings and recommendations in report format  

---

## How to Run the Project
1. Clone this repository
2. Open `Student_performance.ipynb` in Jupyter Notebook / JupyterLab / VS Code
3. Make sure the dataset file `StudentsPerformance(1).csv` is in the same folder
4. Run the notebook cells in order to reproduce the analysis and visualizations

---

## Conclusion
This project demonstrates how exploratory data analysis can be used to uncover the factors that influence student performance and help schools make better academic decisions. By combining score analysis, student segmentation, and visual reporting, the project provides practical insights that can support better planning, intervention, and student success.

---

## Author
**Aditya Singh**  
MANIT Bhopal  
