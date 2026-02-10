❤️ Heart Disease Prediction Using Machine Learning
📌 Overview

This project predicts the presence of heart disease using multiple machine learning classification algorithms.
Different models are trained and evaluated to determine the most reliable model based on performance metrics.

📂 Repository Structure
├── Cpro.ipynb        # Jupyter Notebook containing full implementation
├── README.md        # Project documentation

⚙️ Machine Learning Algorithms Used

K-Nearest Neighbors (KNN)

Support Vector Classifier (SVC)

Decision Tree (DT)

Random Forest (RF)

Logistic Regression (LR)

📊 Model Evaluation Metrics

Models were compared using:

Training Accuracy

Testing Accuracy

Cross-Validation (CV) Score

🔍 Performance Comparison
Algorithm	Train Accuracy	Test Accuracy	CV Score
KNN	0.88	0.79	0.74
SVC	0.85	0.83	0.74
DT	0.79	0.71	0.74
RF	1.00	0.83	0.74
LR	0.85	0.82	0.74
🏆 Best Model

Support Vector Classifier (SVC) is selected as the best model because:

High test accuracy

Balanced training and testing performance

Minimal overfitting compared to Random Forest

Strong generalization capability

📝 Conclusion

The results show that Support Vector Classifier (SVC) provides the most reliable performance for heart disease prediction. While Random Forest achieved perfect training accuracy, it showed signs of overfitting. SVC maintains a strong balance between accuracy and generalization, making it the most suitable model for this dataset.

🛠️ Technologies & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🚀 Future Scope

Hyperparameter tuning

Feature selection and scaling

Try advanced ensemble models

Model deployment using Flask or Streamlit
