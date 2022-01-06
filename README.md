# Analyse des sites de camping en Ile-de-France
Dans ce projet du cours de Python pour les Data Scientists, nous regardons les sites de camping en Ile-de-France. Nous cherchons à faire un état des lieux de ces sites, non seulement en regardant les aménagements qui y sont, mais également en prenant en compte l'aspect de sécurité de ces sites, ces derniers étant éparpillés un peu partout dans la région Ile-de-France dans des endroits divers. Pour ce faire, nous prenons en compte les spécificités des sites de camping (classement, surface, etc.), ainsi que des facteurs externes qui concernent la sécurité (distance aux postes de police, hôpitaux, etc.). 

Nous vous recommandons de lire nos notebooks dans cet ordre : 

* prepare_data : nettoyage des bases de données et calcul des distances entre les sites de camping et les hôpitaux/postes de police les plus proches
* Visualisation : carte montrant les sites de camping et les aménagements/établissements aux alentours
* Clustering : clustering des sites de camping (et interprétation) avec une attention particulière portée sur l'aspect de sécurité
