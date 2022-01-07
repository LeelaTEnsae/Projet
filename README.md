# Analyse des sites de camping en Ile-de-France
Dans ce projet du cours de Python pour les Data Scientists, nous regardons les sites de camping en Ile-de-France. Nous cherchons à faire un état des lieux de ces sites, non seulement en regardant les aménagements qui y sont, mais également en prenant en compte l'aspect de sécurité de ces sites, ces derniers étant éparpillés un peu partout dans des endroits divers dans la région Ile-de-France. Pour ce faire, nous prenons en compte les spécificités des sites de camping (classement, surface, etc.), ainsi que des facteurs externes qui concernent la sécurité (distance aux postes de police, hôpitaux, etc.). 

Nous vous recommandons de lire nos notebooks dans cet ordre : 

* **prepare_data** : nettoyage des bases de données et calcul des distances entre les sites de camping et les hôpitaux/postes de police les plus proches, donne en sortie un fichier .csv contenant les variables principales qu'on utilise pour le clustering
* **clustering** : Réduction de la dimention du dataset avec l'analyse en composantes principales et clustering des sites de camping par la méthode kmeans. Avec une interprétation des qualités des différents clusters
* **Visualisation** : carte montrant les sites de camping et les aménagements/établissements aux alentours, analyse de la répartition géographique des différents clusters

**remarques importantes:**

En particulier, le premier notebook nécessite un certain temps d'exécution qui peut être trop grand, pour cela il est presque nécessaire de l'exécuter sur google colab

Dans les fichiers "visualisation" et "clustering", il est nécessaire d'importer les datasets .csv dans colab avant d'exécuter
