Education Data Visualization
This project explores and visualizes data from U.S. colleges and universities to uncover insights about student success, institutional expenditures, and academic characteristics using techniques like PCA and t-SNE.

 Context
The dataset encompasses rich metrics across admissions, academics, student demographics, faculty qualifications, and institutional spending. These variables are critical for policymakers, educational analysts, and institutional leaders aiming to enhance student outcomes and optimize resource allocation in higher education.

 Objective
The project aims to explore the relationships between institutional variables and student success indicators through visualizations and dimensionality reduction. Key goals include:

Identifying factors strongly associated with higher graduation rates

Comparing characteristics such as faculty qualifications and student/faculty ratios

Detecting patterns or anomalies in expenditure, student demographics, and outcomes

Offering actionable insights for improving educational strategy

Dataset Overview
The dataset contains 777 U.S. colleges with the following features:

Feature	Description
Apps, Accept, Enroll	Applications received, accepted, and students enrolled
Top10perc, Top25perc	Percentage of top-ranking incoming students
F_Undergrad, P_Undergrad	Full-time and part-time undergrad counts
Outstate, Room_Board, Books, Personal	Student-related costs
PhD, Terminal	Faculty qualification metrics
S_F_Ratio	Student/faculty ratio
perc_alumni	Alumni donation percentage
Expend	Instructional expenditure per student
Grad_Rate	Graduation rate

 Data Cleaning & Preprocessing
Confirmed all college names are unique; dropped the Names column

Capped percentage variables (PhD, Grad_Rate) at 100%

Skewness and outliers were observed but retained for exploratory analysis

Standardized features using StandardScaler before PCA and t-SNE

Exploratory Data Analysis
Strong correlations between:

Applications, Acceptances, Enrollments, Full-time Students

Top 10% and Top 25% Students

PhD and Terminal Degrees

Negative correlation between:

Student/Faculty Ratio and Top Students, Outstate Tuition

 Principal Component Analysis (PCA)
Reduced dimensionality from 17 features to 4 principal components capturing >70% variance

PCA Components:

Component	Theme	Description
PC1	Elite Academics	Selectivity, high out-of-state, faculty quality, expenditures
PC2	Large & Accessible	Enrollment volume, wide access
PC3	Student Costs & Support	Spending, faculty attention
PC4	Graduation Success	Outcome-driven institutions

 Scree plot and explained variance visuals included
t-SNE Visualization
Performed t-SNE in 2D and 3D

Visualized data for multiple perplexity values (10–45)

No distinct clustering observed; data is continuous and complex

Key Takeaways
High spending and faculty quality align with strong outcomes, but aren't sole predictors

Institution size does not inherently reduce student success

PCA themes help distill educational strategies into interpretable clusters

t-SNE reaffirms the complexity and nuance of institutional performance

