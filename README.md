# 📊 Análisis de Cancelación de Clientes – Telecom X  

## Descripción  
Este proyecto tiene como objetivo analizar los factores que influyen en la evasion de clientes en la empresa TelecomX.
Se aplicaron técnicas de Machine Learning para predecir la evasion de clientes y proponer estrategias de retención basadas en los resultados.  

---

## Tecnologías utilizadas  
- **Python**  
- **Pandas, NumPy** : para el  procesamiento de datos
- **Scikit-learn** : para el Modelado y métricas  
- **Matplotlib, Seaborn** :para Visualización de graficas
- **Google Colab**  

---

## lujo del proyecto  
1. **Importación y exploración de datos**  
   - Análisis descriptivo  
   - Visualizaciones de patrones  

2. **Preprocesamiento y transformación (ETL)**  
  - Eliminación de columnas irrelevantes
- Encoding
- Verificación de la proporción de cancelación
- Balanceo de clases
- Análisis de correlación
- Normalización de datos (para KNN)
3. **Modelado y evaluación**  
   - Modelos utilizados:  
     - Árbol de Decisión  
     - Random Forest  
     - K-Nearest Neighbors (KNN)  
   - Métricas de evaluación:  
     - Exactitud (Accuracy)  
     - Precisión  
     - Recall  
     - F1-score  
     - Matriz de confusión  

4. **Optimización de modelos**  
   - Búsqueda de hiperparámetros con `GridSearchCV`  

5. **Análisis de importancia de variables**  

6. **Informe final**  
   - Identificación de los factores principales de evasión  
   - Propuesta de estrategias de retención  

---

## Resultados comparativos  

| Modelo              | Exactitud | Precisión | Recall  | F1-score |
|---------------------|-----------|-----------|---------|----------|
| Árbol de Decisión   | 0.797     | 0.756     | 0.876   | 0.812    |
| Random Forest       | **0.844** | **0.826** | 0.870   | **0.848**|
| KNN                 | 0.813     | 0.768     | **0.896** | 0.827    |

**Conclusión:**  
- El modelo con mejor rendimiento global es **Random Forest**.  
- **KNN** destaca en *recall*, puede ser de utilidad para identificar clientes que presentan un mayor riesgo de evasión.  
- **Árbol de Decisión** presento resultados buenos, sin embargo, fue superado en desempeño.  

---

## 📝 Estrategias de retención sugeridas  
•	Retener a clientes nuevos
•	Revisión o flexibilizar los precios
•	Promocionar contratos de largo plazo
•	Incentivar al uso de pagos automáticos
•	Promover los servicios adicionales como soporte técnico y seguridad.
---
