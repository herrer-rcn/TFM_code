# TFM_code
code of the TFM

En este repositorio se encuentra el codigo separado por notebooks del TFM 
RECOGNITION PREDICTION ON TENNIS STROKES USING ML TECHNIQUES
Autor:Rubén Herrera

- En el script TFM archivo inicial Jugador 1 acelerometro.ipynb se encuentra el codigo inicial, donde se estudia y explica el estudio, limpieza, fragmentación por golpes del jugador 1
- En el script TFM archivo inicial Jugador 2 acelerometro.ipynb y consecuentemente 3,4,5,6 son copias del 1 donde se realiza el mismo proceso para todos los jugadores.
- En el script TFM giroscopio limpieza todos jugadores.ipynb se realiza la misma operación que se ha realizado para el acelerometro, pero sin fragmentar la muestra, solo limpieza. Se realiza en bucle para todos los jugadores
- En el scriot TFM fragmentacion de golpes del giroscopio, se realiza la particion de golpes del giroscopio, basandose en los tiempos unix de los golpes del acelerometro
- En el script interpolación TFM se realiza la busqueda del fragmento con mas puntos y se iguala el resto de muestras a esa muestra con mas puntos
- En el script fusionyconversionparamodeloTFM.ipynb se realiza una conversion a columnas de los archivos interpolados del giroscopio y del acelerometro
- en el script modeloacc TFM se realiza la particion en train test i validacion cruzada i la creacion de los modelos busqueda de hiperparametros del modelo solo de acc
- En el script modelo acc_gyr TFM se realza la particion en train test i validacion cruzada i la creacion de los modelos busqueda de hiperparametros del modelo del aceleremetro mas el giroscopio
- Los scripts de TFM DTW y de fragmentacion por tiempo son parte de las pruebas realizadas para probar dichos metodos
