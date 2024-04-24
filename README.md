# MIAX12-ML

Material preparado para las clases de Machine Learning del máster MIAX: Edición 12

Autores:

* Christian Oliva Moya

* Luis Fernando Lago Fernández

<hr>

## Contenido del repositorio

* `data` incluye algunos ficheros CSV para trabajar durante la parte práctica de las clases.

* `notebooks` incluye los notebooks que estamos usando como práctica durante las clases. En particular, un notebook tendrá el siguiente nombre: `<BLOQUE>_<N>_<DESCRIPCION>.ipynb`, donde `<BLOQUE>` será el bloque del temario que tiene relación con el notebook, `<N>` es simplemente un ordinal y `<DESCRIPCION>` da nombre al notebook. Por ejemplo, el notebook `3_1_arboles.ipynb` es el primer notebook del bloque 3.

* `slides` incluye las diapositivas que se están viendo durante las clases.

## Temario

* **Bloque 1: Introducción al curso y al Machine Learning. Conceptos básicos de ML**
  * Notebook *1_1_introduccion_experimentando_con_activos*. Introducción a un primer concepto de ML con activos financieros.

* **Bloque 2: K-Nearest Neighbors (KNN). Introducción a Sklearn y Google Colab**
  * Notebook *2_1_knn*. Implementación manual de KNN. Comparación con `KNeighborsClassifier` de Sklearn.
  * Notebook *2_2_knn_experimentando_con_activos*. Uso de KNN con la misma idea de búsqueda de patrones en el tiempo. Introducción a `KNeighborsRegressor` de Sklearn.

* **Bloque 3: Árboles de decisión**
  * Notebook *3_1_arboles*. Implementación de `DecisionTreeClassifier` y visualización del árbol con Sklearn.
  * Notebook *3_2_arboles_bancarrota*. Implementación con Sklearn.
