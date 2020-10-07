# Comentario "Inspectability and Control in Social Recommenders" (2012)

El paper trata sobre un análisis de la influencia de darle más control a un usuario en la configuración de un sistema recomendador, en específico, del tipo social. Esto significa que en vez de usar a todos los usuarios dentro del sistema para generar las recomendaciones, únicamente utiliza a los amigos del usuario para esto. 

A modo de hipótesis, se presenta la posibilidad de que un usuario de estos tipos de sistemas tendrá una preferencia por inspeccionar las recomendaciones y controlar los parámetros del sistema, debido a que al ser los otros usuarios utilizados sus amigos, tiene más interes en el por qué de las recomendaciones y su origen.

El sistema testeado es un recomendador de música en base a amistades de facebook. El sistema entrega un grafo con recomendaciones, el cual enlaza los gustos del usuario a los amigos relacionados y las recomendaciones resultantes de tal conexión. Por otro lado, se pone a prueba que tipo de 'controles' que se le dan usuario son más efectivos, probando en este caso un control sobre las preferencias en los gustos del usuario propio vs. un control sobre las influencias que tendrán los amigos en las recomendaciones. 

Como resultados, se obtiene que el uso de estos controles y de esta herramienta para visualizarlas recomendaciones tiene un efecto positivo en la comprensibilidad de las recomendaciones. Además, se obtiene que dependiendo del tipo de usuario, el usuario se siente más o menos en control o confiado en el sistema.

A pesar de que este paper fue publicado antes que el paper anterior (See What You Want to See: Visual User-Driven Approach for Hybrid Recommendation.), el leer ambos de forma seguida convierte al que se lea en segundo lugar un tanto redundante: siento que ambos comunican información similar al respecto, y a pesar de tener objetivos distintos (uno recomendar papers y el otro música), tienen conclusiones similares sobre la importancia de darle control al usuario sobre el sistema para ciertos casos de uso. A pesar de que las ideas principales son similares, cabe que ambos papers difieren en los detalles y desarrollos específicos de sus investigaciones.

Buscando más información sobre los sistemas recomendadores sociales, encontré un paper muy reciente llamado "Interfaces and Human Decision Making for Recommender Systems" (2020), el cual resume y trata sobre __Workshops__ que se realizarán en la conferencia **RecSys'20**, que tratan en específico de __Human Decision Making for Recommender Systems__. En este paper se hace notar que este tipo de workshops se enfocan en el "aspecto humano" de los sistemas recomendadores, haciendo investigaciones enfocadas a mejorar la experiencia del usuario con el sistema, en específico en términos de interacción. Por lo tanto, es posible decir que el tema tratado en este paper sigue siendo relevante en la actualidad, y todavía tiene muchos aspectos por investigar.

## Referencias

Peter Brusilovsky, Marco de Gemmis, Alexander Felfernig, Pasquale Lops, John O'Donovan, Giovanni Semeraro, and Martijn C. Willemsen. 2020. Interfaces and Human Decision Making for Recommender Systems. In Fourteenth ACM Conference on Recommender Systems (RecSys '20). Association for Computing Machinery, New York, NY, USA, 613–618. DOI:https://doi.org/10.1145/3383313.3411539

  
