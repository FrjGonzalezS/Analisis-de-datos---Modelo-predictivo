# Análisis de Datos Climáticos: Predicción de Lluvia en Sydney

### 🚀 Tecnologías y Habilidades Utilizadas

Este proyecto sigue el modelo de análisis **CRISP-DM (Cross-Industry Standard Process for Data Mining)**, asegurando un enfoque estructurado y eficiente en cada fase del proyecto, desde la comprensión del negocio hasta la implementación de modelos predictivos.

### 🔄 Fases del Modelo CRISP-DM:
1. **Business Understanding**: Identificación del problema a resolver, en este caso, la predicción de lluvia en Sydney.
2. **Data Understanding**: Exploración y análisis inicial de los datos climáticos.
3. **Data Preparation**: Limpieza y transformación de los datos para que sean aptos para el modelado.
4. **Modeling**: Creación de modelos predictivos utilizando técnicas de machine learning.
5. **Evaluation**: Evaluación de los modelos para asegurar que cumplen con los objetivos del negocio.
6. **Deployment**: Preparación para implementar el modelo en un entorno productivo.

### 🛠️ Bibliotecas y Herramientas de Python:
- **pandas**: Manipulación de datos y manejo de grandes conjuntos de datos climáticos.
- **numpy**: Operaciones matemáticas y optimización de cálculos numéricos.
- **matplotlib** y **seaborn**: Visualización de datos para la detección de patrones y representación gráfica de valores atípicos.
- **scikit-learn (sklearn)**:
  - **Preprocesamiento**: Se utilizaron `StandardScaler` para la estandarización de variables numéricas y `SimpleImputer` para el manejo de valores faltantes.
  - **Modelos predictivos**: Se aplicaron modelos de **Regresión Logística**, **Naive Bayes** y **Árbol de Decisión** para la predicción de lluvia.
  - **Clustering**: Se utilizó **KMeans** para el análisis no supervisado, permitiendo identificar patrones en los datos climáticos.
  - **Evaluación de modelos**: Uso de métricas como `accuracy_score`, `classification_report` y la curva ROC-AUC para evaluar el rendimiento de los modelos.

### 🧠 Habilidades Técnicas:
1. **🔍 Análisis y Preprocesamiento de Datos**:
   - Manejo de valores faltantes y atípicos (outliers) para limpiar y preparar los datos para el modelado.
   - Transformación de variables categóricas en numéricas utilizando técnicas de codificación y escalado de variables.

2. **⚙️ Modelado Predictivo**:
   - Implementación de modelos de clasificación supervisada (Regresión Logística, Naive Bayes, Árbol de Decisión) para predecir la probabilidad de lluvia al día siguiente.
   - Aplicación de un modelo no supervisado (KMeans) para identificar clusters en los datos climáticos.

3. **📊 Evaluación de Modelos**:
   - Comparación de diferentes modelos supervisados, midiendo métricas de precisión, recall y F1-score para evaluar la calidad de las predicciones.
   - Análisis de curvas ROC y AUC para medir la capacidad de los modelos para distinguir entre clases.

4. **📈 Visualización de Datos**:
   - Uso de gráficos de caja (boxplots) para detectar y visualizar outliers.
   - Creación de mapas de calor para analizar correlaciones entre variables climáticas.
   - Representación gráfica de la curva ROC para evaluar el rendimiento de los modelos.

### 🔔 Conclusión
Este proyecto se desarrolló siguiendo el modelo **CRISP-DM**, asegurando un proceso claro y eficiente desde la fase inicial de comprensión del negocio hasta la evaluación de los modelos. 
Las tecnologías utilizadas incluyen bibliotecas de Python ampliamente empleadas en ciencia de datos, mientras que las habilidades desarrolladas cubren desde la limpieza de datos hasta la evaluación y mejora de modelos predictivos.
