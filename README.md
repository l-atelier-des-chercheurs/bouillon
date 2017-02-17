# bouillon

[fr]
Cet espace est destiné à accueillir un outil pour enseigner la programmation pour créer des formes (creative coding). Basé sur [p5.js](https://p5js.org/), bouillon sera accessible par une URL et reprendra les options de base pour éditer du code et le faire tourner en temps réel. La différence avec un éditeur de code habituel est que le code de chaque personne connecté à cette page sera visible et accessible par tous à chaque instant, et pourra être exécuté en un click de manière à permettre et à inciter à collaborer, s'inspirer ou détourner le code des autres participants.

Bouillon comportera les fonctionnalités suivante (à plus ou moins long terme) :
- encart d'écriture du code
- bouton de lecture du code, exécutant le programme dans un encart dédié
- color-coding
- recherche du mot sélectionné dans la doc de p5.js
- un encart pour chaque personne connecté à la page, visible par tous et mise à jour en direct
- bouton de lecture du code pour chaque autre encart, pour afficher le rendu du code d'une autre personne
- des onglets autour de l'encart personnel pour "stocker" du code : par défaut, l'utilisateur est sur le 1. Il peut passer au 2 pour écrire un nouveau code sans perdre le 1, ou tester le code de quelqu'un 
- bouton de copie, qui récupère l'intégralité du code d'un autre encart pour le coller dans l'onglet en cours (après une confirmation s'il existe déjà du code dans l'onglet)
- un mode "collaboratif", permettant d'éditer le code d'un autre utilisateur directement dans sa fenêtre. Ce mode est opt-in, c'est à dire qu'il faut cocher une case pour autoriser l'édition extérieure (et éviter qu'elle ne soit intrusive). 
	- Idéalement, lorsqu'un autre utilisateur souhaite éditer un encart qui ne lui appartient pas, l'auteur de l'encart devrait avoir une notification et une demande d'autorisation individuelle.
- un champ en haut de page permet de préciser un nom identifiant chaque individu. Par défaut, ce champ affiche une chaine de caractère générée (animal + adjectif ? type "aigle perçant" ou "chat aveugle").

Un croquis pour visualiser ça :

![image](https://cloud.githubusercontent.com/assets/1948417/23075461/d8525858-f53c-11e6-81a2-5852b1df0bb1.png)
