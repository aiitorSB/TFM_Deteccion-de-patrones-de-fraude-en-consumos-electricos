# Detección de patrones de fraude en consumos eléctricos mediante aprendizaje automático aplicado a contadores inteligentes

Resumen
El fraude eléctrico constituye uno de los principales problemas a los que se enfrentan las compañías distribuidoras, debido a las pérdidas económicas y operativas que genera. En este contexto, el presente Trabajo de Fin de Máster tiene como objetivo desarrollar y evaluar un sistema de detección de fraude eléctrico basado en técnicas de aprendizaje automático aplicadas a datos de consumo procedentes de contadores inteligentes.

Para ello, se llevó a cabo un análisis exploratorio y un proceso de preprocesamiento del conjunto de datos utilizado, compuesto por más de 560.000 registros de consumo energético correspondientes a distintos tipos de edificios. Posteriormente, se implementaron tres modelos supervisados basados en Gradient Boosting (XGBoost, LightGBM y CatBoost), así como un modelo no supervisado (Isolation Forest). La optimización de hiperparámetros se realizó mediante Optuna, utilizando validación cruzada de cinco particiones para garantizar la robustez de los resultados.

Los resultados obtenidos muestran que los modelos supervisados alcanzan un rendimiento muy elevado en la detección de fraude, obteniendo valores de ROC-AUC cercanos a 0,96 y una precisión global del 96%. El modelo que obtuvo el mejor comportamiento global fue LightGBM. Por lo contrario, el modelo Isolation Forest mostró una capacidad de detección muy inferior.

En conclusión, las técnicas de aprendizaje automático supervisado basadas en gradient boosting son una solución eficaz y fiable para la detección de fraude eléctrico en redes inteligentes.

Abstract
Electricity theft is one of the main challenges faced by power distribution companies due to the economic and operational losses it causes. In this context, the aim of this Master’s Thesis aims to develop and evaluate an electricity fraud detection system based on machine learning techniques applied to consumption data from smart meters.

To this end, an exploratory analysis and preprocessing of dataset were carried out, consisting of more than 560,000 energy consumption of more than 560,000 energy consumption records from different types of buildings. Subsequently, three supervised models based on gradient boosting (XGBoost, LightGBM and CatBoost) were implemented, as well as an unsupervised model (Isolation Forest). Hyperparameter optimization was performed using Optuna, employing five-partition cross-validation to ensure the robustness of the results.

The results show that the supervised model achieved very high performance in fraud detection, obtaining POC-AUC values close to 0,96 and an overall accuracy of 96%. The model that performed best overall was LightGBM. Conversely, the Isolation Forest model showed a much lower detection capacity. 

In conclusion, supervised machine learning techniques based on gradient boosting are an effective and reliable solution for detecting electricity fraud in smart grids.
