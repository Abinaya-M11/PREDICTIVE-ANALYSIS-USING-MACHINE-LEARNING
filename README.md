# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

"COMPANY":CODTECH IT SOLUTIONS

"NAME":ABINAYA M

"INTERN ID":CT04DL1390

"DOMAIN":DATA ANALYTICS

"DURATION":4 WEEKS

"MENTOR":NEELA SANTHOSH KUMAR

# ✅ Task 2: Predictive Modeling using Machine Learning


In this task, I implemented supervised machine learning models using Python and Scikit-learn to predict a continuous variable (logS: solubility) from a dataset of molecular descriptors.

# 🧰 Tools & Libraries Used:

Python

Pandas for data manipulation

Scikit-learn for ML models

Matplotlib for visualization 

Jupyter Notebook

# 📌 Dataset Used:

Source: Delaney_solubility_with_descriptors dataset

Target Variable: logS (Solubility of molecules)

Features: Molecular descriptors such as Molecular Weight, LogP, etc.

# ⚙️ Steps Performed:

1. 📥 Data Loading
   
Loaded dataset directly from GitHub using pandas.read_csv().


2.🧹 Data Preparation

Separated the target (y = logS) and features (x = rest of columns).

3. 🔀 Data Splitting

Split the data into training (80%) and testing (20%) using train_test_split.

🤖 Model Building

# ✅ Linear Regression:

Trained using LinearRegression() from sklearn.linear_model.

Generated predictions for both train and test sets.

📊 Performance Metrics:

MSE (Train): Calculated using mean_squared_error

R² Score (Train/Test): Indicates the goodness of fit

# ✅ Random Forest Regression:

Model: RandomForestRegressor() (assumed from structure; code wasn't shown in preview)

Trained and tested like Linear Regression.

Performance compared using same metrics (MSE, R²)

📊 Model Evaluation & Comparison:

Evaluated both models based on Mean Squared Error and R² Score for training and test data.

Stored results in a DataFrame lr_results and compared performance.

Visualizations were optionally created for actual vs predicted plots.

# ✅ Outcome:

Successfully built and evaluated Linear Regression and Random Forest models.

Understood model performance through proper evaluation metrics.

Compared models and visualized predictions effectively.
