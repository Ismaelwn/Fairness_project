# Fairness in Medical Data Analysis

## Description

Ce projet vise à analyser et à corriger les biais présents dans un jeu de données médical issu de **"Chest X-ray NIH 14 Dataset"**. L’objectif est d’examiner l’équité des diagnostics en fonction des différentes caractéristiques démographiques et médicales des patients, en utilisant des techniques d’analyse de données et de pré-traitement.

## Jeu de Données

Le jeu de données utilisé est un extrait de **Chest X-ray NIH 14 Dataset**, contenant **55 552** lignes, chaque ligne représentant un diagnostic. Un même patient peut apparaître plusieurs fois. Les données incluent :

- **Image Index** : Nom du fichier image de la radiographie.
- **Finding Labels** : Diagnostic(s) associé(s) à l’image.
- **Follow-up** : Suivi médical du patient.
- **Patient ID** : Identifiant unique du patient.
- **Patient Age** : Âge du patient.
- **Patient Gender** : Genre du patient.
- **View Position** : Position lors de la prise de vue.
- **OriginalImage Width** : Largeur de l’image.
- **OriginalImage Height** : Hauteur de l’image.
- **OriginalImagePixelSpacing x** : Résolution de l’image sur l’axe horizontal.
- **OriginalImagePixelSpacing y** : Résolution de l’image sur l’axe vertical.
- **Unnamed: 11** : Colonne sans informations pertinentes.

## Objectifs du Projet

1. **Analyse exploratoire des données (EDA)**
   - Analyse **univariée** : Étudier la distribution des variables.
   - Analyse **bivariée** : Identifier des corrélations entre variables.
   - Détection des biais potentiels liés à l'âge, au genre et aux diagnostics.

2. **Correction des biais**
   - Application des méthodes de **pré-traitement** étudiées en cours.
   - Normalisation et rééquilibrage des données.
   - Tests pour évaluer l’impact des corrections sur les prédictions et la fairness.

## Installation

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/Ismaelwn/Fairness_project.git
   ```
2. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
   ```
3. **Lancer l’analyse des données** :
   ```bash
   python projet.ipnyb
   ```



## Contributions

Les contributions sont bienvenues !

1. **Forker le dépôt**.
2. **Créer une branche** (`git checkout -b feature/NouvelleCorrection`).
3. **Commiter vos modifications** (`git commit -m "Correction d’un biais dans les données"`).
4. **Pousser votre branche** (`git push origin feature/NouvelleCorrection`).
5. **Ouvrir une Pull Request**.

## Licence

Ce projet est sous licence MIT.

