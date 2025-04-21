# WeatherAPI – API météo simple avec Python

Ce projet est une API simple écrite en Python permettant de récupérer des informations météo depuis une source externe ou simulée. Il a pour but de servir de point d'entrée à des applications web ou mobiles cherchant à intégrer des données météorologiques.

# Objectif du projet

- Mettre en place une API REST minimale pour exposer des données météo
- Permettre une extension simple pour ajouter des endpoints, connecter à des services externes ou automatiser des rapports
- Offrir un déploiement simple et rapide via un script

# Technologies utilisées

- Python
- Requests
- FastAPI
- Shell Script (`startup.sh`) pour lancement rapide

# Structure du projet

```
- main.py             --> Script principal de l’API météo
-__init__.py         --> Initialisation du module
-requirements.txt    --> Dépendances Python
-startup.sh          --> Script de démarrage
- LICENSE             --> Droit d’utilisation
- .gitignore / .gitattributes → Fichiers Git
- README.md            --> Description du projet
```

# Fonctionnalités

- Récupération de données météo en temps réel ou simulées
- Réponses formatées en JSON
- Structure modulaire pour ajout de nouvelles fonctionnalités (prévisions, historique, alertes météo)
- Déploiement simple via script `startup.sh`

# Utilisation

1. Installer les dépendances :

```bash
pip install -r requirements.txt
```

2. Lancer le serveur :

```bash
sh startup.sh
```

Ou manuellement :

```bash
python main.py
```

# Auteur

Projet réalisé par BOMO MEKA JOSPIN MARIEL, dans le cadre d’un exercice de création d’API avec Python.
