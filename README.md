# HOSPITAL-RESOURCE-OPTIMIZATION
Smart optimization of hospital bed and resource usage – UC3M Hackathon

Hospital bed and resource management is complex and often inefficient. The lack of prediction leads to overcrowding, admission delays, and suboptimal discharges. Can we use hospital data to predict demand and intelligently optimize resources?

Background

Reactive decisions instead of predictive ones.
High variability in length of stay.
Lack of decision-support tools.
Direct impact on quality of care.

Challenge objective
Design a predictive system that helps anticipate occupancy, length of stay, and hospital resource needs

Possible solutions

1. Length-of-stay prediction
Models based on diagnosis, age, comorbidities.
Individual discharge prediction.

3. Occupancy models
Short-term demand prediction.
Scenario simulation.

5. Management dashboard
Real-time visualization.
Overcrowding alerts

7. Decision-support system
Prioritization recommendations.
Hospital flow optimization.

# DATABASES:
 1. https://www.kaggle.com/c/prediccin-de-estancia-hospitalaria-2020-1/data
 2. https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data
 3. https://www.kaggle.com/code/alobde/hospital-admission-duraci-n-de-ocupaci-n-de-cama 

# MODELS:
1. Length of stay (existing patients): CatBoostRegressor
2. Occupancy prediction (new patients): RandomForestRegressor or LGBMRegressor
3. Management dashboard: Streamlit, Plotly Dash

