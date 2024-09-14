# **Proyecto: Predicción de Mortalidad de Salmónidos según Parámetros de Calidad de Agua**

Este proyecto evalúa el impacto de los 8 parámetros más importantes de calidad de agua, según el libro "Calidad de Agua para el Cultivo de Salmónidos en Chile" (Ase Atland & Vilhelm Bjerknes, Instituto Noruego de Calidad de Agua, 2009), en la mortalidad de salmónidos. El objetivo es determinar si estos parámetros permiten predecir la mortalidad y evaluar la importancia de cada uno en el modelo predictivo.

## **Parámetros evaluados:**

-Temperatura (Temp): Medida en grados Celsius.
-pH: Nivel de acidez o alcalinidad del agua.
-Amonio (NH₄): Concentración de amonio en mg/L.
-Amoniaco (NH₃): Concentración de amoniaco en mg/L.
-Nitratos (NO₃): Concentración de nitratos en mg/L.
-Dureza del agua: Medida de dureza en mg/L (concentración de CaCO₃).
-Dióxido de Carbono (CO₂): Concentración de CO₂ en µg/L.
-Hierro (Fe): Concentración de hierro en µg/L.
-Mortalidad: Número de muertes registradas.

## **Descripción del Proyecto**

-Análisis Exploratorio de Datos (EDA): Se realiza un análisis exploratorio para comprender los parámetros y su relación con la mortalidad de los salmónidos.
-Modelos Predictivos: Se implementan dos modelos de aprendizaje automático:
    -Regresión Lineal.
    -Random Forest Regressor.
-Para ambos modelos, se evalúa la precisión mediante:
    -Error Cuadrado Medio (MSE).
    -Coeficiente de Determinación (R²).

## **Requisitos**

Para ejecutar este proyecto, necesitarás instalar las siguientes librerías de Python:

```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, r2_score
from sklearn.ensemble import RandomForestRegressor

```
Puedes instalarlas usando pip:

```
pip install pandas matplotlib seaborn scikit-learn

```

## **Estructura del Proyecto**
-data/: Contiene los datos de entrada necesarios para el análisis.
-notebook/: Contiene los cuadernos de Jupyter utilizados para la EDA y los modelos.
-src/: Contiene los scripts Python para los modelos predictivos y análisis.
-README.md: Este archivo, con detalles del proyecto.

## **Ejecución**

El proyecto considera un Jupyter Notebook donde se realiza el análisis exploratorio de datos y la evaluación de los modelos.

1. Clona este repositorio:

```
git clone https://github.com/tu-usuario/nombre-del-repo.git
```

2. Instala las dependencias listadas en la sección de "Requisitos".
3. Ejecuta el notebook para entrenar los modelos y evaluar los resultados.

## **Resultados Esperados**

-Regresión Lineal: El modelo predictivo basado en la regresión lineal entrega una primera aproximación simple.
-Random Forest Regressor: Este modelo permite evaluar la importancia de los diferentes parámetros y proporciona predicciones más precisas en comparación con la regresión lineal.

## **Contribuciones**
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
3. Haz commit de tus cambios (git commit -m 'Añadir nueva funcionalidad').
4. Envía tus cambios (git push origin feature/nueva-funcionalidad).
5. Abre un pull request.


## **Licencia**
Este proyecto está licenciado bajo la MIT License.
