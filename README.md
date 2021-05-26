# Proyecto_03

1.1  Dataset: STEAM
Recuerda descargar el dataset de aquí. Son dos archivos, uno de calificaciones y otro de información sobre los juegos.
En este notebook te dejamos unas celdas para que puedas comenzar a trabajar con este dataset. Sin embargo, deberás modificarlas para hacer un mejor manejo de datos. Algunas cosas a las que deberás prestar atención (tal vez no a todas):
1.	Tipos de datos: elige tipos de datos apropiados para cada columna.
2.	Descartar columnas poco informativas.
3.	Guardar en memoria datasets preprocesados para no tener que repetir código que tarde en correr.
1.1.1  Exploración de datos
Dedícale un buen tiempo a hacer un Análisis Exploratorio de Datos. Elige preguntas que creas que puedas responder con este dataset. Por ejemplo, ¿cuáles son los juegos más populares?¿Y los menos populares?
1.1.2  Filtro Colaborativo
Deberás implementar un sistema de recomendación colaborativo para este dataset. Ten en cuenta:
1.	Haz todas las transformaciones de datos que consideres necesarias. Justifica.
2.	Evalúa de forma apropiada sus resultados. Justifica la métrica elegida.
3.	Elige un modelo benchmark y compara tus resultados con este modelo.
4.	Optimiza los hiperparámetros de tu modelo.
Puedes implementar un filtro colaborativo a partir de la similitud coseno o índice de Jaccard. ¿Puedes utilizar los métodos de la librería Surprise? Si no es así, busca implementaciones (por ejemplo, nuevas librerías) que sean apropiadas.
Para comenzar a trabajar, puedes asumir que cada entrada es un enlace entre una persona usuaria y un item, independientemente de si la crítica es buena o mala.
1.1.3  Para pensar, investigar y, opcionalmente, implementar
1.	¿Cómo harías para ponerle un valor a la calificación?
2.	¿Cómo harías para agregar contenido? Por ejemplo, cuentas con el género, precio, fecha de lanzamiento y más información de los juegos.
3.	¿Hay algo que te gustaría investigar o probar?
1.1.4  ¡Tómate tiempo para investigar y leer mucho!
