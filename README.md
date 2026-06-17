# PROJET DE FIN DE MODULE

## DEEP LEARNING

### Conception, Implémentation, Comparaison et Analyse Critique de Modèles de Deep Learning pour Données Tabulaires, Images et Séquences

---

### Réalisé par

**RAMZI SAAD**

### Module

**Deep Learning**

### Encadré par

**M. Batal Mousaab**

### Établissement

**École Marocaine des Sciences de l’Ingénieur (EMSI) – Casablanca**

**Département Informatique**

### Année Universitaire

**2025 – 2026**

---

# Présentation Générale du Projet

## Contexte

Le Deep Learning constitue aujourd’hui l’un des domaines les plus influents de l’intelligence artificielle moderne. Grâce à sa capacité à apprendre automatiquement des représentations complexes à partir de grandes quantités de données, il est utilisé dans de nombreux secteurs tels que la vision par ordinateur, le traitement automatique du langage naturel, les systèmes de recommandation et l’aide à la décision.

Dans ce contexte, ce projet a pour objectif d’étudier et de comparer plusieurs architectures majeures de réseaux de neurones profonds en utilisant le framework PyTorch.

## Objectif Général

L’objectif principal consiste à concevoir, entraîner et évaluer différentes architectures de Deep Learning adaptées à plusieurs types de données :

* Données tabulaires
* Images
* Données séquentielles et textuelles

L’étude met particulièrement l’accent sur la comparaison des performances obtenues ainsi que sur l’analyse des avantages et limites de chaque architecture.

---

# Organisation du Projet

## Partie I : Réseaux de Neurones Multicouches (MLP)

### Objectif

Mettre en œuvre un modèle de classification supervisée sur des données tabulaires réelles.

### Jeu de données

Breast Cancer Wisconsin Dataset

* 569 observations
* 30 caractéristiques descriptives
* Classification binaire

### Travaux réalisés

* Prétraitement des données
* Construction d’architectures MLP avec PyTorch
* Utilisation de nn.Module et nn.Sequential
* Comparaison de plusieurs méthodes d’initialisation :

  * Initialisation Gaussienne
  * Initialisation Constante
  * Initialisation Xavier
* Sauvegarde et chargement des modèles

### Résultat obtenu

Précision d’environ **97 %**

---

## Partie II : Réseaux de Neurones Convolutifs (CNN)

### Objectif

Étudier les mécanismes fondamentaux de la vision par ordinateur et développer un modèle CNN performant.

### Jeu de données

Fashion-MNIST

### Travaux réalisés

* Implémentation manuelle de la corrélation croisée
* Implémentation des opérations de pooling
* Conception d’une architecture LeNet améliorée
* Étude d’ablation :

  * Padding
  * Foulée (Stride)
  * Nombre de filtres
  * Convolutions 1×1
* Visualisation des cartes de caractéristiques

### Résultat obtenu

Précision d’environ **91 %**

---

## Partie III : Réseaux Récurrents et Architecture Seq2Seq

### Objectif

Analyser le comportement des modèles récurrents pour le traitement des données séquentielles.

### Modèles étudiés

* RNN
* LSTM
* GRU
* Seq2Seq

### Travaux réalisés

* Modélisation du langage
* Étude du problème de disparition du gradient
* Mise en œuvre du Gradient Clipping
* Architecture Encodeur–Décodeur
* Teacher Forcing
* Greedy Search
* Beam Search

### Métriques d’évaluation

* Perplexité
* Score BLEU

---

# Environnement de Développement

## Langage

Python 3.10+

## Bibliothèques utilisées

* PyTorch
* TorchVision
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Seaborn
* NLTK

---

# Méthodes d’Exécution

## Exécution sous Google Colab

1. Importer le notebook dans Google Drive.
2. Ouvrir avec Google Colaboratory.
3. Activer l’accélération GPU.
4. Exécuter les cellules dans l’ordre.

## Installation des dépendances

pip install torch torchvision scikit-learn matplotlib seaborn pandas numpy nltk

---

# Conclusion

Ce projet met en évidence l’adéquation entre la nature des données et l’architecture de Deep Learning utilisée. Les résultats obtenus démontrent que les MLP sont adaptés aux données tabulaires, les CNN aux données visuelles et les architectures récurrentes aux données séquentielles, confirmant ainsi l’importance du choix du modèle dans les applications d’intelligence artificielle modernes.
