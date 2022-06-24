# Labo-ML
Laboratoire de recherche de ML

# Besoins exprimés
L’architecture doit permettre de traiter les demandes de validation des pièces d'identité 
envoyées en flux sur l'application Web sous format .pdf ou .png . Elle doit permettre d’intégrer 
un retour humain pour les pièces jointes dont la prédiction de validation n’est pas certaine.
Une validation de pièces jointes doit être de l’ordre de 3 secondes. Elle doit permettre le suivi des performances des modèles déployés et les redéployer si décidé par le business ou de manière automatique si la performance va en dessous d’un certain seuil. Les modèles doivent correctement valider et rejeter avec un f1-score global de 80%.

# Outils d'environnement
- Une image python 3.9 qui contiendra comme librairies (mlflow, tensorflow, fastApi).
- Une image mongo db pour le stockage des performance du modèle.
- s3 pour le stockage des modèles déployés.

