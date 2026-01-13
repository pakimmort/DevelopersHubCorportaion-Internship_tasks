# Heart Disease Prediction

## Task 3: Heart Disease Prediction

### Objective
The goal of this project is to build a predictive model that can determine whether a person is at risk of developing heart disease based on their health-related data. Early prediction can help in timely interventions and better healthcare management.

### Dataset
The dataset used is the **Heart Disease UCI Dataset**, which is publicly available on [Kaggle](https://www.kaggle.com/). The dataset contains various attributes such as age, sex, blood pressure, cholesterol, and other health metrics relevant to heart disease prediction.

**Key Features Include:**
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression
- Slope of peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia

**Target Variable:**
- `target` — Indicates presence (`1`) or absence (`0`) of heart disease.

### Project Instructions
The following steps were undertaken to build the predictive model:

1. **Data Cleaning**  
   - Checked for missing values and inconsistencies.  
   - Imputed or removed missing data if necessary.  
   - Converted categorical variables into numerical form using encoding techniques.

2. **Exploratory Data Analysis (EDA)**  
   - Explored feature distributions and correlations.  
   - Visualized relationships between features and the target variable.  
   - Identified important features that influence heart disease risk.

3. **Model Training**  
   - Built classification models including **Logistic Regression** and **Decision Tree**.  
   - Split the dataset into training and testing sets for evaluation.  

4. **Model Evaluation**  
   - Assessed model performance using:  
     - **Accuracy**  
     - **Confusion Matrix**  
     - **ROC Curve and AUC**  

5. **Feature Importance**  
   - Determined which features most strongly impact the prediction of heart disease.  

### Tools and Libraries
- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
