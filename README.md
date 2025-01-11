# Attack-and-anomaly-detection-in-IoT
# Attack and Anomaly Detection in IoT

Ce projet vise à détecter les attaques et les anomalies dans les systèmes IoT (Internet des Objets) en utilisant des techniques de traitement de données, d'apprentissage automatique et d'analyse de séries temporelles. Le projet est structuré autour d'un notebook Jupyter qui contient des scripts pour le prétraitement des données, la détection d'anomalies, et la visualisation des résultats.

---

## 📋 Table des matières

1. [Structure du projet](#structure-du-projet)
2. [Installation](#installation)
3. [Utilisation](#utilisation)
4. [Données](#données)
5. [Auteurs](#auteurs)
6. [Licence](#licence)
7. [Remarques](#remarques)

---

## 🏗️ Structure du projet

Le projet est organisé en plusieurs sections principales :

1. **Prétraitement des données** :
   - **Nettoyage des données** : Gestion des valeurs manquantes et correction des valeurs inattendues.
   - **Normalisation** : Normalisation des données pour préparer les données à l'analyse.
   - **Visualisation** : Visualisation des données nettoyées pour comprendre leur distribution.

2. **Détection d'anomalies** :
   - **Modèles de détection d'anomalies** : Utilisation de modèles d'apprentissage automatique pour détecter les anomalies dans les données IoT.
   - **Évaluation des modèles** : Évaluation des performances des modèles en utilisant des métriques telles que la précision, le rappel, et le F1-score.

3. **Détection d'attaques** :
   - **Identification des attaques** : Utilisation de techniques spécifiques pour identifier les attaques potentielles dans les données IoT.
   - **Visualisation des attaques** : Visualisation des points de données identifiés comme des attaques.

4. **Visualisation des résultats** :
   - **Graphiques et tableaux** : Visualisation des résultats de la détection d'anomalies et d'attaques pour une interprétation facile.

---

## 🛠️ Installation

Pour exécuter ce projet, vous devez avoir installé les bibliothèques suivantes :

- `numpy`
- `matplotlib`
- `pandas`
- `scikit-learn`
- `seaborn`

Vous pouvez installer ces bibliothèques en utilisant `pip` :

```bash
pip install numpy matplotlib pandas scikit-learn seaborn

🚀 Utilisation
Clonez ce dépôt sur votre machine locale :

git clone https://github.com/votre-utilisateur/Attack-and-anomaly-detection-in-IoT.git
cd Attack-and-anomaly-detection-in-IoT

📊 Données
Le projet utilise un fichier CSV nommé mainSimulationAccessTraces.csv qui contient des données simulées d'accès IoT. Ce fichier inclut plusieurs colonnes telles que :

sourceID
sourceAddress
sourceType
value
timestamp
