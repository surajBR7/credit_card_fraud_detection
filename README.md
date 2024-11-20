# Credit Card Fraud Detection

This project is focused on detecting fraudulent transactions using machine learning techniques. It involves data preprocessing, normalization, and the implementation of a Decision Tree Classifier to classify transactions as fraudulent or genuine.

## Dataset

The dataset consists of credit card transactions with features including transaction amount and other anonymized variables. Key details:
- **Total records:** 2,848,070
- **Features:** 31 (including target variable)

## Project Overview

1. **Data Exploration:**
   - Visualization of transaction amounts.
   - Statistical analysis of transaction amounts to understand their distribution.

2. **Data Preprocessing:**
   - Standardization of feature values.
   - Normalization using L1 norm.
   - Handling class imbalance using computed sample weights.

3. **Model Training and Evaluation:**
   - Splitting the dataset into training and testing sets (70% training, 30% testing).
   - Implementation of a Decision Tree Classifier using Scikit-Learn.
   - Calculation of ROC-AUC score for model evaluation.

## Dependencies

The following Python libraries are used in this project:
- `numpy`
- `pandas`
- `matplotlib`
- `sklearn`

Install the dependencies using:
```bash
pip install numpy pandas matplotlib scikit-learn
```
## Steps to Run the Notebook

1. **Clone the repository:**
   ```bash
   git clone https://github.com/surajBR7/credit_card_fraud_detection.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd credit_card_fraud_detection
   ```
3. **Open the notebook:**
   ``` jupyter notebook CCFD.ipynb
   ```
4. **Run the cells sequentially.**


## Results
- Highest Transaction Amount: $25,691.16
- Lowest Transaction Amount: $0.00
- 90% of Transactions: Have an amount ≤ $203.00
- Model Performance:
  - ROC-AUC Score: 0.966
  - Training Time: ~38 seconds
  - 
## Repository Structure
- CCFD.ipynb: Jupyter Notebook containing the implementation.
- README.md: Project documentation (this file).

## future work
- Explore advanced models such as Random Forest, XGBoost, or Neural Networks.
- Investigate feature engineering techniques for improved classification.
- Implement real-time fraud detection using this model.

## Author

Replace `Suraj B R` and `credi_card_fraud_detection` with your GitHub username and repository name. Replace "Your Name" with your name. This format is ready to copy and paste into your `README.md` file!
