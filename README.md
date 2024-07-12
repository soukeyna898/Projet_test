**Cours :** INF 6243 Techniques d’apprentissage

**TP2 – Hiver 2024 :** Classification

**Date limite pour remettre votre travail :** 22 mars 2024`

**Modalités de travail:**

1.  Les TPs se feront individuellement sur Python.
2.  La remise des TP doit se faire sur Moodle.
3.  Un retard de remise de TP de $n$ journées va causer la perte de $20 n$ points.  


**Description des données:**

La description originale des données est sur le site : https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

L’ensemble contient 3000 instances de données de clients et vise à étudier la prédiction du défaut de paiement. Chaque client est décrit sur 23 attributs numétique.  

**Implantation demandée**

On vous demande de tester la classification supervisée avec les algorithmes suivants :

*   KPPV (à 7 voisins)
*   Arbre de décision (profondeur maximale 10)
*   Classificateur de Bayes
*   SVM (version linéaire)
*   Réseau de neurones à deux couches cachées
* 	Foret aléatoire (T=100)


**Instructions:**


*   Utiliser 80 % des données pour l’entrainement et 20% pour la validation).

* Remettre votre devoir dans ce fichier Jupyter, avec une cellule pour chaque algorithme.

*   Afficher les métriques suivantes pour la validation de la classification : exactitute, précision, rappel, matrice de confusion.
Utiliser les fonctions : **accuracy_score, recall_score, precision_score, confusion_matrix** de  sklearn.metrics

*   Il est préférable d’équilibrer les classes Y=0 et Y=1 pour un meilleur entrainement.  Utiliser la fonction **imblearn.over_sampling.RandomOverSampler**

* Il est préférable de centrer et standardiser les données.
Utiliser la fonction **sklearn.preprocessing.StandardScaler**


