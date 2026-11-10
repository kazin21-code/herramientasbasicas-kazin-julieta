# Proyecto final de análisis de datos
Autora: Kazin Julieta.
Curso: Herramientas básicas para el Análisis de Datos 2026.

## La evolución de la Fórmula 1
Este proyecto busca analizar cómo evolucionó el rendimiento de las escuderías de Fórmula 1 entre 2017 y 2025 (puntos y abandonos) y qué factores se relacionan con los mejores resultados, integrando distintas herramientas como Python, Power BI y GitHub.

# Dataset
Tabla de F1 con una fila por vuelta de cada piloto en cada Gran Premio con 232.932 filas y 34 columnas. El dataset fue creado deliberadamente con valores faltantes, errores y registros duplicados para simular problemas reales de calidad de datos y permitir un proceso completo de limpieza.

La tabla sucia fue la que se utilizó en el Google Colab para el análisis exploratorio, llegando al fin del análisis a una tabla limpia. Esta última es la que tuve en cuenta a la hora de ejecutar el dashboard con Power BI.

# Enlaces 

Google colab: https://colab.research.google.com/drive/1C05KDkJlI-9MfxMt1oEI9HnJE18JKDOm?usp=sharing

Tabla_F1_original: https://docs.google.com/spreadsheets/d/1pxYFYUq54JfQHz-hoF2_boBpBn-SkDPr4XFdW1_Gbxw/edit?gid=1345150346#gid=1345150346

Data_set_limpio: https://docs.google.com/spreadsheets/d/1FKsrlgMCt_xVqG-K-zELp7HbFJUIN1NjbdhHFkf8Ic4/edit?gid=479168240#gid=479168240

# Herramientas utilizadas

- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn  
- Google Colab  
- Power BI 
- GitHub

# Estructura 
<img width="635" height="175" alt="image" src="https://github.com/user-attachments/assets/756436a6-79c6-4b07-83f4-06bb6c22ba95" />


# Objetivos
Se plantearon una pregunta principal y 3 subpreguntas que se pueden resolver a partir del date set elegido:

**Pregunta principal**
- ¿Cómo evolucionó el rendimiento de las escuderías de Fórmula 1 entre 2017 y 2025 (puntos y abandonos) y qué factores se relacionan con los mejores resultados?

**Subpreguntas**

   - ¿Qué escuderías acumularon más puntos, en total y en cada temporada?
   
   - ¿Qué porcentaje de las participaciones terminó en abandono y cómo cambió por temporada?
   
   - ¿Cuántas posiciones ganan o pierden en promedio las escuderías entre la largada y la llegada, y qué tanto influye la posición de largada?


# Proceso de trabajo

### **Metodología**
1. **Diagnóstico de calidad de datos**

- Identificación de nulos
- Duplicados
- Inconsistencias
- Valores fuera de rango
  
2. **Limpieza y transformación**
   
- Eliminación de 6.784 registros duplicados
- Normalización de categorías
- Conversión de tipos de datos
- Tratamiento de valores faltantes
  
*Resultado*: 223.919 registros limpios.

3. **Creación de indicadores** (KPIs)
   
- Puntos totales
- Porcentaje de abandonos
- Posiciones ganadas promedio

4. **Análisis exploratorio** (EDA)
   
- Análisis descriptivo
- Visualizaciones
- Interpretación de resultados
  
5. **Dashboard en Power BI**
   
- KPIs
- Gráficos interactivos
- Filtros dinámicos

# Hallazgos

- Red Bull fue la escudería con mejor rendimiento acumulado durante gran parte del período analizado.
- Las tasas de abandono disminuyeron en comparación con los primeros años analizados, reflejando mejoras en la confiabilidad de los monoplazas.
- Existe una relación positiva entre una buena posición de largada y el resultado final de la carrera.
- Algunas escuderías lograron ganar posiciones de forma consistente durante las carreras, evidenciando estrategias y ritmos de carrera competitivos.
- Red Bull, Mercedes y Ferrari concentran más del 60 % de los puntos: Mercedes dominó 2017-2020, Red Bull 2021-2024 y McLaren 2025.

# Dashboard 

El dashboard fue desarrollado en Power BI e incluye:

- 3 indicadores principales (KPIs)
- 4 visualizaciones interactivas
- Filtros por temporada
- Filtros por escudería
- Filtros por piloto
<img width="1195" height="676" alt="image" src="https://github.com/user-attachments/assets/8a63e6a0-86f9-4430-a455-285347e00dfb" />


# Conclusión

El proyecto permitió aplicar un flujo completo de trabajo de análisis de datos, desde la limpieza y transformación de la información hasta la generación de visualizaciones, lo que permitió obtener los elementos necesarios para responder las preguntas planteadas sobre la evolución de la Fórmula 1 a lo largo de los años.

El análisis evidenció tendencias relevantes en el rendimiento de las escuderías, la evolución de los abandonos y la importancia de la posición de largada en los resultados obtenidos.

Es importante aclarar que los abandonos durante una carrera pueden deberse a múltiples factores, como problemas técnicos en el monoplaza, errores en las paradas en boxes, incidentes con otros vehículos o accidentes en pista. Por este motivo, la disminución observada en la cantidad de abandonos a lo largo de los años puede asociarse, en parte, a mejoras en la fiabilidad de los autos y de sus componentes mecánicos.
