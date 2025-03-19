# Titanic Dataset Analysis and Survival Prediction  

## Overview  
The Titanic dataset is widely used for machine learning practice, focusing on predicting passenger survival based on various features such as age, class, and gender. This project applies **data preprocessing techniques** and trains a **Logistic Regression model** to classify whether a passenger survived or not.  

---

## Workflow and Methodology  

### 1. **Handling Missing Values**  
- The **Age** column contained missing values, which were filled with the **mean age within each Pclass (Passenger Class)** to maintain accuracy in data distribution.  

### 2. **Encoding Categorical Variables**  
- Categorical columns such as **Sex** and **Embarked** were converted into numerical representations using encoding techniques, making them suitable for model training.  

### 3. **Dropping Unnecessary Columns**  
- Columns that were not useful for prediction, such as **Passenger ID, Name, Ticket, and Cabin**, were removed to reduce noise and improve model performance.  

### 4. **Model Selection and Training**  
- The dataset was split into **training and testing sets** using **train_test_split**.  
- **Cross-validation** was applied to ensure robustness.  
- A **Logistic Regression model** was trained to predict **survival probability**.  

### 5. **Model Performance Evaluation**  
- The trained model was evaluated, achieving an accuracy score of **0.8034 (80.34%)**.  

---

## Key Takeaways  
- **Missing values were handled strategically** by imputing the mean age within each Passenger Class.  
- **Feature Engineering**: Converting categorical data into numerical values improved model learning.  
- **Logistic Regression** was effective, achieving a classification accuracy of **80.34%**, indicating strong predictive performance on survival outcomes.  

