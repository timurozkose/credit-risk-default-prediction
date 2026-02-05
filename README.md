# credit-risk-default-prediction
In this project, I built an end-to-end machine learning pipeline to predict loan default risk using borrower and loan characteristics. The main objective was to support data-driven credit decision-making by estimating the probability that a borrower will default on a loan. Credit risk assessment is a central problem in banking and financial institutions, as incorrect lending decisions can lead to significant financial losses or missed revenue opportunities.

I worked with real-world consumer loan data that included borrower demographics, credit history, and loan-specific attributes. The project began with extensive data cleaning and preprocessing, including handling missing values, correcting data types, and removing features that could cause data leakage. Special attention was given to ensuring that only information available at the time of loan approval was used for prediction, which is critical in real financial applications.

After preprocessing, I conducted exploratory data analysis (EDA) to understand variable distributions, class imbalance, and relationships between features and default behavior. Since loan default datasets are naturally imbalanced, I evaluated performance using appropriate metrics such as ROC-AUC, precision, recall, and confusion matrices, rather than relying only on accuracy.

For modeling, I compared interpretable statistical models with tree-based machine learning methods. Logistic regression was used as a baseline model to provide transparency and interpretability, allowing me to examine how individual features contribute to default risk. I then implemented tree-based models, such as Random Forest or Gradient Boosting, to capture non-linear relationships and improve predictive performance. Model results were compared to highlight trade-offs between interpretability and predictive power.

Beyond technical performance, I framed the results from a business perspective, emphasizing the financial impact of false positives and false negatives in credit decisions. This helped demonstrate how model thresholds can be adjusted depending on an institution’s risk tolerance.

Overall, this project demonstrates my ability to apply machine learning, statistics, and financial reasoning to a real-world risk management problem, combining technical rigor with practical business insights.
