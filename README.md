# Big-Data-Projet
### Moulin David - Gaildry Arthur - Bertrand Sébastien

Nous disposons de données bancaires divisées en trois parties : 

* train qui contient **1997419** opérations non frauduleuses et de **2581** opérations frauduleuses

* test qui contient **4003** opérations non frauduleuses et de **3997** opérations frauduleuses

* predict qui contient **2000** opérations dont on ne connait pas "l'état"

On souhaite créer un modèle d'apprentissage capable d'identifier des opérations frauduleuses.

Pour cela nous allons utiliser des algorithmes d'apprentissage supervisés.


Le Dossier Data-Analysis contient les notebooks des 3 méthodes utilisées : 

* Arbre de décision 
* SVM
* Réseaux de neurones

Le dossier PushToS3 contient le script qui permet de mettre les fichiers csv sur un bucket d'AWS.


