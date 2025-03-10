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

### Model Development & Exploration  
- **Linear Regression**  
- **Random Forest Regression**  

### Model Evaluation  
- **Metrics Used:**  
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  
  - Coefficient of Determination (R²)
 
### Key Insights & Results  

**Feature Selection Improves Model Efficiency:**  
We identified the top 20 CpG sites that retain predictive power, reducing model complexity without compromising accuracy.  

**Best Model Performance:**
The Linear Regression model achieved the highest accuracy with an MAE of **X** years, outperforming the baseline Linear Regression methods.  

**Biological Relevance:**  
The most predictive CpG sites were associated with known ageing-related genes, aligning with epigenetic clock research.  
