
# Water Quality Prediction Using Machine Learning

This project focuses on predicting water quality using machine learning techniques by analyzing various physicochemical parameters of water. The goal is to determine whether water is potable (safe for drinking) and to study the influence of different parameters on overall water quality.

The project was developed as part of an **Implant Training Program in Machine Learning** at **Approtech R&D Solutions Pvt. Ltd.**.

---

## Project Overview

Water quality assessment is a critical task in environmental monitoring and public health. Traditional testing methods are time-consuming and require manual analysis. This project leverages machine learning models to automate water quality prediction and provide accurate insights using historical data.

Both **classification** and **regression** approaches are implemented to analyze water quality effectively.

---

## Dataset Description

The project uses the **Water Potability Dataset**, a publicly available dataset commonly used for water quality analysis.

### Features:
- pH  
- Hardness  
- Total Dissolved Solids  
- Chloramines  
- Sulfate  
- Conductivity  
- Organic Carbon  
- Trihalomethanes  
- Turbidity  

### Target Variable:
- **Potability**
  - `0` – Not Potable  
  - `1` – Potable  

---

## Methodology

1. Data loading and exploration  
2. Handling missing values  
3. Feature scaling and preprocessing  
4. Model building for classification and regression  
5. Performance evaluation and comparison  
6. Prediction and result visualization  

---

## Machine Learning Models Used

### Classification Models
- Logistic Regression    
- Random Forest Classifier  
- Support Vector Machine (SVM)   

### Regression Models 
- Random Forest Regressor
- Gradient Boosting Regressor

---

## Evaluation Metrics

### Classification Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  

### Regression Metrics
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

---

## Tools and Technologies

- Python  
- Google Colab  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Google Colab Notebook

The complete implementation and model comparison can be accessed through the Google Colab notebook:

🔗 https://colab.research.google.com/drive/1mX03rVFXFQC8wMwnBnQg3Mm-1A3JEpQf?usp=sharing

---

## Results and Insights

- Machine learning models effectively predicted water potability with reasonable accuracy  
- Ensemble models such as **Random Forest** performed better compared to basic models  
- Regression analysis helped in understanding the impact of individual water parameters  
- The project demonstrates the applicability of ML in environmental monitoring  

---

## Future Enhancements

- Integration with real-time water sensor data  
- Implementation of deep learning models  
- Deployment as a web application  
- Time-series analysis for seasonal water quality prediction  

---

## Author

**Santhosh S**  
B.Tech – Information Technology  
Saveetha Engineering College  

---

## Acknowledgements

- Approtech R&D Solutions Pvt. Ltd.  
- Water Potability Dataset (Public Source)  
- Mentors and faculty for guidance and support  
