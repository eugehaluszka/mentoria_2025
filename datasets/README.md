# Descripción de la base de datos: _Tweets sobre obesidad_

## Descripción de la base de datos 

•	Nombre del archivo: tweets_obesidad_argentina.csv

•	Número de filas: 11111

•	Número de columnas: 13

Este repositorio contiene una base de datos con 11111 registros y 13 columnas recopilados de Twitter a partir de palabras clave sobre obesidad. La información fue extraída con el objetivo de analizar conversaciones en torno a la obesidad en Argentina, incluyendo interacciones, fechas, hashtags y datos geográficos. Para identificar la provincia de origen de los usuarios que generaron los tweets, se realizó un proceso de reconocimiento de localidades, ciudades y departamentos más relevantes y frecuentes a partir de la variable "location" asociada a cada usuario. Posteriormente, se asignó una provincia a cada tweet con base en esa información. En los casos en que un tweet presenta dos o más provincias identificadas, esto se debe a que el usuario mencionó múltiples lugares en su descripción de ubicación. Esta variable se denominó "pcia". 

## Descripción de las variables

| Variable |	Descripción |
| - |-|
|id_str |	Identificador único del tweet.|
|date	| Fecha y hora de publicación del tweet.|
| rawContent | Texto completo del tweet.|
|replyCount	|Número de respuestas que recibió el tweet.|
|retweetCount	|Número de veces que el tweet fue retuiteado.|
|likeCount	|Número de “me gusta” que recibió el tweet.|
|quoteCount	|Número de veces que el tweet fue citado por otros usuarios.|
|conversationId|	ID de conversación, permite agrupar tweets que forman parte de un hilo.|
|hashtags	|Lista de hashtags utilizados en el tweet.|
|viewCount|Número de visualizaciones del tweet (si está disponible).|
|pcia|	Provincia argentina desde la cual se publicó el tweet (cuando disponible).|
|mes|	Mes de publicación del tweet (formato numérico).|
|user_id	|Identificador del usuario que publicó el tweet.|

## Uso sugerido
Este conjunto de datos puede ser utilizado para estudios de análisis de sentimiento, tendencias temáticas, análisis geográfico, entre otros, en el marco de la salud pública y el tratamiento de temas como la obesidad en redes sociales.

