# Monografia Especializacion Ciencia de Datos

# Análisis de agrupación de distintos tipos de hurtos en la ciudad de Medellín 

Este repositorio contiene los notebooks de Jupyter para realizacion de un análisis y clusterizacion de datos utilizando Python. A continuación, se describe el paso a paso de la implementación y cómo ejecutar el script.

## Contenido de los notebooks

El notebook incluye varios pasos para la carga, análisis y visualización de datos:

1. **Carga de Datos**: Utilizamos la biblioteca `pandas` para cargar datos desde un archivo en formato `.csv`. directamente desde la pagina con la ayuda de `requests`
2. **Análisis Descriptivo**: Se calculan estadísticas descriptivas (media, mediana, moda, etc.) para tener una visión general de los datos.
3. **Preprocesamiento de Datos**: Se incluyen celdas para limpiar y transformar los datos en función de las necesidades del análisis.
4. **Visualización**: Usamos `matplotlib` para crear gráficos que ilustran la distribución y relación de las variables.
5. **Implementacion de cluster**: se realizan diversidad de metodologias de agrupacion de datos para obtener informacion de valor de los mismos
   
## Requisitos

Para ejecutar este notebook, asegúrate de tener instaladas las siguientes bibliotecas:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn math warnings requests
