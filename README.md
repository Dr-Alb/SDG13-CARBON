# SDG13-CARBON
🌱 Carbon Emissions Predictor – AI for SDG 13: Climate Action
This project uses machine learning to predict CO₂ emissions based on fossil fuel usage data. It supports the United Nations Sustainable Development Goal 13: Take urgent action to combat climate change and its impac

📌 Project Summary
Goal: Build a supervised ML model to predict total carbon emissions based on various fuel sources (gas, liquid, solid, cement, etc.).

SDG Target: Reduce greenhouse gas emissions by improving data-driven decision-making.

Method: Supervised learning using a Random Forest Regressor on fossil fuel datasets.

Outcome: A model that can help policymakers or researchers estimate CO₂ emissions trends based on fuel consumption patterns.

🔍 Problem Statement
Climate change is accelerated by rising CO₂ emissions from human activity. Understanding and predicting these emissions is vital for global sustainability. This project tackles:

Estimating total emissions from key fuel consumption sources.

Visualizing actual vs predicted emissions.

Empowering data-driven policies through AI.

📊 Dataset
Source: CO2 Emissions - Global Fossil Fuel Dataset

Columns Used:

Gas Fuel, Liquid Fuel, Solid Fuel, Cement, Gas Flaring as input features

Total emissions as the prediction target

🧪 Machine Learning Approach
Algorithm: RandomForestRegressor (scikit-learn)

Features: Fuel-based CO₂ emission components

Target: Total annual CO₂ emissions

Steps:

Data preprocessing and cleaning

Train/test split (80/20)

Model training and evaluation (R², MAE, MSE)

Visualization of results

✅ Results
Metric	Value
R² Score	0.97 (approx)
MAE	~ 50 million tons
MSE	~ 3000 (scaled)

📈 The model shows high accuracy in predicting carbon emissions based on fuel consumption.

🧠 Ethical Reflection
Bias Risk: Historical datasets may underrepresent regions with poor data infrastructure.

Sustainability: Promotes transparency in emissions reporting and can assist governments in climate policy planning.

Fairness: Designed to treat all countries’ data equally based on availability.

🛠 Tools Used
Python 🐍

Pandas, NumPy – data processing

scikit-learn – ML model

Matplotlib, Seaborn – visualization

Google Colab – notebook environment

📸 Screenshots
Include these in your repo:

📷 dataset-head.png — preview of dataset

📷 actual-vs-predicted.png — scatter plot of predictions

🚀 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/carbon-emissions-predictor.git
cd carbon-emissions-predictor
Open the notebook in Google Colab or Jupyter.

Run all cells to load data, train model, and visualize results.

🎯 Future Enhancements
Add real-time emission data via APIs

Compare with other regressors (XGBoost, SVR)

Build a Streamlit app for interactive predictions

Integrate geospatial mapping for country-level insights

🤝 Contributing
Pull requests are welcome! For major changes, open an issue first to discuss.

📄 License
This project is open-source under the MIT License.

