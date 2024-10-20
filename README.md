# Loan Approval Prediction

## Project Overview

This project was developed as part of a **Kaggle Competition** in collaboration with my Sudanese friend. The goal of the project was to predict loan approval based on customer data. We utilized various attributes such as customer age, income, credit card ratings, and more. By leveraging past data of approved and rejected loans, we trained a machine learning model that successfully achieved an accuracy of **92.5%** on the testing data, making this a significant success.

## Key Features

- **Data-Driven Predictions**: Predicts whether a loan application will be approved based on historical data.
- **High Accuracy**: Achieved a 92.5% accuracy on the testing data set.
- **Multi-Feature Analysis**: Considers several customer factors such as age, income, credit history, and more.

## Technologies Used

We used a variety of technologies and tools for this project:

- **Python**: Core programming language for data analysis and model implementation.
- **Pandas**: For efficient data manipulation and preprocessing.
- **NumPy**: For numerical computations.
- **Scikit-Learn**: Used to build and train the machine learning models (e.g., Logistic Regression, Decision Trees, etc.).
- **Matplotlib & Seaborn**: For visualizing data patterns and insights.
- **Kaggle API**: To download datasets and submit the results.
- **Jupyter Notebook**: For interactive data exploration and model development.

## Data

The dataset consisted of customer information, including:

- **Age**: The age of the customer.
- **Income**: The customer's annual income.
- **Credit Card Rating**: The credit score or rating of the customer.
- **Loan Amount**: The amount of the loan applied for.
- **Loan History**: Information on previous loans and repayment behavior.
  
Each of these features played a role in determining whether the loan application was approved or rejected.

## Model Implementation

### Steps Involved:

1. **Data Preprocessing**:
   - Handled missing values and performed feature encoding.
   - Scaled numerical values to improve model performance.

2. **Feature Selection**:
   - Selected the most important features using correlation analysis and feature importance metrics.

3. **Model Selection**:
   - Evaluated multiple models, including **Logistic Regression**, **Random Forest**, and **XGBoost**, to find the best-performing one.

4. **Model Training**:
   - Trained the selected models on the training data and used **cross-validation** to fine-tune hyperparameters.

5. **Model Evaluation**:
   - Evaluated the performance of the models on testing data, achieving an accuracy of **92.5%** using the Random Forest model.

## Installation

To run this project on your local machine, follow the instructions below:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repository/loan-approval-prediction.git
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook LoanApprovalPrediction.ipynb
    ```

## Model Performance

- **Accuracy on Testing Data**: 92.5%
- **Precision**: High precision in predicting loan approvals, reducing false positives.
- **Recall**: High recall to ensure legitimate approvals are not missed.
  
The model demonstrated a strong ability to generalize and accurately predict loan approvals, making it a reliable solution.

## Future Improvements

- **Improved Data Balancing**: Further balancing of approved vs. rejected loan data to prevent bias.
- **Integration with Financial Systems**: Expanding the system to be used by financial institutions for real-time loan approval predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributors

- **Ziad Amer** - Lead Data Scientist
- **Yosif Shahin** - Data Analyst and Model Contributor

## Acknowledgments

We thank **Kaggle** for providing the competition platform and dataset, and our mentors who guided us throughout the project.
