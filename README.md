Customer Churn Prediction
This project focuses on predicting customer churn using machine learning. By analyzing customer behavioral and demographic data, the model identifies which customers are likely to leave, helping businesses take proactive retention actions.

✅ Model Performance
Accuracy: 90%

Sensitivity (Recall for Churn): 55.6%

Specificity (Recall for Non-Churn): 96.8%

These results indicate the model is very effective at identifying customers who are likely to stay, and moderately effective at identifying customers who are likely to churn.

📌 Highlights
Classification model built using customer data

Preprocessing includes encoding, scaling, and balancing techniques

Evaluation metrics: Accuracy, Sensitivity, Specificity, Confusion Matrix

Built using Python in Jupyter Notebook

📁 Project Structure
Copy
Edit
📦Customer-Churn-Prediction
 ┣ 📜customer-churn-dkp.ipynb
 ┣ 📜churn_dataset.csv
 ┗ 📜README.md
🛠 Dependencies
Make sure to install the following Python packages:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn
📈 Future Improvements
Improve sensitivity with advanced techniques like SMOTE or cost-sensitive learning

Try ensemble models (e.g., XGBoost, Random Forest)

Deploy the model as an API for real-time churn predictio
