# Projet_M2TestTech

Developed with Unreal Engine 5

======================================================
READ ME DU TEST TECHNIQUE M2 DE MAC VICAR THOMAS
======================================================
SUJET SÉLÉCTIONNÉ : Outil de construction de bâtiment
======================================================

Contrôles :

- Bouger le personnage: Z Q S D (avancer, aller à gauche, reculer, aller à droite)

- La souris sert à bouger la caméra

- Ouvrir le mode de construction: B (Un carré vert apparaît alors une fois appuyé sur la touche B.)

- Parcourir les blocs à disposition: Molette de la souris (Vers le bas et vers le haut)
A NOTER: Il y a 3 blocs disponibles: un cube, un sol et un mur!

- Tourner le bloc séléctionné: R (Chaque bloc se tourne à 45° à chaque fois que l'on appuye sur la touche R) 

-Poser le bloc séléctionné: Clic Gauche

- Supprimer le bloc que l'on vise: X

- Changer aléatoirement la couleur du bloc que l'on vise: C
A NOTER: La couleur est choisie entre 4 matériaux différents.

- Quitter le jeu: Echape (ESC)

=================================================================================================================
Informations en plus:

- Lorsqu'un bloc est posable, le bloc choisi dans le mode de construction s'allume en vert sinon il devient rouge.

- Il est impossible de poser un bloc en l'air sans qu'un autre bloc adjacent ne se trouve en dessous de lui.

- Il est possible de poser et de snap un bloc au dessus d'un autre bloc (bloc différent ou même bloc).

- La rotation des blocs se fait à 45° à chaque fois que l'on appuie sur la touche R

- Tous les blocs peuvent s'accrocher (snapping) entre eux même s'il ne s'agit pas du même bloc placé. Seul le cube de base ne peut pas s'accrocher à d'autres blocs que lui même 
(choix fait car peu d'intérêt d'accrocher un cube aux autres blocs mis à disposition)

- Bug sur les collisions box des static meshes lorsqu'il s'agit de snap un mur avec un sol et que l'on souhaite ensuite poser et snap un autre mur ou un autre sol au bloc posé précédemment.
/!\ Il est quand même important de noter que TOUS les blocs sont snappables entre eux malgré cela. Il faut trouver le bon angle et/ou réussir à avoir la bonne collision box du bloc posé par moment.

- La destruction des blocs (Touche X) et le changement de couleur aléatoire des blocs (Touche C) se fait dans le même rayon que celui pour poser les blocs.

=========================================================================================================================================================================================================
Angle d'amélioration possible / Fonctionnalité ajoutable :

- Séléction des blocs dans le mode de construction via une UI servant de menu de séléction de bloc
- Pouvoir bouger ailleurs un bloc posé sans avoir à le supprimer
- Changer la couleur des blocs manuellement (outil "pinceau")
- Rajout d'autres blocs pour augmenter les possibilités de création
- Améliorer les collision box des static mesh pour qu'elle soit pareil lors du snapping d'un bloc à un autre 