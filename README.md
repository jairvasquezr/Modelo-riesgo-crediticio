# Modelado de Riesgo Crediticio

Este proyecto desarrolla modelos predictivos para evaluar el riesgo de incumplimiento en solicitudes de crédito al consumo, aplicando técnicas estadísticas y de machine learning a datos reales anonimizados de una institución financiera peruana.

## 📊 Definición del problema
Predecir la probabilidad de que un cliente incurra en default dentro de los próximos 12 meses, a partir de variables registradas en su solicitud de crédito.

## 🛠️ Herramientas y métodos
- **Python** (Pandas, Scikit-learn, XGBoost, Seaborn)
- **Ingeniería de variables**: Weight of Evidence (WoE), Information Value (IV)
- **Análisis estadístico**: Análisis bivariado, pruebas de Kolmogorov-Smirnov
- **Machine Learning**: Random Forest, XGBoost, Ridge, Lasso

## 📈 Resultados
Se compararon múltiples modelos predictivos.  
Los resultados indican que el modelo **Random Forest** entrenado con datos **balanceados por undersampling** logra detectar la mayor cantidad posible de defaults, según la métrica de **recall**.

## 📁 Estructura del proyecto
- `notebook.ipynb`: Análisis principal y desarrollo del modelo

## 🚀 Autor
**Jair Fernando Vasquez Ramos**  
Bachiller en Física | Científico de Datos | Machine Learning aplicado a Riesgo y Finanzas  
[LinkedIn](https://www.linkedin.com/in/jair-fernando-vasquez-ramos-a51a19293/) | [Portafolio](https://github.com/jairvasquezr?tab=repositories)

