# Un Pong Monoplayer
Votre partiel du 14/12/2020

#### Déroulement

On éteint les téléphones et on coupe le son des PCs. Vous avez accès au web, mais pas de chat et cie. Je ne veux pas vous voir vous ballader sur les repos github de vos camarades, c'est pas un travail d'équipe cette fois. Si vous copiez le travail de vos collègues ce sera facile à voir et ce sera rapide à n0ter pour moi.

- 14h00 - 14h05 Prennez connaissance des consignes, posez les questions si il y en a. 
- 14h05 - 14h15 On ne code pas! Réfléchissez un peu sur papier à comment vous allez faire.
- 14h15 - 15h55 On ententend des ventilos de PC, des touches de clavier et rien d'autre.

-----------

Un petit aperçu de ce que j'attends [est visible ici](https://drive.google.com/file/d/1ypgUYziRdZlav33MX-wfUyRSb4CpwXQm/view?usp=sharing).

### Pour qui est fait ce jeu?
Une petite fille de 8 ans qui s’ennuie dans sa chambre.

- On reste minimal dans le graphisme (car ce n’est pas l’objet du partiel) mais gardez en tête que les petites filles de 8 ans adorent le rose sous toutes ses formes :\
- Le niveau de difficulté est facile, celui d’une petite fille de 8 ans qui ne joue pas beaucoup. 
- La balle ne va donc pas accélérer très vite.

L'objectif est bien d'**avoir un jeu jouable**. Si vous n'arrivez pas à afficher des petits coeurs pour les vies par exemple ce n'est pas très grave, affichez des ronds ou simplement un texte. Allez à l'essentiel, gérez bien votre temps. Faites des mises en ligne régulièrement sur github dès que vous avez réussi une étape et testez bien que ça fonctionne en ligne aussi bien qu'en local.



## Pour commencer

Créez un nouveau repo nommé `pong-monoplayer` sur votre github.

- initialisez votre repo avec un readme.md
- dans les settings activez github pages
- mettez dans votre readme le lien vers votre site ainsi créé... et vérifiez que ce lien marche!

Bref...faites la même chose que les autres fois :)

Vous pouvez partir de votre pong comme point de départ, [partir de mon code](https://github.com/davidmars/pong-jquery) ou repartir de zéro si vous êtes dingos, c’est comme vous le sentez.



## Screen de départ
Faire un écran de départ qui ressemble à ça :

![alt text](ecran-debut.png)

## Fonctionnement du Jeu

#### Contrôles asymétriques

- La joueuse en appuyant sur la touche flèche haut du clavier fait bouger la raquette gauche vers le haut et la raquette droite vers le bas

- La joueuse en appuyant sur la touche flèche bas du clavier fait bouger la raquette gauche vers le bas et la raquette droite vers le haut.

*Si vous ne parvenez pas à faire fonctionner le jeu avec les flèches du clavier, vous pouvez les remplacer par les touches H et B (sous entendu haut / bas)*

![alt text](ecran-3.png)

#### Accélération
La balle accélère un peu à chaque toucher de raquette.

#### Points
Chaque fois que la joueuse touche la balle, elle gagne 10 points.

#### Vies
Quand la joueuse rate la balle, elle perd une vie. 

### Screen de fin

Quand la joueuse a perdu ses 5 vies, on lui dit...
![alt text](ecran-fin.png)

Le bouton rejouer permet de refaire une partie, 

- la balle repart au centre
- le score est remis à zéro
- la vitesse réinitialisée
- la joueuse a de nouveau 5 vies.

## Bonus pour votre note

#### Qualité de code

- Il n’y a pas de fichiers inutiles
- Il n’y a pas de variables inutiles.
- Il n’y a pas de fonctions inutiles.
- Il n’y a pas de CSS ou HTML inutiles.
- Les classes sont dans des fichiers séparés, nommés correctement.

#### Pour frimer un peu

- Quand la balle touche une raquette, lui donner un effet graphique (changement de couleur, rebond, bordures… comme vous le sentez mais n’y passez pas une heure)

#### Pour frimer beaucoup

- Utiliser switch case quelque part  (m’indiquer où c’est dans votre README dans le code)
- Toutes les variables et toutes les méthodes sont commentées selon la norme jsdoc.
- En bas du pong afficher des commentaires aléatoires en fonction de ce qui se passe dans le jeu (Bien joué, pas mal, dommage, perdu, super, bravo…)
- Quand il reste 3 vies, faire apparaitre un coeur au centre du terrain. Si ce coeur est touché alors il disparait et la joueuse gagne une vie.

