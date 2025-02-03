# 🌍 Happiness Score Prediction using Machine Learning  

## 📌 Project Overview  
This project analyzes global happiness scores using **machine learning** to predict a country's happiness level based on socioeconomic factors such as **GDP, social support, life expectancy, and freedom to make life choices**. It also explores how these factors impact overall happiness.  

## 📊 Dataset  
**Source:** [World Happiness Data 2024 – Kaggle](https://www.kaggle.com/datasets/abdullah0a/world-happiness-data-2024-explore-life/code)  

### Features:  
- **GDP per Capita**  
- **Social Support**  
- **Healthy Life Expectancy**  
- **Freedom to Make Life Choices**  
- **Generosity**  
- **Perceptions of Corruption**  
- **Positive Affect**  
- **Negative Affect**  
- **Happiness Score** *(Target Variable)*  

## 🚀 Models Used & Performance  
| Model                 | MAE  | MSE  | R² Score |
|-----------------------|------|------|----------|
| **Linear Regression** | 0.4216 | 0.3042 | 0.7579 |
| **K-Nearest Neighbors** | 0.3154 | 0.1871 | 0.8511 |
| **Support Vector Regression** | 0.3517 | 0.2142 | 0.8295 |
| **Decision Tree** | 0.3924 | 0.3054 | 0.7569 |
| **Random Forest** (Best) | 0.3100 | 0.1714 | 0.8636 |

### **Best Model: Random Forest**  
- **Hyperparameters:** `{'max_depth': 30, 'min_samples_split': 2, 'n_estimators': 300}`  
- **Updated Performance:**  
  - MAE: `0.3112`  
  - MSE: `0.1742`  
  - R² Score: `0.8613`  

## 🔮 Example Prediction  
Given a **fictional country** with these parameters:  
```json
{
  "GDP": 8.5,
  "Social Support": 0.82,
  "Healthy Life Expectancy": 65.2,
  "Freedom": 0.75,
  "Generosity": 0.02,
  "Corruption": 0.7,
  "Positive Affect": 0.65,
  "Negative Affect": 0.25
}
```
**Predicted Happiness Score: `5.2186`**  

## 📌 Future Improvements  
- Fine-tune hyperparameters for better accuracy.  
- Test with additional datasets for improved generalization.  
- Explore deep learning models for predictions.  

📌 **GitHub Repository:** [Happiness Score Prediction](https://github.com/Yashaswini0110)  
