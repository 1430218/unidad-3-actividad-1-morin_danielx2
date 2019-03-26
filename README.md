# Unidad-3-Actividad-1
## Implementación de los métodos PCA, LDA y JPCA para reducción de dimensionalidad.


# Problema
Mediante el uso del dataset de "Runas" realice lo siguiente:
  1. Implemente una versión propia de los algoritmos: PCA, LDA y KPCA.
  2. Muestre, mediante gráficas, el aporte de cada componente (o disciminante) al comportamiento de dataset. Ésto por cada algoritmo implementado.
  3. Entrene y optimice (gridsearch) al menos 2 algoritmos de clasificación por cada uno los siguientes casos:
    1. Con la totalidad de las características:
      1. 5s y no-5s. (5ta runa)
      2. multi-class
    2. Con los k componentes obtenidos mediante PCA:
      1. 3s y no-3s. (3ra runa)
      2. Multi-class
    3. Con los k discriminantes obtenidos mediante LDA:
      1. 1. 6s y no-6s. (6ta runa)
      2. Multi-class
    4. Con los  k componentes obtenidos mediante KPCA:
      1. 8s y no-8s. (7ma runa)
      2. Multi-class
  4. Se deberá proporcionar una tabla comparativa con las siguientes medidas, de los experimentos antes mencionados en el punto 3:
    * Precisión (accuracy)
    * Sensibilidad (Recall)
    * F1
  5. De igual forma, se deberá proporcionar una gráfica que compare la el área bajo la curva (ROC-AUC).

Se deberá entregar un archivo *ipynb* por cada experimento en el punto 3, en el cual deberá contener una breve explicación del experimiento. Para el caso del punto 4 y 5, se deberá incluir un archivo .md (Markdown) o ipynb con conclusiones de la práctica.


**Nota:** * En caso de no implementar su propia versión de los algoritmos mencionados y utilizar la librería scikit-learn, se deberá incluir los mismos puntos pero con el dataset MNIST, separando cada caso en carpetas distintas.
