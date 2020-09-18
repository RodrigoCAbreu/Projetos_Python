O objetivo deste estudo de caso é mostrar a você uma aplicação prática de Machine Learning com o algoritmo SVM (Support Vector Machines) e PCA (Principal Component Analysis) para redução de dimensionalidade.

Essa abordagem trata o reconhecimento de face como um problema de reconhecimento bidimensional, aproveitando o fato de que as faces normalmente estão na posição vertical e, portanto, podem ser descritas por um pequeno conjunto de características 2D. As imagens de rosto são projetadas em um espaço de recurso ('espaço de rosto') que melhor codifica a variação entre imagens de rosto conhecidas.

O PCA é aplicado para reduzir a dimensionalidade dos dados e então treinar o modelo SVM para uma tarefa de classificação.