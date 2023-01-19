# 2- Technologies adaptés

## a) Hadoop

**Hadoop** est un logiciel open-source pour le stockage et le traitement de big data dans un environnement distribué. Il est conçu pour traiter de gros volumes de données sur un cluster de matériel de base. Hadoop fournit un système de fichiers distribué (HDFS) pour le stockage des données et un framework pour le traitement de ces données en utilisant le modèle de programmation MapReduce. Il comprend également des modules supplémentaires pour des tâches telles que la gestion des données, l'accès aux données et la gouvernance des données. Hadoop est largement utilisé dans les applications big data et est considéré comme une technologie clé dans l'écosystème big data.<br/><br/>
En parlant de Hadoop, on doit parler nécessairement du modéle de programmation mapReduce.<br/><br/>
**MapReduce** est un modèle de programmation et une implémentation associée pour traiter et générer de grands ensembles de données avec un algorithme parallèle et distribué sur un cluster. Il s'agit d'un composant central de l'écosystème Hadoop, utilisé pour effectuer des traitements de données à grande échelle sur des clusters distribués.<br/>
Le modèle de programmation MapReduce se compose de deux fonctions principales :<br/>
- La fonction "Map" : qui traite une paire clé/valeur pour générer un ensemble de paires clé/valeur intermédiaires.
* La fonction "Reduce" : qui fusionne toutes les valeurs intermédiaires associées à la même clé intermédiaire.<a/>
<br/>
MapReduce est bien adapté au traitement de grandes quantités de données en parallèle et permet un traitement efficace des données sur des grappes de matériel de base. Cela en fait un choix populaire pour les applications big data, telles que data mining, log processing et l'analyse de données à grande échelle.

## b) Spark

**Apache Spark** est un système informatique distribué open source, utilisé pour le traitement et l'analyse des données volumineuses. Il peut traiter des données par lots et en temps réel, ainsi que des données de différents formats, notamment structurées, semi-structurées et non structurées. Spark est conçu pour être hautement évolutif et efficace, et il comprend une variété de bibliothèques intégrées pour des tâches telles que le SQL, le streaming et l'apprentissage automatique. Il peut fonctionner sur une variété de gestionnaires de clusters, y compris Apache Mesos, Hadoop YARN, et son propre gestionnaire de cluster autonome. Spark est souvent utilisé en conjonction avec d'autres technologies de big data telles que Hadoop et Apache Cassandra.

## c) Dask

**Dask** est une bibliothèque open-source de traitement parallèle pour l'analyse en Python. Elle permet aux utilisateurs d'exploiter toute la puissance de leurs ressources CPU et mémoire sans avoir besoin d'algorithmes parallèles complexes ou de copies redondantes des données. Dask permet le calcul parallèle grâce à l'ordonnancement des tâches et aux algorithmes bloqués, qui divisent les gros calculs en morceaux plus petits et plus faciles à gérer. Dask est souvent utilisé en remplacement de cadres de calcul parallèle plus importants, comme Apache Spark, et il peut gérer des calculs plus importants que la mémoire et hors cœur, en plus des bibliothèques Python existantes, comme NumPy, Pandas et Scikit-learn. Dask fournit également un tableau flexible (Dask Array) et un dataframe (Dask Dataframe) qui imitent l'interface de leurs homologues Numpy et Pandas respectifs, mais qui fonctionnent sur des données distribuées et en mémoire plus importante.

