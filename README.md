📘 Machine Learning for Credit Risk Prediction
Improving Lending Decisions with XGBoost, Decision Trees, and Clustering

This project applies machine learning techniques to classify borrower credit risk and improve lending decision outcomes. Using supervised and unsupervised learning methods, I explored how predictive models can identify high-risk borrowers before loan approval, reducing default rates and enhancing portfolio performance.

This work was completed as the final project for STA 419 – Applied Statistics & Machine Learning.

🔍 Project Objectives

Build predictive models to classify borrower credit risk

Compare performance across multiple ML approaches

Understand which financial behaviors drive risk

Communicate results with both technical and business impacts

Provide reproducible R code for transparency and learning

📂 Files in This Repository
File	Description
FinalProject.Rmd	Full R Markdown with code, models, visuals, and explanations
FinalProject.html	Rendered HTML report version
Slides.pdf (optional if you upload later)	LinkedIn carousel / presentation deck
/images (optional folder)	Exported charts / confusion matrices
⚙️ Machine Learning Methods Used
✔ Supervised Models
Model	Purpose
K-Nearest Neighbors	Baseline classifier
Decision Tree	Transparent rule-based model
XGBoost	High-performance gradient boosting method

➡ XGBoost achieved the strongest balance between accuracy & identifying high-risk borrowers.

✔ Unsupervised Learning
Method	Purpose
PCA	Dimensionality reduction
K-means Clustering	Exploratory borrower grouping

➡ PCA results showed risk is influenced by many factors, not a single driver.

📊 Key Insights & Results

Borrower risk does not naturally separate into clear groups — supervised learning is required

Decision Trees provide useful interpretability but may overfit

XGBoost outperformed other models, reducing misclassified risky borrowers

Loan amount, duration, and credit history were among the strongest predictors

🧠 Technologies Used
Tool / Library	Purpose
R (tidyverse)	Data preparation
caret	Training & evaluation
xgboost	Gradient boosting
DMwR	KNN and modeling utilities
ggplot2	Visualizations
▶ How to Run the Code

1️⃣ Download the repository
2️⃣ Open FinalProject.Rmd in RStudio
3️⃣ Install required libraries (listed in the RMD header)
4️⃣ Knit to HTML or PDF

🧾 Business Impact

Accurate credit risk prediction allows lenders to:

Reduce loan defaults

Price risk more effectively

Improve approval confidence

Enhance portfolio stability

🚀 Future Improvements

Hyperparameter tuning for all models

Add neural networks or LightGBM

More financial features (DTI, income, payment history)

Deploy a real-time scoring API

📬 Contact & Links

👤 Your Name
📧 Email: [your email]
🔗 LinkedIn: [your LinkedIn]
🗂 Full report shared on LinkedIn: (if posting)# credit-risk-ml-project
