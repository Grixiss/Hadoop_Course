# Cours de formation Apache Hadoop

Ce cours est destiné à aider les développeurs, les chefs de projets, les data-scientists, et les architectes à comprendre et à maîtriser l'écosystème Hadoop.

## Jour 1

### Module 1 : Introduction à Hadoop

#### Objectifs pédagogiques :
- Comprendre le fonctionnement du Framework Hadoop
- Apprendre les principes des projets et modules Hadoop Common, HDFS, YARN, MapReduce
- Savoir utiliser YARN pour gérer les jobs MapReduce

#### Cours :

Hadoop est un framework open source qui facilite le stockage et le traitement de grands ensembles de données à travers des grappes de serveurs. Il est composé de quatre modules principaux :

Hadoop Common : Il s'agit des bibliothèques et des utilitaires communs requis par d'autres modules Hadoop.
Hadoop Distributed File System (HDFS) : Il s'agit d'un système de fichiers qui stocke les données sur les nœuds de la grappe, offrant une très haute bande passante de données.
Hadoop YARN : Il s'agit d'un gestionnaire de ressources et un système de planification de tâches.
Hadoop MapReduce : Il s'agit d'un algorithme de traitement en parallèle pour les grandes quantités de données.

#### Exercices :

**Exercice 1 : QCM**

Quelle est la fonction principale de Hadoop ?

a. Traitement des données en temps réel
b. Traitement des transactions en ligne
c. Stockage et analyse de grandes quantités de données
d. Stockage de données relationnelles

Réponse correcte : c. Stockage et analyse de grandes quantités de données

**Exercice 2 : Travaux Pratiques**
Créer un cluster Hadoop à partir de zéro en utilisant Hadoop Common, HDFS, YARN et MapReduce.

### Module 2 : MapReduce

#### Objectifs pédagogiques :
- Comprendre le principe et les objectifs du modèle de programmation MapReduce
- Connaître les fonctions map() et reduce() et les couples (clés, valeurs)
- Savoir implémenter MapReduce avec le framework Hadoop

#### Cours :
MapReduce est un modèle de programmation pour le traitement en parallèle. Il divise une tâche en deux parties : une phase de "Map" où il effectue des opérations sur un ensemble de données, et une phase de "Reduce" où il agrège les résultats. En utilisant MapReduce, nous pouvons traiter de grandes quantités de données de manière distribuée sur un cluster de machines.

Dans la phase Map, les données en entrée sont divisées en paires clé-valeur. Ensuite, chaque paire clé-valeur est traitée et une sortie intermédiaire est générée. Dans la phase Reduce, les paires clé-valeur intermédiaires sont regroupées par clé et traitées pour générer la sortie finale.

#### Exercices :

**Exercice 3 : QCM**
Quelle est la fonction de la phase Map dans MapReduce ?
a. Elle trie les données
b. Elle réduit les données à un ensemble plus petit
c. Elle divise les données en paires clé-valeur
d. Elle fusionne les données en un seul ensemble

Réponse correcte : c. Elle divise les données en paires clé-valeur

**Exercice 4 : Travaux Pratiques**
Développer un algorithme MapReduce pour compter le nombre de mots dans un texte. Utiliser le livre "The Project Gutenberg EBook of Alice's Adventures in Wonderland" comme ensemble de données.

## Jour 2

### Module 3 : Programmation avec Hadoop

#### Objectifs pédagogiques :
- Savoir configurer des jobs MapReduce
- Comprendre les interfaces principales de Hadoop
- Connaître le processus de production d'un job MapReduce

#### Cours :
[Contenu du cours]

#### Exercices :

**Exercice 5 : Travaux Pratiques**
Développer un job MapReduce pour filtrer les tweets contenant un mot spécifique à partir d'un ensemble de données de Twitter.

### Module 4 : Streaming avec Hadoop

#### Objectifs pédagogiques :
- Comprendre le streaming Map/Reduce
- Savoir créer des jobs Map/Reduce en Python

#### Cours :
[Contenu du cours]

#### Exercices :

**Exercice 6 : Travaux Pratiques**
Créer un job de streaming Map/Reduce en Python pour compter le nombre de mots dans un texte.

## Jour 3

### Module 5 : Pig et Hive

#### Objectifs pédagogiques :
- Connaître les bases de Pig et Hive
- Savoir écrire des requêtes Pig et Hive

#### Cours :
[Contenu du cours]

#### Exercices :

**Exercice 7 : QCM**
Quel outil permet d'écrire des requêtes SQL pour extraire des données de Hadoop?
a. Pig
b. Hive
c. HBase
d. Spark

Réponse correcte : b. Hive

**Exercice 8 : Travaux Pratiques**
Écrire un script Pig pour compter le nombre de mots dans un texte.

**Exercice 9 : Travaux Pratiques**
Écrire une requête Hive pour obtenir le nombre total de tweets contenant le mot "Hadoop".

### Module 6 : Sécurité en environnement Hadoop

#### Objectifs pédagogiques :
- Comprendre le mécanisme de gestion de l'authentification en environnement Hadoop

#### Cours :
[Contenu du cours]

#### Exercices :

**Exercice 10 : Travaux Pratiques**
Configurer l'authentification Kerberos pour un cluster Hadoop.

Ceci complète le cours de formation de trois jours sur Hadoop. Nous espérons que cela vous aidera à développer une bonne compréhension de Hadoop et de ses capacités.
