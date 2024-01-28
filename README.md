# Application-Design---Projet-1

## Bonjour Monsieur,
Dans ce dépôt GitHub, vous trouverez le premier projet d'Application Design dans un fichier .zip

## INFORMATIONS GENERALES : 
Nom : DEBETTE Jeanne
Design choisi : les plantes
Langage : XML
Point important : mon émulateur sur Android Studio n'a pas fonctionné. Il ne s'est pas lancé, malgré plusieurs essais et sans relever d'erreur repérable (à ma connaissance). Je n'ai donc pas pu tester mon rendu. J'ai tout de même tenté au maximum de faire des contraintes entre les éléments pour limiter les mouvements indésirables de ces derniers (selon la résolution d'écran par exemple).

## COMMENTAIRES DE CODE :
La réalisation de ce projet s'est faite en 2 temps : Le haut du Design (icônes en haut à droite, lignes d'introduction et bandeau de menu avec les trois choix), puis les 4 zones avec chacune une plante.

Pour la première partie, j'ai divisé le haut du Design en 3 :
Les icônes à droite (rattachées entre elles avec des marges et ancrées sur le bord droit de l'écran)
Puis les éléments sur la gauche (plante puis texte en deux parties). La couleur des zones de texte a été personnalisée et une des deux zones a été mise en gras. La taille de la police a également été codée dans le fichier XML.
Enfin, la troisième partie est le menue en bandeau. Il est rattaché au zones de textes de la première partie et est centré sur l'écran. Les éléments internes sont dépendant du bandeau large (nommé "rectangleL" dans le XML et "bandeau_vert" dans les fichiers en raison des contraintes de nomination des fichiers).

Pour la seconde partie, les réalisations des 4 éléments a été identique pour chacun :
Création de la "boîte blanche" (ayant déjà le nom de la plante et le rond vert via l'exportation depuis Figma), ancrée par rapport au bandeau de menu, au bord gauche de l'écran et par rapport aux autres boîtes du Design.
Puis insertion de la plante dans la boîte (ajustement manuel des marges si nécessaire pour s'approcher du Design Figma)
Enfin, insertion de la flèche blanche (pareil : contrainte sur la boîte blanche puis ajustement manuel des marges --> les différentes boîtes n'ayant pas la même taille les unes par rapport aux autres)

A noter que pour chaque élément de cette seconde partie, j'ai adopté la nomenclature suivante : nomelement_position, avec en position : h pour haut, b pour bas, g pour gauche et d pour droite, permettant ainsi de repérer les éléments mis en relation entre eux.

## Bonne correction !
