# Comentario: Deep Learning Based Recommender System: A Survey and New Perspectives.

El paper trata acerca del uso de __Deep Learning__ en sistemas recomendadores, y porque es un campo de investigación con gran potencial, tomando un punto de vista global donde analizan el estado del arte actual y perspectivas a tomar para desarrollo futuro. 

En específico, la primera mitad del paper se centra en una introducción a __Deep Learning__ y sus diversos tipos de implementaciones, y el porqué el uso de __Deep Learning__ es un campo de interés en el área de recomendación. Entre los mayores argumentos se encuentra **el uso de transformaciones o funciones no lineales**, que permiten generar funciones más complejas de recomendación , **mayor libertad con respecto a la información que usa** para entrenar y predecir, **modelamiento de patrones secuenciales**, aplicables a tareas en específico como reconocimiento de PLN y **flexibilidad** para construir modelos variados.

Por otro lado, se presentan limitaciones a modelos que usen __Deep Learning__, entre los que se incluye: falta de **interpretabilidad**, donde está el desafío de entender el porqué de las recomendaciones, la necesidad de **altos volúmenes de datos** y el requerimiento de tener **Extensivo afinamiento de parámetros**.

Finalmente, la sección de esta semana termina nombrando y explicando el estado del arte, mediante diferentes __approaches__ para modelos. Entre estos está **Multilayer Perceptron**, **Autoencoder based**, y **Convolutional Neural Networks**.

Como introducción a la materia de _Deep Learning_ en sistemas recomendadores, me parece que el paper es una buena lectura inicial. Abarca varios temas al respecto de forma no muy profunda, y al ser un análisis del estado del arte, contiene información actualizada a esa fecha por lo que es información relevante a aprender. De esta forma, permite a un lector como yo que no conozca todavía el área los conocimientos básicos para poder adentrarse en literatura más compleja y específica sin confundirse  completamente.

Algo que me interesó en particular de esta primera parte del texto es el procesamiento de datos de diversa índole no estructurados. En particular, en el paper de septiembre del 2020 de nombre "Recommender Systems Leveraging Multimedia Content" es un escrito equivalente al paper que se está comentando, en el sentido de que hace un análisis del estado de arte, pero se enfoca particularmente en modelos que abarquen esta subárea de __multimedia content__.

En particular, el escrito referenciado menciona la necesidad de tener modelos que reciban contenido multimedia, y explica el proceso general que siguen los modelos que atacan estos problemas: __Segmentation__, __Feature extraction__, _Item representation__, __Semantic Orientation__ y __Learning Recommendation Model__. Con esto como base, procede a diferenciar los tipos de recomendaciones en 3 grandes categorías: Audio, Imagen y Video. Finalmente y tras un análisis de estas tres categorías, se proponen preguntas a investigar respecto al tema, dando pie para la generación de más literatura al respecto.

# Referencias
Deldjoo, Yashar & Schedl, Markus & Cremonesi, Paolo & Pasi, Gabriella. (2020). Recommender Systems Leveraging Multimedia Content. Computing Surveys. 53. 1-38. 10.1145/3407190. Recuperado de https://www.researchgate.net/publication/344454095_Recommender_Systems_Leveraging_Multimedia_Content
