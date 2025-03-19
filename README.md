# Film-Junky-Union

## Descripcipción del proyecto

Film Junky Union, una nueva comunidad vanguardista para los aficionados de las películas clásicas, está desarrollando un sistema para filtrar y categorizar reseñas de películas. Tu objetivo es entrenar un modelo para detectar las críticas negativas de forma automática. Para lograrlo, utilizarás un conjunto de datos de reseñas de películas de IMDB con leyendas de polaridad para construir un modelo para clasificar las reseñas positivas y negativas. Este deberá alcanzar un valor F1 de al menos 0.85.

## Conclusiones
- Existen algunas formas diferentes de convertir texto en tokens y lemas.
- Hay varias maneras de convertir textos en vectores.
- El modelo simple TF-IDF + LogisticRegression ofrece una buena calidad según las métricas objetivo.
- La lematización con spaCy no parece aportar mucho.
- BERT requiere mucho tiempo en CPU, pero mucho menos en GPU.
- El modelo de clasificación basado en el modelo de lenguaje (BERT) muestra métricas (precisión, F1, etc.)de  valores similares a modelos menos complejos, pero parece ser más discriminativo (las probabilidades son más 'polarizadas') y menos susceptible al sobreajuste.
