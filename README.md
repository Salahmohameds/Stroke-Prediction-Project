---

# Stroke Prediction Project

This project aims to develop a machine learning model that predicts the likelihood of stroke in individuals based on health-related factors. It demonstrates the potential of data-driven approaches in healthcare for early stroke detection.

## Overview

- **Goal**: Build a predictive model for stroke risk.
- **Dataset**: Includes features such as age, gender, hypertension, heart disease, smoking status, etc.
- **Technologies**: Python, Scikit-learn, Pandas, Numpy, Matplotlib, Seaborn, Jupyter Notebooks.

## Project Structure

- **stroke_test (2).ipynb**: Contains the exploratory data analysis (EDA), feature engineering, and initial modeling process.
- **stroke prediction (1).ipynb**: Finalized model training, hyperparameter tuning, and performance evaluation.

## Methodology

1. **Data Preprocessing**: 
   - Dealt with missing values by imputing median values for numerical columns and mode for categorical columns.
   - Applied feature scaling using StandardScaler and one-hot encoding for categorical variables.
2. **Exploratory Data Analysis**: 
   - Visualized data distributions using histograms and boxplots.
   - Identified correlations between features and stroke using heatmaps and pairplots.
3. **Modeling**: 
   - Built and tested several models: Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine.
4. **Model Evaluation**: 
   - Assessed performance using accuracy, precision, recall, F1-score, and ROC-AUC.
   - Best model: Random Forest with an AUC-ROC score of 0.89.

## Results

- **Best-performing model**: Random Forest, providing a balance between precision and recall for stroke prediction.
- **Key features influencing stroke risk**: 
  - Age
  - Hypertension
  - Average glucose level
  - Smoking status
  
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stroke-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd stroke-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

- Open and run the Jupyter notebooks to explore the data and models.
- Modify the model parameters or try new models to experiment with different approaches.

## Conclusion

This project demonstrates how machine learning can help predict stroke risks based on key health factors, potentially aiding in early interventions. The Random Forest model showed the best results with an AUC-ROC score of 0.89, making it a useful tool for medical decision support.

## Acknowledgments

Special thanks to the **Digital Egypt Pioneers Initiative (DEPI)** for providing guidance, and to **Ahmed Essam Azab** for mentorship during this project. The dataset was sourced from **Kaggle**.

## License

This project is licensed under the MIT License.

---

