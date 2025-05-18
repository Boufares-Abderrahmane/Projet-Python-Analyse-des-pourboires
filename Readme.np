# Projet Python — Analyse des pourboires (Tips Dataset)

## Objectif du projet

Ce projet consiste à manipuler, explorer et analyser un jeu de données contenant des informations sur des repas au restaurant (note, pourboire, nombre de personnes, genre, type de repas, jour, etc.). L’objectif est de produire une **analyse descriptive et bivariée** à partir du fichier `Pourboire.csv`, tout en développant des compétences pratiques en Python avec **pandas**, **matplotlib** et **seaborn**.

L'ensemble des analyses a été réalisé dans le notebook `N1.ipynb`, puis complété avec des analyses bivariées dans le notebook `N2.ipynb`.

---

## Contenu du projet

### Fichiers principaux
- `N1.ipynb` : Notebook de préparation et d’analyse univariée du dataset
- `N2.ipynb` : Notebook d’analyse bivariée complémentaire
- `Pourboire.csv` : Fichier de données utilisé

---

## Outils & bibliothèques utilisées

- Python 3
- pandas
- numpy
- matplotlib
- seaborn

---

## Étapes de l’analyse

### Nettoyage et préparation
- Importation du fichier `Pourboire.csv`
- Vérification des types de variables et conversion si besoin (virgule → point pour les décimales)
- Renommage de la variable `nombre d’individus` en `n` (pour plus de simplicité)
- Création de nouvelles variables :
  - `note_par_individu`
  - `pourboire_par_individu`

### Analyse descriptive
- Description statistique des variables numériques
- Calcul des déciles des notes et des notes par individu
- Comparaison des observations :
  - Clients avec une note < D1 vs > D9
  - Tables à 1 personne vs 6 personnes
  - Déjeuner vs dîner
  - Selon le **genre**

### Visualisations
- Histogrammes des notes par individu, selon le genre et le repas
- Boxplots des notes par individu selon :
  - Le type de repas
  - Le jour de la semaine
- Nuages de points entre **note et pourboire** :
  - Différenciés selon le repas et les jours
  - Avec densités marginales
- Diagrammes en barres :
  - Nombre de personnes selon le type de repas
  - Version avec fréquences

### Analyse bivariée
Réalisée dans le notebook `N2.ipynb` :
- Études croisées entre les variables (note, pourboire, genre, repas, jour, nombre de personnes)
- Représentations graphiques croisées
- Tests statistiques et observations des distributions

---

## Résultats clés

- La note moyenne augmente avec le nombre de personnes
- Les repas du soir (dîner) tendent à générer des notes plus élevées
- Les hommes ont laissé en moyenne des pourboires plus élevés
- Une corrélation positive existe entre **note** et **pourboire**
- Des comportements distincts selon le moment du repas (déjeuner/dîner) et le jour

---

## Auteur

Projet réalisé par **Abderrahmane Boufares**  
boufares11@gmail.com

