# **SuperMonkeyBall**

TP Super Monkey Ball

## **TODO**

> ## **Monde**
> Est un enssemble de plusieurs level.

> ## **Level**
> Tout le level doit être dans un même objet car le joueur controller l'inclinaison du level.

> ## **Timer**
> Le personnage à 60 secondes pour arriver à la fin du level.
> 
> Si le timer arrive à 0 recommencer le level et enlever une vie au personnage.

> ## **Character**
> Est soumi à la physique et bougera en fonction de l'inclinaison du level.
>
> Le personnage gagne de l'inertie avec le temps.
>
> Lorsque le personnage tombe trop loin du level recommencer au dernier checkpoint ou au début du level.
>
> Si le personnage à 3 vie de base si il les perds toute le monde recommence.

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
> Suit le personnage et tourne suivant la direction du personnage.

## **Pour aller plus loin**
> ## **Collectible**
> Ajouter des collectibles sur le chemin du personnage
>
> Joue un son et emet des particules.
>
> Redonne une vie au personnage.

> ## **Menu**
> Créer un menu de sélection de monde.