# Hotel-Booking-Cancellation-Prediction
This project analyzes hotel booking records to predict cancellations using supervised machine learning techniques. It provides insights into key features that influence cancellation behavior and builds classification models to help hotels reduce revenue loss.

## Objective 
- Predict whether a hotel booking will be canceled.
- Identify the most important factors influencing cancellations.
- Evaluate and compare different classification models.

## Dataset 
- Source: [Kaggle](https://www.kaggle.com/datasets/youssefaboelwafa/hotel-booking-cancellation-prediction)

## Overall Framework
![Framework Screenshot](https://github.com/user-attachments/assets/6b4f2727-bd7c-4233-ba32-39daa19ddd18)
### 1. Data Preprocessing
- Handled missing values, duplicates, and irrelevant features.
- Encoded categorical variables and normalized continuous features.

### 2. Exploratory Data Analysis (EDA)
- Explored cancellation patterns across different customer segments.
- Visualized trends by country, market segment, hotel type, and deposit type.

### 3. Feature Selection
- Employed Mutual Information to select the most relevant features.
- Reduced dimensionality and eliminated irrelevant variables to improve model performance and efficiency.

### 4. Model Development
- Trained classification models: Random Forest, Fradient Boosting, XGBoost, Decision Tree and Ada Boost
- Evaluated using accuracy, precision, recall, and F1-score.

### 5. Hyperparameter Tuning
- Applied GridSearchCV to find optimal parameters for each model.

## Result
- Best-performing model: **Gradient Boosting**
- Accurary: 84.35%
