# Análisis Unificado de la Producción y Exportación de Café frente a Datos Agrícolas (FAO)
## Contexto General
Este proyecto surge de la necesidad de integrar, limpiar y homologar diversas fuentes de datos para estudiar el comportamiento de la industria cafetalera a nivel global. Específicamente, se cruzan las bases de datos históricas de producción y exportaciones de la Organización Internacional del Café (ICO) con el amplio registro de producción de cultivos proporcionado por la Organización de las Naciones Unidas para la Alimentación y la Agricultura (FAO).

El análisis abarca un horizonte temporal que inicia en 1990 y se extiende hasta 2018, permitiendo evaluar las tendencias de producción de café en comparación con la dinámica agrícola general de los países productores.

# Objetivos
* **Aplicar Limpieza y Homologación de Datos**: Resolver las inconsistencias de nomenclatura de países entre los datasets de la FAO y de la ICO para asegurar una integración del 100% de los países productores.
* **Transformación y Estructuración**: Convertir los datasets de formato ancho (wide) a formato largo (long), normalizar las unidades de medida de la industria cafetalera (sacos de 60 kg) a toneladas métricas para hacerlas comparables con los estándares de la FAO, y calcular variables derivadas como el crecimiento año con año (YoY%) y el rendimiento relativo de producción vs. exportación. 
* **Análisis Exploratorio y Visualización**: Identificar a los principales productores históricos de café, analizar la correlación entre las métricas de cultivo generales y las específicas de café, y visualizar la evolución temporal y la relación estructural entre la producción y la exportación por país.