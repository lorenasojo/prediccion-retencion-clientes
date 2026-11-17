# Predicción y retención de clientes | Model Fitness

## 1. Contexto 

Model Fitness, una cadena de gimnasios, busca mejorar la retención de sus clientes y reducir la cancelación de membresías (*churn*).

El proyecto analiza una base de datos de 4,000 clientes con información sobre características personales, duración de contratos, frecuencia de asistencia, participación en actividades grupales y gastos adicionales.

El objetivo fue identificar patrones asociados con la cancelación, desarrollar modelos predictivos y segmentar a los clientes para proponer estrategias de fidelización.

## 2. Mi contribución

Desarrollé un análisis integral de los datos que incluyó:

- Exploración, limpieza y revisión de la estructura del conjunto de datos.
- Análisis comparativo entre clientes que permanecieron y clientes que cancelaron.
- Identificación de patrones mediante estadísticas descriptivas, distribuciones y correlaciones.
- Construcción y evaluación de modelos de clasificación.
- Segmentación de clientes mediante técnicas de clustering.
- Interpretación de resultados y elaboración de recomendaciones de negocio.

## 3. Metodología y decisiones técnicas

El proyecto se desarrolló en cuatro etapas:

**Análisis exploratorio (EDA)**

Se examinaron 4,000 registros y 14 variables para identificar características relacionadas con la cancelación. Se compararon los comportamientos de ambos grupos, prestando especial atención a la antigüedad, duración del contrato y frecuencia de asistencia.

**Modelado predictivo**

Se implementaron dos algoritmos de clasificación: regresión logística y bosque aleatorio (*Random Forest*).

Se compararon mediante tres métricas: exactitud (*accuracy*), precisión (*precision*) y sensibilidad (*recall*). El bosque aleatorio presentó el mejor desempeño en el conjunto de validación.

**Segmentación de clientes**

Se estandarizaron las características, se construyó un dendrograma mediante clustering jerárquico y se aplicó K-means con cinco clústeres para identificar perfiles de clientes.

**Interpretación y recomendaciones**

Se analizaron las características promedio y las tasas de cancelación de cada grupo para identificar segmentos prioritarios y proponer acciones de retención.

## 4. Resultados principales

**Evaluación de modelos**

El modelo de bosque aleatorio obtuvo los siguientes resultados:

| Métrica | Resultado |
|---|---:|
| Exactitud | 92.75% |
| Precisión | 88.50% |
| Recall | 83.49% |

**Segmentación de clientes**

Se identificaron cinco grupos con diferentes comportamientos de cancelación.

El clúster 3 presentó el mayor riesgo de abandono, con una tasa de cancelación del 57.3%. Este grupo se caracteriza por una menor frecuencia de asistencia, menor antigüedad y contratos más cortos.

Por otro lado, el clúster 2 presentó la mayor fidelidad, con una tasa de cancelación de apenas 2.2% y una duración promedio de contrato de aproximadamente 11.85 meses.

## 5. Conclusiones e impacto potencial en el negocio

Los resultados permiten identificar grupos de clientes que requieren diferentes estrategias de atención.

Se recomienda priorizar acciones de retención para clientes con baja frecuencia de asistencia y contratos cortos, implementar programas de fidelización y promover planes de mayor duración.

La segmentación permite orientar las estrategias de marketing según el comportamiento de los clientes, mientras que los modelos predictivos ofrecen una herramienta para anticipar posibles cancelaciones.

## 6. Herramientas y tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

## 7. Evidencia del proyecto

- Notebook de análisis: [Agregar enlace al archivo del repositorio]
- Repositorio de GitHub: [Agregar enlace]

