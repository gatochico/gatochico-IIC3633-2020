# Comentario de "Context Aware Recommender Systems" (2011)

El siguiente paper trata sobre el concepto de contexto en las recomendaciones y la inclusión de este en sistemas recomendadores para ciertos casos de uso. Los sistemas recomendadores tradicionales vistos hasta ahora en el curso ignoran la existencia del contexto, y que las preferencias de un usuario por sobre un item o otro pueden cambiar dependiendo de este.

Lo primero que presenta el escrito es una pequeña discusión sobre el concepto "Contexto". Explica que es algo díficil de definir y expone el punto de vista de Dourish (2004) para subcategorizar el contexto en: **"Representational View"**, que define el contexto como forma de información, delineable, estable e independiente de la actividad y **"Interactional View"**, donde define que el _Scope_ de las _Features_ que influyen en el contexto es dinámico y hay una relación entre contexto y actividad.

Luego, se habla sobre los factores contextuales, que serían los factores de contexto que deberían influir en la recomendación. Aquí, dependiendo de qué tan estructurados y que tanto sepa el modelo sobre los factores, estos se clasificarán en **Fully Observable**, **Partially Observable** y **Unobservable**. Estos factores también pueden separarse en **Estáticos** y **Dinámicos**, dependiendo si cambian o no en el tiempo. 

Lo otro que es necesario entender es dónde incorporar el contexto: Esto puede ser como un filtro posterior o previo (_post and pre_ filtering), o incorporarlo como parte del modelo (_modeling_). Incluso, hay casos donde predicciones que no toman en cuenta el contexto funcionan mejor que predicciones que sí lo hacen, ya que si no usamos contexto, en general hay más datos de 'cada tipo' para entrenar.

Finalmente, el paper habla sobre posibles aplicaciones donde se podría usar un CARS y explica los desafíos que presentaban los CARS en ese momento. Entre estos se encuentran: la investigación y desarrollo de paradigmas distintos a _prefiltering_, _postfiltering_ y _modeling_, El comparar los 3 paradigmas para identificar las debilidades y fortalezas de cada uno, y luego la posibilidad de hacer combinaciones de estos tres paradigmas.

A modo general, investigué un poco sobre el avance que han renido los CARS y me encontré con esta publicación: "Context-Aware Recommender System: A Review of Recent Developmental Process and Future Research Direction" (2017), la cual hace una _review_ de los recientes progresos en el área. Este indica que a medida que avanzan los años, publicaciones sobre CARS han aumentado. Dentro de estos, predomina el uso de Datos tanto implícitos como explícitos al mismo tiempo como _input_ del modelo, y el uso de vectores sigue siendo el más popular. Otra cosa interesante es el que también predomina el uso del paradigma _Contextual Pre-Filtering_ de forma arrasante por sobre el _Modeling_ y el _Contextual Post-Filtering_. Eso sí, el paper responde una de las interrogantes del original, ya que indica que una investigación en particular concluyó que ninguno de los tres paradigmas era uniformemente superior al resto en términos de _Accuracy_ y _Diversity_.

Para finalizar, nuevamente me pareció un paper interesante y que es una buena introducción al tema, ya que explica todos los conceptos claves del área y presenta un estado general de los CARS en ese tiempo. Eso nos permite generar una base necesaria para entender escritos más complejos de este tema. Como única crítica, siento que la sección de _Challenges_ era demasiado corta y poco explicada vs. el resto del papers, por lo que se podrían haber añadido más desafíos o explicado de forma más específica los tres postulados. De esta forma, hubiera sido más facil buscar información o medir el avance que han tenido los CARS en la época actual.

## Referencias
Haruna, K.; Akmar Ismail, M.; Suhendroyono, S.; Damiasih, D.; Pierewan, A.C.; Chiroma, H.; Herawan, T. Context-Aware Recommender System: A Review of Recent Developmental Process and Future Research Direction. Appl. Sci. 2017, 7, 1211. Recopilado de https://www.mdpi.com/2076-3417/7/12/1211.