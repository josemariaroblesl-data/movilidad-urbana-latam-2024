# movilidad-urbana-latam-2024
Análisis de movilidad urbana y productividad económica en 15 ciudades de América Latina (2024)
# Análisis de Movilidad Urbana y Productividad Económica en LatAm (2024)

## Objetivo
Evaluar si existe relación entre la congestión de tráfico urbano y el PIB per cápita en 15 ciudades de América Latina, para identificar ciudades prioritarias para inversión en infraestructura de transporte.

## Fuentes de datos
- **TomTom Traffic Index**: métricas de congestión y tiempos de viaje por ciudad.
- **OECD Cities**: PIB per cápita, desempleo, población y calidad del aire.

## Metodología
- Limpieza y estandarización de columnas (formatos numéricos, fechas, snake_case).
- Filtrado y agregación de datos de tráfico por ciudad-año (2024).
- Unión de datasets (`merge` tipo INNER) por ciudad y año.
- Visualización de distribuciones (boxplot, histograma) y comparación entre variables.

## Herramientas
Python · Pandas · Seaborn · Matplotlib · Jupyter Notebook

## Hallazgo principal
Ciudad de México presenta la congestión más alta del dataset (2,833 min de retraso promedio), mientras que no existe una relación lineal clara entre PIB per cápita y nivel de congestión — Montevideo, por ejemplo, combina PIB alto con tráfico muy bajo.

## Autor
José María Robles Linares — [LinkedIn](https://www.linkedin.com/in/jose-maria-robles-linares)
