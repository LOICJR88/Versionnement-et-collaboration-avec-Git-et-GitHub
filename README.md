Projet Deep Learning - De la conception au déploiement de modèles de Deep Learning

Description
Ce projet fait partie des Travaux Pratiques de Deep Learning. Il implémente un réseau de neurones fully-connected pour la classification des chiffres manuscrits du dataset MNIST.

Objectifs
Construire et entraîner un modèle de Deep Learning avec Keras/TensorFlow
Suivre les expérimentations avec MLflow
Déployer le modèle via une API Flask
Conteneuriser l'application avec Docker
Mettre en place des bonnes pratiques de versionnement avec Git

Architecture du Projet
.
├── train_model.py          # Script d'entraînement du modèle
├── app.py                  # API Flask pour les prédictions
├── requirements.txt        # Dépendances Python
├── Dockerfile             # Configuration Docker
├── mnist_model.h5         # Modèle entraîné (généré)
└── README.md              # Documentation

Modèle
Architecture : Réseau fully-connected (Dense)
Couche d'entrée : 784 neurones (28×28 pixels)
Couche cachée : 512 neurones + ReLU + Dropout(0)
