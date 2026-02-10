# ❤️ Heart Disease Prediction using Machine Learning  

> A machine learning project to predict heart disease by comparing multiple classification algorithms and selecting the most reliable model.

---

## ✨ Project Highlights
- Implemented **5 Machine Learning models**
- Compared models using **Train Accuracy, Test Accuracy & CV Score**
- Identified the **best-performing and well-generalized model**
- Clean and beginner-friendly implementation

---

## 📁 Repository Structure
├── Cpro.ipynb # Complete Jupyter Notebook
├── README.md # Project documentation


---

## ⚙️ Algorithms Implemented
- 🔹 K-Nearest Neighbors (KNN)
- 🔹 Support Vector Classifier (SVC)
- 🔹 Decision Tree (DT)
- 🔹 Random Forest (RF)
- 🔹 Logistic Regression (LR)

---

## 📊 Model Performance Comparison

| Algorithm | Train Accuracy | Test Accuracy | CV Score |
|---------|---------------|--------------|----------|
| KNN | 0.88 | 0.79 | 0.74 |
| **SVC** | 0.85 | **0.83** | 0.74 |
| DT | 0.79 | 0.71 | 0.74 |
| RF | **1.00** | **0.83** | 0.74 |
| LR | 0.85 | 0.82 | 0.74 |

---

## 🏆 Best Model: Support Vector Classifier (SVC)
- High test accuracy  
- Balanced training and testing performance  
- Minimal overfitting  
- Strong generalization ability  

Although Random Forest achieved perfect training accuracy, it showed signs of **overfitting**. SVC proved to be more reliable.

---

## 📝 Conclusion
This project demonstrates how different machine learning algorithms perform on a heart disease dataset. Based on evaluation metrics, **Support Vector Classifier (SVC)** emerged as the most reliable model due to its balanced accuracy and generalization performance.

---

## 🛠️ Tech Stack
- 🐍 Python  
- 📊 Pandas & NumPy  
- 📈 Matplotlib & Seaborn  
- 🤖 Scikit-learn  

---

## 🚀 Future Enhancements
- Hyperparameter tuning  
- Feature selection & scaling  
- Try advanced models (XGBoost, Gradient Boosting)  
- Deploy using Flask or Stream.
