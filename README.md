# 🎓 Projet ML : Insertion Professionnelle des Diplômés de Master

> **Description** : Ce projet de Machine Learning a pour objectif d'analyser et de modéliser l'insertion professionnelle des étudiants diplômés d'un Master en France, en se basant sur les données ouvertes de l'Enseignement Supérieur et de la Recherche (ESR).

## 📁 Structure du projet

Voici les fichiers clés présents dans ce dépôt :

* **`Projet.ipynb`** : Le notebook Jupyter principal contenant l'analyse exploratoire des données (EDA), les étapes de nettoyage, et l'entraînement du modèle de Machine Learning.
* **`fr-esr-insertion_professionnelle-master.csv`** : Le jeu de données brut original.
* **`fr-esr-cleaned.csv`** : Le jeu de données après l'étape de nettoyage et de prétraitement (prêt pour l'entraînement).
* **`modele_insertion_master.pkl`** : Le modèle de Machine Learning final entraîné et exporté (prêt à être réutilisé pour des prédictions sans avoir à le réentraîner).
* **`model_metadata.json`** : Fichier contenant les métadonnées et la configuration du modèle sauvegardé.

## 🛠️ Technologies utilisées

* **Langage :** Python 3
* **Environnement :** Jupyter Notebook
* **Bibliothèques principales (estimées) :**
  * `pandas` & `numpy` (Manipulation et nettoyage des données)
  * `matplotlib` / `seaborn` (Visualisation des données)
  * `scikit-learn` (Création, entraînement et sauvegarde du modèle)

## ⚙️ Comment tester le projet en local ?

1. **Cloner ce dépôt :**
   ```bash
   git clone [https://github.com/mattmathbg/Projet_ML.git](https://github.com/mattmathbg/Projet_ML.git)
   cd Projet_ML
   ```

2. **Lancer Jupyter Notebook :**
   Assure-toi d'avoir installé les bibliothèques nécessaires (pandas, scikit-learn, etc.), puis lance la commande :
   ```bash
   jupyter notebook
   ```

3. **Explorer :**
   Ouvre le fichier `Projet.ipynb` pour suivre ma démarche étape par étape, de l'exploration des données brutes jusqu'à la création du modèle final.

## 👨‍💻 Auteur

**Mattéo** - Étudiant en Informatique à l'Université de Lorraine.

* [Mon Profil GitHub](https://github.com/mattmathbg)
