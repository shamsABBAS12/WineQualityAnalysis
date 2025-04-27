# WineQualityAnalysis
🍷 Wine Quality Prediction App Welcome to the innovative Wine Quality Prediction App! This end-to-end machine learning solution is tailored to classify wine quality using a range of physicochemical attributes. Built with Streamlit, the application is hosted on Hugging Face.


🚀 Project Highlights
- Designed a fully functional web application for wine quality classification.
- Leveraged Optuna to fine-tune hyperparameters for optimal model selection.
- Addressed class imbalance effectively with SMOTE.
- Deployed a user-friendly app interface using Streamlit on the Hugging Face platform.


🌟 Core Features
- Input wine characteristics to predict its quality instantly.
- Compare performance across multiple machine learning algorithms.
- Real-time and interactive results.
- Simple, intuitive interface for seamless user interaction.


🛠️ Technology Stack
- Python for backend programming.
- Pandas and NumPy for handling and processing data.
- Matplotlib and Seaborn for data visualization.
- Scikit-Learn for developing machine learning models.
- Optuna for model optimization.
- SMOTE to overcome dataset imbalance.
- Streamlit to design the web application.


Deployment through Hugging Face.
📊 Dataset Features This project uses a dataset containing various wine properties, such as:
- Fixed and volatile acidity
- Residual sugar content
- Chlorides and density
- pH levels
- Sulphates and alcohol concentration
- Free and total sulfur dioxide levels
- Quality score (as the target variable)


🔎 Process Overview
- Data Analysis
- Explored and visualized correlations among features.
- Identified critical attributes affecting wine quality.
- Data Preparation
- Normalized data with StandardScaler.
- Balanced dataset using SMOTE for better representation.
- Model Development
- Tested various classifiers, including KNN, Random Forest, and Decision Tree.
- Applied Optuna for meticulous hyperparameter tuning.
- Chose the best-performing model for deployment.
- Deployment Process
- Serialized the model using Pickle for integration.
- Created an interactive Streamlit interface for users.
- Successfully deployed the app on Hugging Face.
