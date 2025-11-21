Descripción del proyecto

Este proyecto consiste en analizar los datos de cuatro tiendas diferentes utilizando Python, Pandas y Matplotlib.
Los datos provienen de archivos CSV y fueron cargados mediante un código base provisto en el desafío.

El objetivo es extraer insights relevantes sobre ventas, productos, categorías y calificaciones, además de generar visualizaciones que apoyen la interpretación de los resultados.

📂 Contenido del proyecto

El proyecto realiza los siguientes pasos:

✔ 1. Carga y preparación de datos

Se importaron los CSV de las cuatro tiendas usando el código base provisto.

Cada tienda se almacenó en un DataFrame independiente.

Se añadió una columna Tienda a cada DataFrame.

Se concatenaron todos los DataFrames en uno solo para facilitar el análisis.

✔ 2. Análisis realizados
Ingresos por tienda

Se calculó el ingreso total de cada tienda al sumar los valores de la columna Precio.

Ventas por categoría

Se contó el número total de ventas por categoría y tienda, considerando que cada fila representa una venta.

Productos más y menos vendidos

Se identificaron los productos con mayor y menor número de ventas en cada tienda.

Calificación promedio por tienda

Si existía la columna Calificación, se calculó su promedio por tienda para evaluar la satisfacción general.

✔ 3. Visualizaciones generadas

Se construyeron 3 gráficos utilizando Matplotlib:

Gráfico de barras – Ingresos por tienda
Muestra qué tienda generó más ingresos totales.

Gráfico de barras – Ventas por categoría y tienda
Permite comparar qué tipo de productos dominan en cada tienda.

Gráfico de barras o boxplot – Calificación promedio por tienda
Ayuda a observar el nivel de satisfacción del cliente en cada tienda.

(Opcional)
4. Top de productos más vendidos

🛠️ Tecnologías utilizadas

Python 3

Pandas

Matplotlib

Google Colab

CSV como fuente de datos

▶️ Cómo ejecutar este proyecto

Abrir el archivo en Google Colab.

Ejecutar la celda del código base para cargar los datos.

Ejecutar las celdas de análisis.

Visualizar los gráficos generados al final.

No se necesita instalar nada adicional más allá de:

import pandas as pd
import matplotlib.pyplot as plt

📈 Resultados clave

Identificación de la tienda con mayores ingresos.

Categorías más y menos vendidas en cada tienda.

Productos destacados (top y bottom performers).

Comportamiento general del cliente según calificación (si aplica).

📎 Archivos incluidos

Notebook de análisis (.ipynb)

Archivos CSV originales

Gráficos generados (dentro del notebook)
