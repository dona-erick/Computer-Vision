# Computer-Vision
# Défi de classification des animaux

### Pouvez-vous créer un algorithme de classification binaire pour distinguer les zèbres des éléphants ?


## Description
   ### Objectif:
   
   créer un modèle d'apprentissage automatique pour prédire avec précision la probabilité qu'une image contienne un zèbre, 
   par opposition à un éléphant. Bien que cela puisse être une tâche facile pour les humains, les éléphants et les zèbres, 
   votre ordinateur trouvera cela un peu plus difficile.

  L'ensemble de données contient plus de 18 000 images de zèbres et d'éléphants, 
  échantillonnées à partir de la collection Snapshot Serengeti de plus de 6 millions d'animaux. 
  Les données ont été récupérées à partir du référentiel de données de l'Université du Minnesota, https://doi.org/10.13020/D6T11K , 
  sous une licence Creative Commons , à partir d'une étude intitulée : Images de pièges photographiques utilisées dans « Identification des espèces animales
  dans les images de pièges photographiques à l'aide de l'apprentissage profond et de la science citoyenne » .*

## Évaluation
La mesure d’évaluation pour ce défi est l’ aire sous la courbe .

Votre fichier de soumission devrait ressembler à :

étiquette d'identification
ASG001dw7n_1.jpeg 1
ASG001dw7q_2.jpeg 0
ASG001dw7s_1.jpeg 0


## Techniques utilisées
 . Labelisser les données (Label 0 pour "éléphants", 1 pour "zèbres")
 . Redimensionnage des images (size = 224, 224)
 . Visualisation des images 
 . Data augmentation pour améliorer 

## Outils utilisées

 . Tensorflow et keras
 . Pytorch !pip install torch if you want to install 
 . Python
