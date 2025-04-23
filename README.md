# Agro-Advisor
Agro Advisor is an end‑to‑end data‑science pipeline that helps farmers choose the most suitable crop for their specific soil and climate conditions. Built entirely in Python, the project leverages K‑Nearest Neighbors (K‑NN) and extensive exploratory data analysis to deliver 97.7 % classification accuracy, empowering growers to make informed, data‑driven planting decisions.

🚀 Key Features
Precision Crop Recommendation

Trains a K‑NN classifier on curated agronomic data—including soil pH, nitrogen, phosphorus, potassium, temperature, rainfall, and humidity—to suggest the optimal crop for a given set of conditions.

Robust Data Pipeline

Implements rigorous data‑cleaning routines (handling missing values, outlier detection, scaling) and feature‑engineering steps that elevate predictive performance.

Comprehensive EDA notebooks visualize correlations and highlight the most influential agronomic features.

High Model Performance

Achieves 97.7 % accuracy on the test set after hyperparameter tuning (optimal k, distance metric, and weighting scheme).

Cross‑validated results underscore the model’s stability and generalizability across diverse agro‑climatic zones.

Actionable Insights for Farmers

Outputs clear, human‑readable recommendations—e.g., “Based on current NPK levels and forecast rainfall, maize is the top choice.”

Potential integration with mobile or web dashboards to deliver localized advice directly to farmers.

Scalable & Reproducible Codebase

Modular scripts (data_ingest.py, preprocess.py, train.py, recommend.py) and Jupyter notebooks for transparency.

Requirements.txt and environment.yml provided for quick setup via pip or conda.

🛠️ Technical Stack
Languages & Libraries: Python 3.11, pandas, NumPy, scikit‑learn, Matplotlib, Seaborn

Modeling: K‑Nearest Neighbors (with grid‑search hyperparameter tuning)

Data Handling: CSV ingestion, preprocessing pipelines, train/validation/test split

Visualization: Pairplots, heatmaps, feature‑importance bar charts for stakeholder reporting

📈 Impact
By translating complex agronomic data into practical crop recommendations, Agro Advisor enables smarter planting decisions that can boost yields, reduce input waste, and improve livelihood outcomes for farming communities. The project demonstrates how applied machine learning can drive tangible benefits in agriculture, one of the world’s most critical sectors.

