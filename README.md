# classification_type_cancer_du_sein
Classer le type de cancer
Interpretation du Model Ce code définit un modèle de réseau neuronal séquentiel à l'aide de l'API Keras de TensorFlow. Le modèle comporte trois couches entièrement connectées, avec 64 neurones dans la couche d'entrée, 32 neurones dans la couche cachée et 1 neurone dans la couche de sortie. La fonction d'activation utilisée à la fois dans les couches d'entrée et cachée est ReLU (unité linéaire rectifiée), qui est couramment utilisée dans les réseaux de neurones.

La couche d'entrée a une forme d'entrée de (30,), ce qui signifie que le modèle attend des données d'entrée avec 30 entités. La couche de sortie a un seul neurone avec une fonction d'activation sigmoïde, ce qui est approprié pour les problèmes de classification binaire.

Le modèle comprend également une couche d'abandon avec un taux de 0,2, qui abandonne de manière aléatoire 20 % des unités d'entrée pendant l'entraînement pour aider à prévenir le surajustement.
