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

* **Bloque 1: Introducción al curso y al Machine Learning. Conceptos básicos de ML** [2024-04-26]
  * Notebook *1_1_introduccion_experimentando_con_activos*. Introducción a un primer concepto de ML con activos financieros.

* **Bloque 2: K-Nearest Neighbors (KNN). Introducción a Sklearn y Google Colab** [2024-04-26]
  * Notebook *2_1_knn*. Implementación manual de KNN. Comparación con `KNeighborsClassifier` de Sklearn.
  * Notebook *2_2_knn_experimentando_con_activos*. Uso de KNN con la misma idea de búsqueda de patrones en el tiempo. Introducción a `KNeighborsRegressor` de Sklearn.

* **Bloque 3: Árboles de decisión** [2024-04-26]
  * Notebook *3_1_arboles*. Implementación de `DecisionTreeClassifier` y visualización del árbol con Sklearn.
  * Notebook *3_2_arboles_bancarrota*. Implementación con Sklearn.
 
* **Bloque 4: Preprocesamiento** [2024-05-03]
  * Notebook *4_1_exploracion*. Visualización, procesamiento de NaNs y errores en el dataset.
  * Notebook *4_2_transformaciones*. Tratamiento de datos de diferente naturaleza, dummies, etc.
  * Notebook *4_3_estandarizacion*. Estandarización a media 0, desviación 1

* **Bloque 5: Validación** [2024-05-03]
  * Notebook *5_1_cross_validation_and_threshold*. Implementación de un cross validation con Sklearn y probando el threshold con distintas métricas.
 
* **Bloque 6: Reducción de dimensionalidad** [2024-05-03]
  * Notebook *6_1_feature_importance_con_error*. Selección de atributos por permutación y por correlación asumiendo un error a posta.
  * Notebook *6_2_feature_importance_corregido*. Corrección del notebook anterior. Las clases están desbalanceadas.
  * Notebook *6_3_PCA*. Ejemplo de PCA con Sklearn.
 
* **Bloque 7: Clustering** [2024-05-04, 2024-05-06 y 2024-05-07]

* [2024-05-04]
  
  * Notebook *7_1_clustering_aglomerativo*. Implementación manual del clustering aglomerativo. Ejemplo de uso de Scipy.
  * Notebook *7_2_KMeans*. Implementación manual de KMeans. Ejemplo de uso de Sklearn. Interpretación de los representantes.
  * Notebook *7_3_EM*. Ejemplo de uso de Sklearn.
  * Notebook *7_4_DBSCAN*. Clustering particional vs densidad. Implementación manual de DBSCAN. Ejemplo de uso de Sklearn.
  * Notebook *7_5_comparacion_clustering*. Ejercicios de comparación de los algoritmos de clustering en diferentes problemas.

* [2024-05-06 y 2024-05-07]
    
  * Notebook *7_6_clustering_activos_momentum*. Aplicación de clustering para agrupar activos financieros.
  * Notebook *7_7_HRP*. Hierarchical Risk Parity explicado desde el punto de vista de clustering.
  * Notebook *7_8_clusterizacion_fondos*. Aplicación de clustering para agrupar fondos.
 
* **Bloque 8: Teoría bayesiana** [2024-05-07]
  * Notebook *8_1_naive_bayes*. Ejemplo de uso de SKlearn.
    
* **Bloque 9: Conjuntos de clasificadores** [2024-05-07]
  * Notebook *9_1_conjuntos*. Implementación manual de los algoritmos. Ejemplo de uso con Sklearn.
 
* **Bloque 10: Modelos lineales** [2024-05-08]
  * Notebook *10_1_modelos_lineales*.
    
* **Bloque 11: Métodos de Kernel** [2024-05-08]
  * Notebook *11_1_kernel_methods*.
  * Notebook *11_2_kernel_ridge*.
 
* **Bloque 12: Support Vector Machines** [2024-05-09]
  * Notebook *12_1_support_vector_machines*.
  * Notebook *12_2_svms_pima*.
