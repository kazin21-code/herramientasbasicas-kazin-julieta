# Proyecto final de análisis de datos
Autora: Kazin Julieta.
Curso: Herramientas básicas del analisis de datos.

## La evolución de la Fórmula 1
Este proyecto busca analizar cómo evolucionó el rendimiento de las escuderías de Fórmula 1 entre 2017 y 2025 (puntos y abandonos) y qué factores se relacionan con los mejores resultados, integrando distintas herramientas como Python, Power BI y GitHub.

# Dataset
Tabla de F1 con una fila por vuelta de cada piloto en cada Gran Premio con 232.932 filas y 34 columnas. La misma fue creada apropósito con vacíos, errores y duplicados para poder llevar a cabo un análisis más profundo y lograr llegar a una tabla limpia. 

La tabla sucia fue la que se utilizó en el Google Colab para el análisis exploratorio, llegando al fin del análisis a una tabla limpia. Esta última es la que tuve en cuenta a la hora de ejecutar el dashboard con Power BI.

Tabla_F1_original: https://docs.google.com/spreadsheets/d/1pxYFYUq54JfQHz-hoF2_boBpBn-SkDPr4XFdW1_Gbxw/edit?gid=1345150346#gid=1345150346

Data_set_limpio: https://docs.google.com/spreadsheets/d/1FKsrlgMCt_xVqG-K-zELp7HbFJUIN1NjbdhHFkf8Ic4/edit?gid=479168240#gid=479168240

# Objetivo
Se plantearon una pregunta principal y 3 subpreguntas que se pueden resolver a partir del date set elegido:

**Pregunta principal**
- ¿Cómo evolucionó el rendimiento de las escuderías de Fórmula 1 entre 2017 y 2025 (puntos y abandonos) y qué factores se relacionan con los mejores resultados?

**Subpreguntas**

   - ¿Qué escuderías acumularon más puntos, en total y en cada temporada?
   
   - ¿Qué porcentaje de las participaciones terminó en abandono y cómo cambió por temporada?
   
   - ¿Cuántas posiciones ganan o pierden en promedio las escuderías entre la largada y la llegada, y qué tanto influye la posición de largada?


# Pasos realizados

1- **Diagnóstico**: revisión de tipos, nulos, duplicados, columnas sin utilidad, inconsistencias y valores fuera de rango.

2- **Limpieza**: eliminación de 6.784 duplicados, unificación de textos y categorías, conversión de fechas y tipos, y tratamiento de valores fuera de rango y nulos. El resultado queda en data_set_limpio (223.919 filas).

3- **KPIs**: puntos totales, porcentaje de abandonos y posiciones ganadas promedio.

4- **EDA**: análisis cualitativo y cuantitativo, con 5 gráficos interpretados.

5- **Dashboard en Power BI**: 3 KPIs, 4 gráficos y un panel de filtros por temporada, escudería y piloto.



