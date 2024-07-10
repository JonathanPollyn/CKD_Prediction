# Chronic Kidney Disease Prediction

## Overview
This project's objective is to forecast chronic kidney disease (CKD) by employing diverse machine-learning models. The dataset, acquired from Kaggle, comprises attributes such as blood pressure, specific gravity, albumin, sugar, red blood cells, blood urea, serum creatinine, sodium, potassium, hemoglobin, white blood cell count, red blood cell count, and hypertension status..

## Features
- **Blood Pressure (Bp)**: Blood pressure level
- **Specific Gravity (Sg)**: Measure of urine concentration
- **Albumin (Al)**: Protein level in urine
- **Sugar (Su)**: Sugar level in urine
- **Red Blood Cells (Rbc)**: Count of red blood cells
- **Blood Urea (Bu)**: Urea level in blood
- **Serum Creatinine (Sc)**: Creatinine level in blood
- **Sodium (Sod)**: Sodium level in blood
- **Potassium (Pot)**: Potassium level in blood
- **Hemoglobin (Hemo)**: Hemoglobin level in blood
- **White Blood Cell Count (Wbcc)**: Count of white blood cells
- **Red Blood Cell Count (Rbcc)**: Count of red blood cells
- **Hypertension (Htn)**: Hypertension status
- **Class**: CKD status (1 for CKD, 0 for non-CKD)

## Results
The project involves comparing various machine learning models, including Logistic Regression, Decision Tree, Random Forest, SVM, K-Nearest Neighbors, Naive Bayes, Gradient Boosting, AdaBoost, and XGBoost. The XGBoost model demonstrated its robustness in predicting CKD with a test accuracy of 98.75%.

### Feature Importance
The feature importance analysis identified hemoglobin, serum creatinine, and albumin as the top three crucial predictors of CKD.

## Medium Article
For a detailed explanation of the project, methodologies, and results, please refer to the Medium article: [Predicting Chronic Kidney Disease using Machine Learning]([https://medium.com/your-article-link](https://medium.com/@j.pollyn/predicting-chronic-kidney-disease-using-machine-learning-57941b08f498))

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ckd-prediction.git
    cd ckd-prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook:
    ```bash
    jupyter notebook CKD_Prediction.ipynb
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request.

## Acknowledgements
Special thanks to Kaggle for providing the dataset and the various authors whose work inspired this project.

