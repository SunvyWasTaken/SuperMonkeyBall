# **Super-monkey Ball

TP Super Monkey Ball

## **TODO**

> ## **Monde**
> Est un ensemble de plusieurs levels.

> ## **Level**
> Un level est composé de plusieurs plateformes, de checkpoint optionnel et d'un point d'arrivée.

> ## **Timer**
> Le personnage à 60 secondes pour arriver à la fin du level.
> 
> Si le timer arrive à 0 recommencer le level et enlever une vie au personnage.

> ## **Personnage**
> Le personnage est déplacé à l'aide des flèches directionnellesdirectionnel, ZQSD ou le joystick de la manette.
>
> Lorsque le personnage tombe trop loin du level recommencer au dernier checkpoint ou au début du level.
>
> Le personnage à 3 vie de base si il les perds toute le monde recommence.

> ## **Checkpoint**
> Joue une animation quand le personnage rentre en collision.
>
> Est un point de sauvegarde pour éviter de recommencer le level de zéro.

> ## **Point d'arrivée**
> Le personnage peut entrer en collision avec les rebords.
>
> Termine le level et passe au level suivant.
>
> Si il s'agit du dernier level afficher le menu de fin de monde.
>
> Joue une animation de fin de level.

> ## **Camera**
> Regarde toujours le personnage
>
> Tilté la caméra en fonction de la direction du personnage.
>
> Récupérer la surface normal de la surface ou le personnage est présent afin de tourner la caméra et ne pas ce retrouver dans le sol.

## **Pour aller plus loin**
> ## **Collectible**
> Ajouter des collectibles sur le chemin du personnage
>
> Joue un son et emet des particules.
>
> Redonne une vie au personnage.

> ## **Menu**
> Créer un menu de sélection de monde.

> ## **Camera**
> Faire en sorte de désactivé le déplacement à l'aide de la normal de la surface suivant la surface présente en dessous du personnage. Cela évite certain problême avec l'inclinaison de surface.

> ## **Personnage**
> Faire en sorte que le joueur rebondisse sur les plateformes un peu plus surélevé.
>
> Faire en sorte qu'un character humanoide soit au centre de la sphere du personnage. Celui ci ne doit pas tourner sur lui meme en suivant la boule.
>
> Ajouter une animation indiquant quand le joueur est trop proche d'une bordure.