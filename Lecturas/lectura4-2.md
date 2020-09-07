# Comentario "Document Clustering Based On Non-negative Matrix Factorization" (2001)

El paper trata acerca de una propuesta nueva para realizar _document clustering_ basada en la factorización del corpus del documento. 

Primero se comienza dando una breve explicación de qué es _document clustering_ y su utilidad como herramienta para organizar, navegar, resumir grandes volúmenes de documentos de texto. Esto hace que el revisar y navegar el corpus de documentos sea más fácil y eficiente, ya que se genera una jerarquía de información que facilita su análisis. Se explican los tipos de _document clustering methods_: _Document partitioning_, que consiste en particionar el corpus en segmentos más pequeños o _clusters_ según su temática. y _Agglomerative_, que consiste en un _bottom-up approach_ que a partir de distintos data points, los va agrupando por temáticas en común para construir la jerarquía. 

Recientemente, técnicas de _clustering_ basadas en teorías de partición de grafos han aparrecido como una de las herramientas más eficientes para _document partitioning_. 

El paper propone un nuevo partitioning method, generando un espacio latente semántico derivado de la _Non-negative Matrix Factorization_ donde cada eje captura el tema base de un _cluster_ de documentos y el documento final es representado mediante una combinación aditiva de los temas base.

Lo que diferencia este método del _latent semantic indexing_ basado en SVD es que los vectores de NMF no necesitan ser ortogonales y que cada documento en este espacio semántico tiene la garantía de que no tendrá valores negativos. Empiricamente, el método propuesto tiene mejor precisión que SVD y _eigen decomposition_ (otro método para _clustering_).

Buscando en literatura más moderna, encontré el siguiente paper llamado "Graph Regularized Nonnegative Matrix Factorization for Data Representation" (D. Cai, X. He, J. Han and T. S. Huang. 2011), el cual usa este método como base e implementa un grafo de afinidad para codificar la información y la factorización de matriz respeta este grafo, con resultados prometedores. Esto demuestra que el método propuesto en este paper tenía potencial tanto por sí sola como posibilidades de ser mejorado.

Como opinión general, consideré este paper interesante debido al método de usar los tópicos como ejes. En general considero bastante interesante el tema de PLN, por lo que el comprender en más detalle el proceso de cómo se extraen los tópicos de un paper es algo muy útil dentro de este curso. Al haber leido el texto previo como una especie de 'introducción' a temas similares, el entrar a un paper como este que es mucho más técnico y especifico no se hace tan desafiante. Mi única crítica, más que una crítica en sí es un detalle personal, ya que al no tener una base matemática tan fuerte dificulta el proceso de entender el funcionamiento de la técnica nueva. 

## Referencias
D. Cai, X. He, J. Han and T. S. Huang, "Graph Regularized Nonnegative Matrix Factorization for Data Representation," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 33, no. 8, pp. 1548-1560, Aug. 2011, doi: 10.1109/TPAMI.2010.231. Recuperado de: https://ieeexplore.ieee.org/abstract/document/5674058