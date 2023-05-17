---
layout: default
title: Información pública sobre este proyecto
---

13 de Abril, 2023

Herramientas que nos serán útiles para este proyecto de análisis de datos urbanísticos:

Librerías de python:

1. pySLEUTH: predicción de expansión de población.
2. Docker: Administrador y gestor de dependencias para aplicaciones.
3. Tipo de información de datos:  Desde bases de datos personales, desde la municipalidad.

Para usar URSA en Windows:
1. Instalar una terminal adecuada (PowerShell puede ser) e instalar python3.
2. Instalar Docker y correr la app
3. Conseguir el token para Google earth-engine


Urbanpy, jupyter notebook de colab:
https://colab.research.google.com/drive/1Pcc92ma5jnitDB86hYFcJ1phYTNScYfM


Obtención de información desde los mapas Google Maps:
https://overpass-turbo.eu

Por ejemplo, para buscar parques y/o canchas, hay que posicionar el mapa en la región de interés y luego definir la siguiente búsqueda: 'leisure': ['park', 'pitch']


Tutorial para instalación de URSA en Windows:

https://github.com/EL-BID/URSA/blob/main/documentation/URSA-Tutorial-Windows.pdf

Seminario de implementación de URSA
https://www.youtube.com/watch?v=bWZIB8yEasM


Descargar el repositorio de URSA y luego dentro, en una terminal de windows powershell:

docker build -t bid-urban-growth . 



## identificación de microbasurales

Finalmente, es la correlación de componentes físicos en el uso del espacio. 

google earth engine
https://code.earthengine.google.com

¿Tif images?

- Imágenes satelitales 

https://www.fundacionbyb.org/basurales


Seminarios en youtube sobre los beneficios y casos de uso de detección de microbasurales:

https://www.youtube.com/watch?v=WWS5lvB__hQ

https://www.youtube.com/watch?app=desktop&v=h-WUOaIG4mU


Clasificación del uso y cobertura del suelo con Machine Learning usando Python:

https://colab.research.google.com/drive/1v8-AqAw4uGt9ZUWCpjXwl7u2NY98lcGB?usp=sharing