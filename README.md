# Loan_Approval_Prediction

# Loan Approval Prediction Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Data Source](#data-source)
4. [Key Features](#key-features)
5. [Methodology](#methodology)
6. [Results and Insights](#results-and-insights)
7. [Setup Instructions](#setup-instructions)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Project Overview
This project aims to predict loan approval statuses using applicant data. By implementing advanced machine learning models, this project helps lending institutions streamline their loan approval process. The analysis focuses on identifying key factors influencing approval decisions and delivering actionable insights.

## Technologies Used
- **Python**: For data preprocessing, model training, and evaluation.
- **Jupyter Notebook**: For interactive data analysis and experimentation.
- **Libraries**: pandas, NumPy, scikit-learn, matplotlib, seaborn, joblib.
- **Power BI**: For creating interactive dashboards and visualizations.

## Data Source
The dataset used in this project contains the following fields:
- Applicant Income
- Co-applicant Income
- Loan Amount
- Credit History
- Loan Term
- Loan Status (Target Variable)

This dataset was sourced from an open Kaggle competition and can be found in the `data` folder of this repository.

## Key Features
1. Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
2. Exploratory Data Analysis (EDA): Visualizing trends and relationships in the data.
3. Model Building: Implementing Logistic Regression, Random Forest, and XGBoost.
4. Model Evaluation: Using metrics such as accuracy, precision, recall, and F1-score.
5. Deployment Ready: Saving the trained model using `joblib` for future use.

## Methodology
The project follows these steps:
1. **Data Preprocessing**: Clean and prepare the data for analysis.
2. **EDA**: Understand data distribution and feature importance.
3. **Model Training**: Train multiple machine learning models and tune hyperparameters.
4. **Evaluation**: Select the best model based on performance metrics.
5. **Visualization**: Use Power BI to create dashboards for insights.

## Results and Insights
- **Accuracy**: 85%
- **Precision**: 80%
- **Recall**: 78%
- **Key Insights**:
  - Applicants with a clear credit history and higher income levels have higher approval chances.
  - Loan Amount and Credit History significantly influence approval decisions.

## Setup Instructions
To replicate this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/loan-approval-prediction.git
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   - Open the notebook in your Jupyter environment.
   - Execute all cells sequentially to preprocess data, train models, and evaluate performance.

4. **Power BI Dashboard**:
   - Open Power BI Desktop.
   - Import the processed data and create interactive dashboards using the provided `.pbix` file.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additional features.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For inquiries or suggestions, reach out to:
- **Email**: aadarshsrivastav08@gmail.com
- **GitHub Profile**: [https://github.com/aadarshkumar11](https://github.com/aadarshkumar11)
