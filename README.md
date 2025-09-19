🏠 Predictive AI for Real Estate Prices

This project applies machine learning techniques to predict real estate prices based on property characteristics. Using a dataset of house sales, we explore data, preprocess features, and build predictive models to estimate house prices.

📊 Project Overview

Goal: Develop a predictive model for house prices.

Dataset: Contains property features such as number of bedrooms, bathrooms, living area size, lot size, condition, and location.

Main Steps:

Data exploration and preprocessing.

Feature engineering (dates, categorical variables, scaling).

Model training and evaluation.

Visualization of model results and insights.

🗂 Dataset

Example columns:

Coluna	Tipo	Descrição
id	int64	Identificador único do imóvel.
date	object	Data da venda.
price	float64	Preço da casa (em dólares).
bedrooms	int64	Número de quartos.
bathrooms	float64	Número de casas de banho.
sqft_living	int64	Área habitável interior (pés²).
sqft_lot	int64	Área total do lote (pés²).
floors	float64	Número de andares.
waterfront	int64	Indicador binário: 1 = vista para a água, 0 = não.
view	int64	Índice de qualidade da vista (0 a 4).
condition	int64	Condição geral da casa (escala de 1 a 5).
...	...	Outras variáveis de estrutura e localização.
🔍 Methods

Exploratory Data Analysis (EDA)

Distribution of prices and key features.

Correlations between attributes.

Outlier detection and missing values check.

Feature Engineering

Convert dates to meaningful time features.

Normalize and scale numerical variables.

Encode categorical attributes.

Machine Learning Models

Linear Regression

Decision Trees / Random Forest

Gradient Boosting (XGBoost, LightGBM, etc.)

Model Evaluation

Metrics: RMSE, MAE, R².

Cross-validation for robustness.

🛠️ Technologies Used

Python

Jupyter Notebook

Libraries:

pandas, numpy (data processing)

matplotlib, seaborn (visualization)

scikit-learn (ML models & evaluation)

xgboost, lightgbm (advanced boosting methods)

🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/PredictiveAI.git
cd PredictiveAI


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook PredictiveAI.ipynb

📈 Results

Predicted house prices with machine learning.

Identified most important features driving property value.

Built a baseline regression model and improved it with boosting methods.

📌 Future Work

Add geospatial analysis with maps.

Deploy the model as a web API or dashboard.

Experiment with deep learning models.

👨‍💻 Author

Pedro Silva
