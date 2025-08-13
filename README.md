# House Price Prediction ML Project

This project demonstrates a complete machine learning workflow for predicting house prices using the California Housing dataset. The notebook covers data loading, cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and hyperparameter tuning.

## Project Structure

- `code.ipynb` — Main Jupyter notebook with all code and analysis
- `housing.csv` — Dataset file
- `README.md` — Project documentation

## Workflow Overview

1. **Data Loading & Cleaning**
	- Load the dataset from CSV
	- Check and handle missing values
2. **Exploratory Data Analysis (EDA)**
	- Visualize feature distributions
	- Analyze correlations
	- Visualize geographical data
3. **Feature Engineering**
	- Log-transform skewed features
	- One-hot encode categorical variables
	- Create new ratio features
4. **Model Training & Evaluation**
	- Linear Regression with feature scaling
	- Random Forest Regressor
	- Model evaluation on test set
5. **Hyperparameter Tuning**
	- GridSearchCV for Random Forest
	- Selection and evaluation of the best model

## How to Run

1. **Clone the repository and navigate to the project folder:**
   ```sh
   git clone https://github.com/avi-poptani-003/House-Price-Prediction-ML-Project.git
   cd House-Price-Prediction-ML-Project
   ```
2. **Set up a Python environment (recommended):**
   ```sh
   python -m venv env
   env\Scripts\activate  # On Windows
   source env/bin/activate  # On Mac/Linux
   ```
3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Start Jupyter Notebook:**
   ```sh
   jupyter notebook
   ```
5. **Open `code.ipynb` and run the cells sequentially.**

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can generate a `requirements.txt` with:
```sh
pip freeze > requirements.txt
```

## Results

- The notebook provides visualizations for EDA and feature relationships.
- Linear Regression and Random Forest models are trained and evaluated.
- Hyperparameter tuning is performed for optimal Random Forest performance.

## Project Highlights

- Clean, well-commented code with clear section explanations
- Robust handling of missing values and categorical data
- Feature engineering for improved model performance
- Reproducible results with fixed random seeds

## License

This project is licensed under the MIT License.