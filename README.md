# PrediFood
Para este proyecto creamos una solución web para optimizar el abastecimiento alimentario en restaurantes mediante Machine Learning. Desarrollado por Alexandre Motta: programación del sistema, scripts de predicción y despliegue en la nube. 

-- Resultados Cuantitativos --
Se evaluaron seis modelos de regresión para predecir el consumo semanal de insumos, utilizando métricas estándar de error:

| Modelo                  | MSE     | RMSE   | MAE   |
|------------------------|---------|--------|-------|
| Gradient Boosting      | 0.0032  | 0.057  | 0.027 |
| Random Forest          | 0.0035  | 0.059  | 0.028 |
| Neural Network (MLP)   | 0.0037  | 0.061  | 0.029 |
| Ridge Regression       | 0.0045  | 0.067  | 0.031 |
| Lasso Regression       | 0.0043  | 0.065  | 0.030 |
| Linear SVR             | 0.0050  | 0.071  | 0.034 |

📈 Gradient Boosting demostró ser el modelo más preciso, con una mejora del 8.4% en RMSE respecto al segundo mejor modelo.

--Tecnologías Aplicadas--
El sistema se estructura en cuatro capas funcionales, integrando herramientas modernas de desarrollo, análisis y visualización:

- Python: Procesamiento de datos y entrenamiento de modelos.
- Azure Machine Learning Studio: Entrenamiento, validación y despliegue de modelos.
- Log Analytics Workspaces: Monitoreo de métricas y detección de anomalías.
- Azure Cosmos DB: Almacenamiento de datos no estructurados en tiempo real.
- Azure MySQL Server: Gestión de datos relacionales y transaccionales.
- Power BI: Dashboards interactivos para seguimiento de insumos, alertas y predicciones.
- Azure App Services: Hosting de la aplicación web y móvil.
- API Connections & Storage Accounts: Integración de servicios y almacenamiento seguro.

--Impacto y Aplicabilidad--

- Reducción estimada del desperdicio alimentario en un 15–20% semanal.
- Predicciones con una precisión superior al 92% en escenarios de demanda variable.
- Interfaz accesible desde dispositivos móviles y escritorio.
- Escalabilidad para implementación en hoteles, comedores industriales y cadenas de restaurantes.

--Publicación Académica--

Este proyecto ha sido documentado en un artículo aceptado en una revista académica.  
Puedes consultar el manuscrito completo aquí:  https://www.scitepress.org/Papers/2025/132337/132337.pdf

--Aviso de Protección--
Este repositorio presenta una versión pública del proyecto PrediFood. Todos los datos sensibles han sido omitidos o simulados para fines de demostración. El código fuente completo no se encuentra disponible públicamente. Para fines académicos o colaborativos, puede solicitarse acceso bajo acuerdo.
