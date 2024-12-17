# Titanic Survival Prediction - Machine Learning Project

## Overview
This project predicts the chances of surviving the Titanic's maiden voyage using Machine Learning (ML) techniques. The prediction is based on various factors such as age, gender, ticket class, and other relevant passenger details. The dataset used is the well-known Titanic dataset, often employed to demonstrate classification problems in ML.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Modeling](#modeling)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The Titanic dataset contains details of passengers aboard the RMS Titanic, including:
- Survival (0 = No, 1 = Yes)
- Passenger class (1st, 2nd, 3rd)
- Name
- Gender
- Age
- Siblings/spouses aboard
- Parents/children aboard
- Fare

The dataset is publicly available and can be downloaded from [Kaggle](https://www.kaggle.com/c/titanic/data).

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Features
The following features were used for building the prediction model:
- **Pclass**: Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex**: Gender (male, female)
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Fare paid for the ticket
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Modeling
The following steps were undertaken:
1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Scaling numerical features
2. **Model Training**:
   - Models used: Logistic Regression, Random Forest, Decision Tree, and Support Vector Machines (SVM).
   - Cross-validation to avoid overfitting.
3. **Evaluation**:
   - Accuracy
   - Precision, Recall, and F1-Score
   - Confusion Matrix

## Results
- The **Random Forest Classifier** achieved the highest accuracy with the following metrics:
  - Accuracy: 82%
  - Precision: 80%
  - Recall: 75%
- Key observations:
  - Women and children had a higher probability of survival.
  - Passengers in 1st class had better survival chances.

## Installation
Follow these steps to run the project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd titanic-survival-prediction
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the project:
   ```bash
   python main.py
   ```

## Usage
1. Add the Titanic dataset (CSV file) in the project directory.
2. Run the script to train and evaluate the ML model.
3. Modify the code to experiment with different models or parameters.
4. Visualize the results with graphs for further insights.

## Contributing
Contributions are welcome! If you'd like to improve the code, fix issues, or add new features:
- Fork the repository.
- Create a new branch.
- Commit your changes.
- Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---
Thank you for checking out the Titanic Survival Prediction project! 🚢

