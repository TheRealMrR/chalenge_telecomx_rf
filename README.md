Análisis de Evasión de Clientes (Churn) 📊

Este repositorio contiene un notebook de Jupyter con el análisis completo del problema de evasión de clientes (churn) para una empresa de telecomunicaciones. Se presentan los pasos de limpieza de datos, transformación, análisis exploratorio y visualizaciones que ayudan a entender qué factores influyen en la decisión de los clientes de abandonar el servicio.

📁 Estructura del Proyecto

notebook/

churn_analysis.ipynb: Notebook principal con todo el flujo de trabajo.

data/

raw/: Datos originales sin procesar.

clean/: Datos limpios y listos para análisis.

README.md: Descripción general y guía de uso.

🎯 Objetivo

Identificar y comprender los patrones de churn mediante:

Limpieza y tratamiento de datos

Creación de variables derivadas (gasto anual, gasto diario)

Visualización de relaciones clave (género, edad, tipo de contrato, método de pago, gastos)

Conclusiones y recomendaciones para reducir la pérdida de clientes.



🔍 Análisis Exploratorio

Se incluyen gráficas y tablas para:

Distribución de churn por género, edad y contrato.

Efecto del método de pago en la retención de clientes.

Comparación de gasto mensual, anual y diario entre clientes que continúan y los que se van.

Gráficas: barras apiladas, boxplots, violines y pie charts con etiquetas de conteo y porcentajes.

📈 Principales Hallazgos

Contratos a largo plazo (anual, 2 años) muestran menor churn.

Adultos mayores tienen mayor probabilidad de abandono.

Métodos de pago automáticos (tarjeta, débito) reducen churn.

Clientes con gasto bajo mensual o diario presentan mayor tasa de abandono.

💡 Recomendaciones

Promociones para contratos anuales y bienales.

Incentivar métodos de pago automáticos con descuentos.

Segmentación de clientes de bajo gasto para ofertas personalizadas.

Atención especial a adultos mayores para mejorar su experiencia.


🛠️ Dependencias

pandas

numpy

matplotlib

seaborn

