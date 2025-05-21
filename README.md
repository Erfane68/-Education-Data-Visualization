Education Data Visualization
This project explores and visualizes data from U.S. colleges and universities to uncover insights about student success, institutional expenditures, and academic characteristics using techniques like PCA and t-SNE.

Objective
The project aims to explore the relationships between institutional variables and student success indicators through visualizations and dimensionality reduction. Key goals include:

Identifying factors strongly associated with higher graduation rates

Comparing characteristics such as faculty qualifications and student/faculty ratios

Detecting patterns or anomalies in expenditure, student demographics, and outcomes

Offering actionable insights for improving educational strategy

Dataset Overview
The dataset contains 777 U.S. colleges with the following features:


Principal Component Analysis (PCA)
Reduced dimensionality from 17 features to 4 principal components capturing >70% variance

PCA Components:

Component	Theme	Description
PC1	Elite Academics	Selectivity, high out-of-state, faculty quality, expenditures
PC2	Large & Accessible	Enrollment volume, wide access
PC3	Student Costs & Support	Spending, faculty attention
PC4	Graduation Success	Outcome-driven institutions


t-SNE Visualization
Performed t-SNE in 2D and 3D

Visualized data for multiple perplexity values (10–45)

No distinct clustering observed; data is continuous and complex

Key Takeaways
High spending and faculty quality align with strong outcomes, but aren't sole predictors

Institution size does not inherently reduce student success

PCA themes help distill educational strategies into interpretable clusters

t-SNE reaffirms the complexity and nuance of institutional performance

