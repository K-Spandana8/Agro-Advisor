# Agro-Advisor
Agro Advisor is a Python‑based, end‑to‑end data‑science pipeline that helps farmers select the most profitable crop for their specific soil and climate conditions. Using a finely tuned K‑Nearest Neighbors (K‑NN) classifier, the system achieves 97.7 % prediction accuracy, converting raw agronomic data into practical, high‑yield recommendations.

Key Components

Data Pipeline: Ingests raw CSV files, imputes missing values, detects outliers, scales numerics, and visualizes feature distributions to uncover links between soil chemistry, weather patterns, and crop suitability.

Feature Engineering: Focuses on seven critical variables—nitrogen, phosphorus, potassium, pH, temperature, rainfall, and humidity. Recursive feature elimination shows these explain over 95 % of model variance, keeping the model both interpretable and robust.

Model Tuning: Grid‑search optimizes k, distance metrics, and weighting schemes. The final K‑NN model maintains high accuracy and consistent cross‑validation scores across diverse agro‑climatic zones.

