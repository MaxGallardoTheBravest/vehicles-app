# vehicles-app
Panel de anuncios de venta de coches — Sprint 7 TripleTen


# Análisis de anuncios de venta de coches

Aplicación web interactiva que permite explorar un conjunto de datos
de anuncios de venta de vehículos en Estados Unidos.

## Enlace a la aplicación

https://vehicles-app-eyh8.onrender.com

## Funcionalidad

La aplicación permite al usuario:

- Construir un **histograma** de la distribución del odómetro
- Construir un **gráfico de dispersión** que relaciona el precio con el kilometraje

Ambas visualizaciones se generan al presionar su botón correspondiente y son
interactivas: permiten hacer zoom y consultar valores al pasar el cursor.

## Datos

El conjunto de datos `vehicles_us.csv` contiene 51,525 anuncios con 13 variables,
entre ellas precio, año del modelo, condición, tipo de combustible y kilometraje.

## Tecnologías

- pandas — manipulación de datos
- plotly express — visualizaciones interactivas
- streamlit — interfaz web