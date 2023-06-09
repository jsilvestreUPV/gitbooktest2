# Aprendizaje supervisado

El aprendizaje supervisado es la forma de ML más común.

La **tarea T** consiste en aprender una transformación $f:\mathcal{X}\to\mathcal{Y}$ donde:
* Las **entradas** $\boldsymbol{x}\in\mathcal{X}$, **características, covariables o predictores** suelen ser un vector numérico de dimensión fija; por ejemplo, $\mathcal{X}=\mathbb{R}^D$, donde $D$ es la dimensión del vector.
* Las **salidas** $\boldsymbol{y}\in\mathcal{Y}$, **etiquetas, objetivos o respuestas** suelen ser etiquetas de clase o reales.

La **experiencia E** viene dada por un **conjunto de entrenamiento,** esto es, un conjunto de $N$ pares entrada-salida
$$\mathcal{D}=\{(\boldsymbol{x}_n,\boldsymbol{y}_n)\}_{n=1}^N$$
donde $N$ es el **tamaño de la muestra**; también es usual referirnos a cada par $(\boldsymbol{x}_n,\boldsymbol{y}_n)$ como **muestra (de entrenamiento).**

La **medida de rendimiento P** depende del tipo de salida.

PEPE



