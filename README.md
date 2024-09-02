# READ ME (ENGLISH VERSION)

## 2nd year Master's Technical Test Project
Developed with Unreal Engine 5


2nd year Master's TECHNICAL TEST README
SELECTED TOPIC: Construction Tool
============================================================

Controls:

- Move the character: Z Q S D (move forward, move left, move backward, move right)

- The mouse is used to move the camera

- Open construction mode: B (A green square will appear once you press the B key.)

- Browse available blocks: Mouse wheel (scroll down and up) 
NOTE: There are 3 available blocks: a cube, a floor, and a wall!

- Rotate the selected block: R (Each block rotates 45° each time you press the R key)

- Place the selected block: Left Click

- Delete the block you are aiming at: X

- Randomly change the color of the block you are aiming at: C 
NOTE: The color is chosen from 4 different materials.

- Quit the game: Escape (ESC)
 
Additional Informations:
===================================

- When a block can be placed in the world, the selected block in construction mode lights up green; otherwise, it turns red.

- It is impossible to place a block in the air without another adjacent block beneath it.

- It is possible to place and snap a block on top of another block (whether it’s the same block or a different one).

- Blocks rotate 45° each time you press the R key.

- All blocks can snap to each other, even if they are different types. The only exception is the basic cube, which cannot snap to other blocks besides itself (this decision was made because there is little interest in snapping a cube to other blocks available).

- There is a bug with the collision boxes of static meshes when snapping a wall to a floor, and then trying to place and snap another wall or floor to the previously placed block. Note: Despite this, all - blocks are still snappable to each other. You just need to find the right angle and/or collision box of the placed block at times.

- The destruction of blocks (X key) and the random color change of blocks (C key) operate within the same radius as placing blocks.


Potential Improvements / Additional Features:
================================================================
- Selection of blocks in construction mode via a UI serving as a block selection menu
- Ability to move a placed block elsewhere without having to delete it
- Manually change the color of blocks (using a "paintbrush" tool)
- Add more blocks to increase creation possibilities
- Improve the collision boxes of static meshes to ensure consistency when snapping blocks together




# READ ME (VERSION FRANCAISE)

## Projet_M2TestTech

Developed with Unreal Engine 5


READ ME DU TEST TECHNIQUE M2
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


Informations en plus:
===========
- Lorsqu'un bloc est posable, le bloc choisi dans le mode de construction s'allume en vert sinon il devient rouge.

- Il est impossible de poser un bloc en l'air sans qu'un autre bloc adjacent ne se trouve en dessous de lui.

- Il est possible de poser et de snap un bloc au dessus d'un autre bloc (bloc différent ou même bloc).

- La rotation des blocs se fait à 45° à chaque fois que l'on appuie sur la touche R

- Tous les blocs peuvent s'accrocher (snapping) entre eux même s'il ne s'agit pas du même bloc placé. Seul le cube de base ne peut pas s'accrocher à d'autres blocs que lui même 
(choix fait car peu d'intérêt d'accrocher un cube aux autres blocs mis à disposition)

- Bug sur les collisions box des static meshes lorsqu'il s'agit de snap un mur avec un sol et que l'on souhaite ensuite poser et snap un autre mur ou un autre sol au bloc posé précédemment.
/!\ Il est quand même important de noter que TOUS les blocs sont snappables entre eux malgré cela. Il faut trouver le bon angle et/ou réussir à avoir la bonne collision box du bloc posé par moment.

- La destruction des blocs (Touche X) et le changement de couleur aléatoire des blocs (Touche C) se fait dans le même rayon que celui pour poser les blocs.


Angle d'amélioration possible / Fonctionnalité ajoutable :
=
- Séléction des blocs dans le mode de construction via une UI servant de menu de séléction de bloc
- Pouvoir bouger ailleurs un bloc posé sans avoir à le supprimer
- Changer la couleur des blocs manuellement (outil "pinceau")
- Rajout d'autres blocs pour augmenter les possibilités de création
- Améliorer les collision box des static mesh pour qu'elle soit pareil lors du snapping d'un bloc à un autre 
