# Upgrad----E-Commerce-Retail-B2B-Case-Study

### Overview
This case study focuses on analyzing customer payment patterns for Schuster, a global retail company specializing in sports equipment and accessories. The objective is to forecast delayed payments on open invoices, enabling more strategic collection efforts and improved financial management.
Problem Statement
Schuster collaborates with numerous vendors under credit terms. Despite penalties for late payments, vendors often fail to comply with payment deadlines, leading to strained relationships and additional resource expenditure. The company aims to:
•	Analyze historical payment data to identify behavioral trends.
•	Predict delayed payments for outstanding invoices.

### Goals
1.	Predict delays in payment for pending invoices.
2.	Equip collection teams with prioritized follow-up lists.
3.	Generate insights to streamline payment processes and reduce delays.

### Approach
The project methodology includes:
1.	Exploratory Data Analysis (EDA):
o	Observed a skewed distribution of transaction amounts, with a majority concentrated at lower values.
o	Identified significant outliers among transaction amounts.
o	Examined customer segmentation based on payment behavior.
2.	Model Evaluation:
o	Constructed a predictive model with a cutoff value of 0.6.
o	Evaluated performance using an AUC score, which demonstrated acceptable accuracy.
3.	Insights and Recommendations:
o	Recommended tighter payment policies for invoice categories with higher delays.
o	Suggested focused strategies for goods-related invoices, given their higher probability of late payments.
o	Proposed penalties for late payments, emphasizing smaller transaction amounts.
o	Highlighted the importance of proactive engagement with high-risk customer segments.

### Key Findings
•	Invoice Class Policies: Credit-related invoices have the highest delay rates.
•	Goods vs. Non-Goods: Delays are more common for goods invoices compared to services.
•	Customer Segmentation: Customers were grouped into three clusters:
o	Cluster 0: Medium payment duration.
o	Cluster 1: Prolonged payment duration.
o	Cluster 2: Early payment duration.
•	High-Probability Customers: Customers with high delay likelihood and significant overdue amounts should be prioritized.

### Recommendations
1.	Invoice Class Policies: Strengthen collection policies for high-risk invoice types.
2.	Targeted Strategies: Design specific follow-up plans for high-risk clusters.
3.	Low-Value Penalties: Introduce penalties for smaller invoices to deter delays.
4.	Goods Invoices: Apply stricter payment terms for goods transactions.

### Files in Repository
•	E-Commerce & Retail B2B Case Study.pptx: Presentation summarizing the project’s problem, approach, and outcomes.
•	E-Commerce & Retail B2B Case Study - FINAL.ipynb: Jupyter notebook containing analysis, modeling, and results.

### How to Use
1.	Clone the repository:
git clone <repository-url>
2.	Open the Jupyter notebook to review the analysis and model:
jupyter notebook "E-Commerce & Retail B2B Case Study - FINAL.ipynb"
3.	Refer to the presentation for a concise overview.

### Tools and Technologies

•	Python for data processing and modeling.

•	Pandas and NumPy for data handling.

•	Matplotlib and Seaborn for visual analytics.

•	Scikit-learn for predictive analysis.

•	Jupyter Notebook for executing the workflow.

# Contributors

•	Chayanika Hazra

•	Bhagyashree Bose

•	Bharat Bhushan 


