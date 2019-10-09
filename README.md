# ¿Cuál es el precio del diamante 💎?

<img src="dataset/diamante.jpg" />

Primera competición dentro de Ironhack para ver quien se aproximaba más al valor real. La base de datos consistia en:
- data.csv: training set (Para entrenar nuestro modelo)
- test.csv: test set (Para hacer predicciones)

_las Features:_

* **id**: only for test & sample submission files, id for prediction sample identification
* **price**: price in USD
* **carat**: weight of the diamond
* **cut**: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
* **color**: diamond colour, from J (worst) to D (best)
* **clarity**: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
* **x**: length in mm
* **y**: width in mm
* **z**: depth in mm
* **depth**: total depth percentage = z / mean(x, y) = 2 * z / (x + y) Valores:(43--79)
* **table**: width of top of diamond relative to widest point Valores:(43--95)

# Resolución: 
Aplicación del modelo random forest, tras el analisis inicial de la base de datos.

NOTA: Al eliminar los datos atípicos el modelo mejora las predicciones dentro del código pero al pasarlo a Kaggle empeora los mismos.

