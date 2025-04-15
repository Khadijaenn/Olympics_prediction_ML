# 🥇 Prédiction des médailles aux Jeux Olympiques

## 🎯 Objectif du projet
Ce projet a pour but de développer un modèle prédictif capable d'estimer le nombre de médailles remportées par chaque pays lors des Jeux Olympiques, en se basant sur des données historiques et des variables socio-économiques telles que le PIB, la population et les performances passées.

---

## 📊 Données utilisées
Les données proviennent d’un dataset nommé **"Olympics Dataset"**, contenant :
- Les performances historiques des pays (nombre de médailles)
- Des variables explicatives comme le PIB, la population, etc.

---

## 🔍 Méthodologie

### 1. Exploration et préparation des données
- Suppression ou imputation des valeurs manquantes (`na.omit`)
- Visualisation des distributions et corrélations via des graphiques

### 2. Modélisation
- Modèle de **régression linéaire**
- Variables utilisées : PIB, population, performances passées
- Séparation des données en **ensemble d'entraînement** et **ensemble de test**

### 3. Évaluation du modèle
- Métrique principale : **Erreur quadratique moyenne (RMSE)**
- Visualisation des erreurs (différences entre valeurs réelles et prédites)

---

## 📈 Résultats

- La majorité des prédictions sont proches des valeurs réelles
- Quelques erreurs significatives (sous-estimation de -4 ou surestimation de +2)
- Les erreurs semblent liées à des cas atypiques ou à la complexité du phénomène

---

## 💡 Recommandations

1. Ajouter d'autres variables (ex: budget alloué au sport, climat, infrastructures)
2. Tester des modèles plus avancés : Random Forest, Gradient Boosting
3. Analyser plus en profondeur les erreurs pour ajuster le modèle

---

## 🗂️ Structure du projet

