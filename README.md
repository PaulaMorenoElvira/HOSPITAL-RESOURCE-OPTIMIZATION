# HOSPITAL-RESOURCE-OPTIMIZATION
Optimización inteligente del uso de camas y recursos hospitalarios- Hackaton UCIII

La gestión de camas y recursos hospitalarios es compleja y frecuentemente ineficiente. La falta de
predicción provoca saturación, retrasos en ingresos y altas subóptimas.¿Podemos usar datos hospitalarios
para predecir demanda y optimizar recursos de forma inteligente?
Antecedentes
Decisiones reactivas en lugar de predictivas.
Alta variabilidad en estancias.
Falta de herramientas de apoyo a la decisión.
Impacto directo en calidad asistencial.
Objetivo del reto
Diseñar un sistema predictivo que ayude a anticipar ocupación, duración de estancia y necesidades de
recursos hospitalarios.

Posibles soluciones

1. Predicción de duración de estancia
Modelos basados en diagnóstico, edad, comorbilidades.
Predicción individual de alta.

3. Modelos de ocupación
Predicción de demanda a corto plazo.
Simulación de escenarios.

5. Dashboard de gestión
Visualización en tiempo real.
Alertas de saturación.

7. Sistema de apoyo a decisiones
Recomendaciones de priorización.
Optimización de flujos hospitalarios.

# BASES DE DATOS:
 1. https://www.kaggle.com/c/prediccin-de-estancia-hospitalaria-2020-1/data
 2. https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data
 3. https://www.kaggle.com/code/alobde/hospital-admission-duraci-n-de-ocupaci-n-de-cama (PROBAR EL SABADO)
 4. PROBAR TAMBIEN el excel (BASEDATOS(PROBAR))

# MODELOS:
1. Duracion de la estancia (pacientes existentes): CatBoostRegressor
2. Prediccion ocupacion (pacientes nuevos): RandomForestRegressor o LGBMRegressor
3. Dashboard de gestion: Streamlit, Plotly Dash
4. Sistema apoyo decisiones: 
