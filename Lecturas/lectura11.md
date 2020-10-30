# Comentario: Deep Learning Based Recommender System: A Survey and New Perspectives. (Parte II)

Para la lectura de esta semana, se terminó de leer la segunda mitad del paper anterior. Resumiendo brevemente el contenido de la primera mitad, el paper analiza la inclusión de Deep Learning en sistemas recomendadores, haciendo un breve resumen de las ventajas y limitaciones de estos modelos y finalmente, explica los diferentes approaches existentes para estos modelos.

En la segunda parte, el paper sigue explicando los diferentes approaches para modelos que utilizan Deep Learning. En específico, estos son: 

- Recurrent Neural Networks: estos modelos están dirigidos al procesamiento de datos secuenciales, donde el orden temporal de las interacciones influye en la recomendación. 

- Restricted Boltzmann Machine based Recommendation: estos modelos aprenden una distribución de probabilidad sobre un set de inputs. De esta forma, podemos inferir las preferencias de un usuario según los ratings que den, sin importar si estos son negativos o positivos.

- Neural Attention Based Recommendation: estos modelos seleccionan inputs específicos al momento de predecir.

- Neural AutoRegressive based Recommendation: una alternativa a Restricted Boltzmann Machine

- Deep Reinforcement Learning for Recommendation: cada recomendación a un usuario le da feedback positivo y negativo al modelo, de forma que vaya mejorando su recomendación una vez es implementado.

- Adversarial Network based Recommendation: consiste en el uso de dos redes neuronales que compiten mutuamente.

- Deep Hybrid Models for Recommendation: combinaciones de modelos para objetivos específicos.

Finalmente, el paper termina presentando los problemas actuales que tiene el trabajo con Deep learning, y la dirección en que apuntan las futuras investigaciones. En particular de esta sección me pareció interesante el área de investigacion sobre las explicaciones de las recomendaciones, donde se menciona que una dirección prometedora es diseñar mecanismos que puedan entregar una conversación o explicación sobre la recomendación entregada. Investigué sobre el modelo que cita el paper como ejemplo, llamado "Neural Rating Regression with Abstractive Tips Generation for Recommendation" (2017), en donde se busca entregar una predicción del rating del usuario respecto a cierto item, pero utilizando lenguaje natural para entregar la información que represente una experiencia y sentimientos del usuario respecto a un item.

Este modelo al ser testeado muestra resultados que superan lo que era el estado del arte en el momento, tanto en las predicciones como en el uso de lenguaje natural.

Como opinión sobre el paper, esta segunda parte es mucho más densa que la primera, ya que se encarga de presentar en detalle los tipos de modelo que son el estado del arte. Por lo tanto, para entender ls explicaciones de estos modelos es muy útil un conocimiento previo al respecto.

Por otro lado, encuentro interesantes las propuestas entregadas para abordar a futuro. Con esto es posible ver qué areas de los sistemas recomendadores que utilizan Deep learning son las que se necesitan tratar, ya que podrían proveer de mayor utilidad. Además sirve como fuente para que se genere nuevo conocimiento, al poder servir de inspiración para futuras investigaciones.

# Referencias
Li, P., Wang, Z., Ren, Z., Bing, L., & Lam, W. (2017, August). Neural rating regression with abstractive tips generation for recommendation. In Proceedings of the 40th International ACM SIGIR conference on Research and Development in Information Retrieval (pp. 345-354).