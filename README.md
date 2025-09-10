# ⛏️ Predicción de la extracción de oro con Machine Learning  

## 🏢 Sobre la empresa  
**Zyfra** desarrolla soluciones de eficiencia para la industria pesada.  
El objetivo de este proyecto es crear un prototipo de modelo de **machine learning** que permita **predecir la cantidad de oro extraído del mineral**, a partir de los datos de extracción y purificación. Para evaluar el desempeño del modelo se utilizará la métrica sMAPE (Error porcentual absoluto medio simétrico), la cual permite medir la diferencia porcentual entre los valores reales y los valores predichos. Esta métrica es especialmente útil en problemas de predicción de cantidades, ya que proporciona una medida simétrica del error y facilita interpretar la fiabilidad del modelo en escenarios de producción.

Este modelo busca optimizar la producción, eliminando parámetros no rentables y mejorando la toma de decisiones en la industria minera.  

---

## 📝 Descripción breve del problema  
El proceso de extracción de oro genera una gran cantidad de datos que requieren limpieza y análisis antes de poder ser usados en modelos predictivos. Sin un modelo eficiente, la predicción de la cantidad de oro extraído puede resultar imprecisa, afectando la optimización del proceso y reduciendo la rentabilidad.  

Este proyecto resuelve el problema mediante:  
1. Preparación y limpieza de los datos.  
2. Análisis exploratorio para comprender las variables más relevantes.  
3. Creación y entrenamiento de un modelo de **machine learning** capaz de predecir con precisión la cantidad de oro extraído.  

---

## 🛠️ Tecnologías usadas  
- **Python**  
- **Pandas** → manipulación y procesamiento de datos  
- **NumPy** → cálculos numéricos  
- **Matplotlib / Seaborn** → visualización de datos  
- **Scikit-Learn** → entrenamiento y validación de modelos de machine learning  

---

## ▶️ Cómo ejecutarlo  

Descargar los datasets con la informacion obtenida durante la obtencion de oro.  

Ejecutar el script o notebook en este orden:

1. preprocesamiento.ipynb → limpieza y preparación de datos.

2. analisis_exploratorio.ipynb → análisis visual y estadístico.

3. modelo_prediccion.ipynb → creación, entrenamiento y evaluación del modelo.

📚 Conclusiones generales

- Tras realizar el preprocesamiento, análisis y creación del modelo, se obtuvo un sMAPE (Error porcentual absoluto medio simétrico) de 13.26%, lo que indica un alto nivel de fiabilidad entre las predicciones y los valores reales.

- El modelo de machine learning desarrollado presenta un desempeño sólido, lo que lo convierte en una herramienta útil para optimizar la producción de oro.

- La eliminación de parámetros no rentables y la selección de variables relevantes son claves para mejorar la eficiencia del modelo.

- Este prototipo puede ser la base para futuras optimizaciones y para la integración de modelos más complejos en la industria minera.
