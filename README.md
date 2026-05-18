A Random Forest model was developed to predict customer churn with an ROC-AUC of ~0.84 and an F1 score of 0.64. 

Threshold optimisation identified 0.50 as the optimal decision point, balancing recall (0.77) and precision (0.54), ensuring effective identification of at-risk customers while controlling unnecessary retention costs.

Customers were segmented into High, Medium, and Low risk groups based on predicted probabilities, enabling targeted retention strategies. SHAP analysis revealed that tenure, contract type, and monthly charges are the primary drivers of churn.

This solution supports proactive customer retention, reduces churn risk, and improves resource allocation efficiency.