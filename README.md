# DN11_Test
Test pour Dontnod11


# Objectif du Projet

Dans cette présentation je vais expliquer ma démarche, c'est à dire ce que je veux rendre à la fin de la journée. Il est donc possible que la qualité final du projet ne reflète pas mes intentions présentés ici. De plus, il est conseillé de jouer avant de lire car je vais expliquer chaque éléments de gameplay que je souhaite intégré ainsi que les objectifs, challenges et rewards pour le joueur.

# Narration / Univers

(Attention, lire ce paragraphe gâchera votre expérience de jeu si vous le lisez avant de joueur). Je souhaite m'inspirer des univers narratif de Tim Schafer et autres jeux Lucas Art basé sur l'humour et l'absurde. Je veux réussir à implémenter toute sorte d'objet loufoque dans la maison de la grand mère. De plus je souhaite lié mon gameplay avec ma narration que voici : 
Le Chaperon entre chez sa mère grand et entend un bruit étrange dans le lit. En s'approchant le chaperon y distingue une forme animal et poilus, un loup. Une discussion s'engage alors entre le Chaperon et le "loup/mère-grand" avec la célèbre tirade "que vous avez de grands yeux, etc...". Le Chaperon ne voudra pas s'approcher du lit de peur de se faire manger. Le "loup/mère-grand" ne bougera pas du lit et demandera au Chaperon de s'approcher régulièrement. Le Chaperon ouvrira alors l'armoire de la mère-grand et y trouvera plusieurs [kigurumi](https://www.kigurumi-france.com/13-deguisement-animaux) (pyjamas intégrals) ainsi qu'une étagère de l'armoire posé dans celle-ci. Le Chaperon ira alors utiliser la planche pour retourner le "loup/mère-grand" sur le dos. Le Chaperon appercevera alors une fermeture éclaire, tirera dessus et libérera la grand mère de son kigurumi dont elle n'arrivais pas à attraper la fermeture.

# Gameplay / intéractions

En reprenant la narration, je vais avoir besoin de :
- Intéraction Action avec l'armoire
- Intéraction Prendre planche
- Intéraction Observer kigurumi
- Intéraction Poser planche
- Intéraction Action avec la fermeture éclair
- Animation de la porte de l'armoire
- Animation de la grand mère qui se retourne
- Dialogue sans choix au démarrage de la scène
- Observation sur plusieurs objets dans la maison (optionnel)
- Cinématique pendant le dialogue du début (optionnel)
- Intéraction Automatique quand on s'approche de la grand mère ("oh non je ne veux pas me faire manger") (optionnel)
- Mini système d'inventaire pour choisir la planche pour l'utiliser (optionnel)
- Ajout d'une clef pour ouvrir l'armoire (optionnel)

Pour ce qui est des 3C :
- Controle du Third Person Controller de base de UE4
- Ajout d'un système Point & Click pour les intéractions
- Affichage du nom d'un élément de décors quand pointé par la souris
- Clavier (ZQSD / Flèches) pour se déplacer
- Clic gauche pour intéragir avec une intéraction
- Clic droit pour bouger la caméra (optionnel ?)
- Clic milieu pour rencentrer la cam (optionnel ?)
- Le personnage peux seulement se déplacer
- La Camera sera la caméra de base du TPC de UE4

# Technique

J'ai fait un github pour que vous puissiez voir chacun des commit qui explique du coup ce que chacun de mes blueprints font . De plus cela vous permet de vérifier le temps que j'ai mis pour chacune des features. J'utilise UE 4.16.
Je vais faire seulement des formes géométrique simple. Les seuls assets "graphique" seraont deux textures 2D pour le pointeur de souris ainsi que le personnage du projet TPC. Tous les décors seront en Geometry ou en Basic et le fait d'ajouter un nom aux objets de décors quand on passe la souris dessus suffiront à créer un univers.

Pour bien voir les descriptif de mes commits, je vous ai rajouté deux images si jamais vous n'êtes pas familier avec Github
![Voir les commits](https://github.com/Fangh/DN11_Test/blob/master/Help_Github1.png)
![Lire les commentaires des commits](https://github.com/Fangh/DN11_Test/blob/master/Help_Github2.png)
