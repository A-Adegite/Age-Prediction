# Epigenetic Age Prediction using Machine Learning
## Overview
Ageing is more than just a number. It's a biological process influenced by genetics, environment, and epigenetics. This project leverages machine learning to predict an individual's age based on DNA methylation data from 27,578 CpG sites. This approach has applications in biomedical research, precision medicine, and longevity studies. Unlike traditional age estimators, this model identifies patterns in epigenetic markers to assess cellular ageing more accurately.

##  Why It Matters
DNA methylation-based age prediction has applications in biological ageing research, forensics, and health diagnostics. Optimizing these models can improve ageing studies and personalized medicine.

## Methodology
Link to dataset: https://drive.google.com/file/d/1-2eE_YfqDO7uow5W-MQOubifqsm1xSNx/view?usp=drive_link

### Data Preprocessing  

### Feature Selection & Engineering  
- **Feature Selection:** Recursive Feature Elimination (RFE)  

### Model Exploration  & Development 
- **Linear Regression**  
- **Random Forest Regression**  

### Model Evaluation  
- **Metrics Used:**  
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  
  - Coefficient of Determination (R²)
 
### Key Insights & Results  

Feature selection identified the top 20–30 CpG sites that retained predictive power, significantly reducing model complexity without compromising accuracy. By focusing on these most informative features 
## Best Model Performance  

The Linear Regression model achieved the highest accuracy, with an **MAE (Mean Absolute Error) of 7.3 years**, outperforming the **Random Forest Regression model** and other baseline approaches.  

| Model              | MSE   | RMSE  | R² Score | MAE  |
|--------------------|------|------|----------|------|
| **Linear Regression** | **97.66** | **9.88** | **0.87** | **7.3** |
| **Random Forest** | 122.38 | 11.06 | 0.84 | 8.5 |

These results highlight the effectiveness of using a **simpler, more interpretable model** (Linear Regression) for **DNA methylation-based age prediction**, while avoiding unnecessary computational complexity. 🚀  


