# Video-Game-Sales
Introducción
La industria de los videojuegos es un sector amplio y en constante crecimiento, impulsado por avances tecnológicos que han hecho que los videojuegos sean cada vez más accesibles. En este proyecto, se analizaron las ventas de videojuegos desde 1980 hasta 2016, centrándose en las cifras de ventas, las plataformas, los géneros y las regiones. El objetivo fue identificar patrones y obtener información clave para comprender qué juegos tienen éxito, qué plataformas son las más populares y cuáles son los productores que dominan el mercado. Además, se examinó cómo estas variables varían según las regiones, incluyendo Norteamérica, Europa, Japón y el resto del mundo. Los conocimientos adquiridos en este análisis aportan una comprensión más profunda sobre los factores que contribuyen al éxito de los videojuegos en esta industria.

Validación de Datos
El conjunto de datos inicial contenía 16,598 filas y 11 columnas antes de los procesos de limpieza y validación. A continuación, se detalla la información de las variables incluidas:

Rank: Clasificación basada en las ventas globales. Sin valores faltantes (el mismo juego en diferentes plataformas se cuenta como valores distintos).
Name: Nombre del videojuego. Sin valores faltantes.
Platform: Plataforma en la que se lanzó el juego (ej. PC, PS4, etc.). Sin valores faltantes.
Year: Año de lanzamiento del juego. 271 valores faltantes, que se eliminaron durante el proceso de limpieza.
Genre: Género del juego. Sin valores faltantes.
Publisher: Editor del juego. 58 valores faltantes, eliminados en el proceso de limpieza.
NA_Sales: Ventas en Norteamérica (en millones). Sin valores faltantes.
EU_Sales: Ventas en Europa (en millones). Sin valores faltantes.
JP_Sales: Ventas en Japón (en millones). Sin valores faltantes.
Other_Sales: Ventas en el resto del mundo (en millones). Sin valores faltantes.
Global_Sales: Ventas totales a nivel mundial. Sin valores faltantes.


[Video Game Sales
](https://github.com/Dynamico-Analytics/Video-Game-Sales/blob/main/Games-Cleaning.ipynb)
