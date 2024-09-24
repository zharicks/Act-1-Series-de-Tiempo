# **Análisis de Series de Tiempo del Índice FTSE 100**

En esta actividad, nos centraremos en el análisis de series de tiempo utilizando datos históricos del índice FTSE 100, obtenidos a través de la API de Yahoo Finance. El FTSE 100, también conocido como "Footsie", es uno de los principales índices bursátiles del Reino Unido, que agrupa a las 100 empresas más capitalizadas que cotizan en la Bolsa de Valores de Londres. La variación de este índice es un reflejo del comportamiento del mercado financiero británico y es de interés para inversores y analistas económicos.

El objetivo de esta práctica es modelar y predecir el comportamiento del índice FTSE 100 utilizando modelos ARIMA (AutoRegressive Integrated Moving Average), un enfoque comúnmente utilizado en el análisis de series de tiempo financieras debido a su capacidad para capturar patrones como la tendencia y la estacionalidad en los datos históricos.

Para esta actividad, se realizarán predicciones de los precios futuros del índice con horizontes de 7, 14, 21 y 28 días, aplicando tanto la técnica de rolling window como sin ella. Además, se evaluarán los modelos utilizando varias métricas de error como MAPE, MAE, RMSE, MSE y R2, y se realizarán gráficos de correlación entre las observaciones reales y las predicciones obtenidas.

Se llevará a cabo un análisis comparativo utilizando diferentes criterios de selección de modelos, como el criterio de información de Akaike (AIC), el criterio de inferencia bayesiana (BIC), y el criterio de información de Hannan–Quinn (HQIC). Estos criterios ayudarán a determinar el modelo ARIMA más adecuado para los datos del FTSE 100, asegurando la precisión y eficiencia en la predicción.

Además, se realizarán pruebas de normalidad e independencia de los residuales de cada modelo para validar los supuestos del modelo y garantizar la solidez de las conclusiones. Todos los pasos irán acompañados de un análisis estadístico detallado de los resultados obtenidos.