# Income Classification Project

## Overview
This project focuses on building and evaluating a machine learning model to classify whether an individual's income exceeds a certain threshold based on demographic and employment-related attributes. The workflow is implemented in a Jupyter Notebook (`income-classification.ipynb`).

## Dataset
The dataset contains demographic and employment-related features such as:
- Age
- Education
- Occupation
- Work hours per week
- Marital status
- Gender
- Native country

The target variable is **income category** (<=50K or >50K).

## Project Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Normalizing numerical features

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Feature importance exploration
   - Correlation checks

3. **Modeling**
   - Different machine learning algorithms tested (e.g., Logistic Regression, Decision Trees, Random Forest, etc.)
   - Hyperparameter tuning
   - Model evaluation using accuracy, precision, recall, and F1-score

4. **Results and Insights**
   - Best performing model identified.(Accuarcy: 83%)
   - Key features influencing income classification

## Requirements
To run the notebook, install the dependencies:

```bash
pip install -r requirements.txt
```

Typical libraries include:
- Python 3.10
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage
1. Clone this repository:  
   ```bash
   git clone <repo_url>
   cd <repo_name>
   ```
2. Install dependencies with `pip install -r requirements.txt`.  
3. Open and run the notebook:  
   ```bash
   jupyter notebook income-classification.ipynb
   ```

## Future Work
- Try advanced models (XGBoost, LightGBM, Neural Networks).  
- Perform feature engineering to improve performance.  
- Deploy the model as a web API for real-time predictions.  

## License
This project is provided for educational purposes. You are free to use and adapt it.
