# Student-Placement-Analysis
Student Placement Analysis
Case Study : Student Placement Analysis (B.Tech)

Project Title
B.Tech Student Placement & Career Path Analysis – EDA & Excel Dashboard

Project Objective
To analyse placement outcomes of B.Tech students across branches, understand what
factors drive placement and salary, and compare career choices (job vs higher education)
based on CGPA, branch and internship experience.

Tools & Technologies Used
1. **Python (Pandas, NumPy)** – Data cleaning, feature engineering, EDA
2. **Seaborn & Matplotlib** – Distribution, comparison and correlation visualizations
3. **Excel** – Pivot tables, charts and summary dashboard

Data Overview
- 400 student records across 10 branches
- Key attributes: Student ID, Gender, Branch, 10th %, 12th %, CGPA, Backlogs,
  Internship Done, Placed, Salary LPA, Specialisation, Higher Education

Analysis Performed

Univariate Analysis
- ~65% students placed, 35% unplaced
- AIML, Data Science and AIDS are the most common branches
- Salary distribution right skewed — most between 8–14 LPA

Bivariate Analysis
- Placed students have consistently higher CGPA than unplaced
- AIML, AIDS and Data Science branches have the highest avg salary
- Students with internship experience have 15–20% higher placement rate

Multivariate Analysis
- Correlation heatmap shows CGPA as strongest predictor of salary
- CGPA vs Salary scatter coloured by branch — AIML/DS students cluster
  at top right (high CGPA + high salary)

Excel Dashboard
- Pivot table: placement rate by branch
- Pivot chart: avg salary by branch and gender
- Slicer filters: branch, placed, internship done

Key Insights
- CGPA is the strongest predictor of both placement and salary
- Internship experience significantly boosts placement chances
- AIML and Data Science branches lead in salary — averaging 14–16 LPA
- Civil and Mechanical branches have the lowest placement rates and salaries
- Most students who pursue higher education either have very high CGPA (9+)
  or were not placed

Business Outcomes
- Students can benchmark their CGPA and internship status against placed peers
- Colleges can identify which branches need stronger industry connect
- Recruiters can filter high-value candidate segments by branch and CGPA

What I Learned
- Handling real-world student data with missing salary values (unplaced students)
- Feature engineering academic scores from multiple percentage columns
- Building Excel dashboards with slicers for non-technical audiences
- Deriving career pattern insights from placement and higher education data

