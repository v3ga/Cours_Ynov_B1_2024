# Cours design interactif B1 Ynov Bordeaux
*du 28 mars au 14 mai 2024*

#### Sketches en ligne
✍️ https://editor.p5js.org/v3ga/collections/hjK0S1GZf

#### Google Sheets pour les rendus
✍️ [https://docs.google.com/spreadsheets/d/14U-QiGUbMP2MJb4XGEI7uMfeGapXhsIvKfrTAt0r4-s/](https://docs.google.com/spreadsheets/d/14U-QiGUbMP2MJb4XGEI7uMfeGapXhsIvKfrTAt0r4-s/edit?usp=sharing)

#### Visualisation de l'exécution d'un programme p5.js
:male_detective: https://v3ga.net/p5LearnableProgramming/index_U2_L2_lines.php<br />
C'est un projet expérimental pour montrer l'exécution pas à pas d'un programme sur quelques commandes de dessin. Utilisez la liste pour accéder aux différents exemples.

## Objectifs pédagogiques
* découverte de l'histoire de l'art génératif et plus largement du design génératif, évolutions des années 60 à nous jours.
* découverte de la programmation interactive temps réel, productions de visuels animés réagissant à des stimuli : mouvement(s), voix, ... 
* apprendre et maîtriser les concepts fondamentaux de la programmation : variables, boucles, branchements, fonctions. 
* apprendre à développer ses propres outils de création, création d'interface (UI) pour configurer et explorer les potentialités d'algorithmes de créations de formes graphiques.
* insérer ses productions de formes dans un workflow plus général : print, site web, installations interactives.

### Déroulé d'un cours  
Le cours sera consacré au deux tiers à l'étude théorique de concepts de programmation créative avec des références graphiques artistiques et l'autre tiers à la pratique par la réalisation d'un exercice « à chaud » utilisant les notions vues.

### Barême pour les exercices
Pour les exercices que je vous donne, le barême est le suivant (sur 10)
* **rendu en temps et en heure** :point_right: 1 point.
* **respect de la consigne** :point_right: 3 points. 
Le sketch doit être sauvegardé sur votre compte en ligne, l'addresse (URL) doit être insérée dans la colonne correspondante dans [le document Google Sheet](https://docs.google.com/spreadsheets/d/14U-QiGUbMP2MJb4XGEI7uMfeGapXhsIvKfrTAt0r4-s/). 
* **créativité** :point_right: 6 points. 
J'entends par créativité une recherche graphique personelle et/ou interactive qui peut se faire à partir de sketches vus en classe ou de références que vous trouvez en ligne.

## Cours 01
*Jeudi 28 mars 2024*

### Introduction
* Présentation du travail de Julien Gachadoat.
* Présentation de l'environnement [Processing](http://www.processing.org) et de son « écosystème » (notamment [p5.js](https://p5js.org/))
* Présentation de l'environnement de développement et premières commandes de dessin dans l'éditeur en ligne [editor.p5js.org/](https://editor.p5js.org/) 

### Dessiner avec du code 
* repère de dessin, espace de dessin [p5js / createCanvas](https://p5js.org/reference/#/p5/createCanvas)
* dessin de formes géométriques : [point](https://processing.org/reference/point_.html), [line](https://p5js.org/reference/#/p5/line), [ellipse](https://p5js.org/reference/#/p5/ellipse), [rect](https://p5js.org/reference/#/p5/rect).
* dessin de formes géométriques « composées » : [beginShape](https://p5js.org/reference/#/p5/beginShape) / [vertex](https://p5js.org/reference/#/p5/vertex) / [endShape](https://p5js.org/reference/#/p5/endShape)
* gestion des couleurs ([color](https://p5js.org/reference/#/p5/color)) et des options de dessin([stroke](https://p5js.org/reference/#/p5/stroke), [noStroke](https://p5js.org/reference/#/p5/noStroke), [fill](https://p5js.org/reference/#/p5/fill), [noFill](https://p5js.org/reference/#/p5/noFill), [strokeWeight](https://p5js.org/reference/#/p5/strokeWeight))
* exporter / faire une capture d'écran avec la fonction [p5js / save](https://p5js.org/reference/#/p5/save)

### Références
* [A Modern Prometheus — The history of Processing by C.Reas & B.Fry](https://medium.com/processing-foundation/a-modern-prometheus-59aed94abe85)
* [Welcome to Processing](https://vimeo.com/140600280), vidéo en anglais par [Dan Shiffman](http://shiffman.net/) pour [la fondation Processing](https://processingfoundation.org/).
* [Design by Numbers](https://dbn.media.mit.edu/) de [John Maeda](https://maedastudio.com/)
* [Ben Fry](https://www.benfry.com/) and [Casey Reas](http://reas.com/)
* [Rune Madsen / Computational color](http://printingcode.runemadsen.com/lecture-color/)
* [Daniel Shiffman / The Coding Train](https://www.youtube.com/channel/UCvjgXvBlbQiydffZU7m1_aw)

#### Exercice
Choisir une des œuvres [« Homages to the square »](https://www.google.fr/search?q=Josef+albers+square&sxsrf=AJOqlzXDonDyiy1zWyFfiJG2-z_exlfBGA:1677769320061&source=lnms&tbm=isch&sa=X&ved=2ahUKEwj0_tjiwb39AhWwVaQEHe5MD3wQ_AUoAXoECAEQAw&biw=1298&bih=898&dpr=1) de Josef Albers pour le récréer avec du code.

<img src="https://raw.githubusercontent.com/v3ga/Cours_Ynov_B1_2023/main/cours01_hommage_square.png" height="250" />

## Cours 02
*Jeudi 11 avril 2024*

### Dessiner avec du code (bis)
* retour sur les notions vus au cours 01 avec le dessin d'un visage de Bruno Munari. Nous introduirons à ce sujet la notion de **variable** que nous reverrons dans le cours 03.

Bruno Munari est un artiste plasticien italien. Peintre, sculpteur, dessinateur, designer, il est également auteur et illustrateur de livres pour enfants (source : [wikipedia](https://fr.wikipedia.org/wiki/Bruno_Munari))

<img src="https://raw.githubusercontent.com/v3ga/Cours_Ynov_B1_2023/main/cours02_visage_munari.png" height="250" /><img src="https://raw.githubusercontent.com/v3ga/Cours_Ynov_B1_2023/main/Design_as_art_cover-1.jpg" height="250" />
<img src="images/Munari_visages.jpg" />

### Animer
* Animer : 
  * avec une fonction génératrice de nombre aléatoires : [random](https://p5js.org/reference/#/p5/random)  
  * avec la variable de temps [frameCount](https://p5js.org/reference/#/p5/frameCount) et la fonction [millis()](https://p5js.org/reference/#/p5/millis)
  * avec les variables [mouseX](https://p5js.org/reference/#/p5/mouseX) et [mouseY](https://p5js.org/reference/#/p5/mouseY) pour capter la position de la souris dans le canvas.

<img src="images/montagnes.jpg" height="250" /><img src="images/composition_aleatoire.jpg" height="250" /><img src="images/arcs.jpg" height="250" /><img src="images/munari_facia.jpg" height="250" />

#### Exercice à rendre pour le jeudi 18 avril 2024
Créez un visage dans le style de Bruno Munari en utilisant des formes géométriques.
Ajouter un élément d’interactivité en utilisant [la position de la souris](https://p5js.org/reference/#/p5/mouseX) ou la fonction [random](https://p5js.org/reference/#/p5/random). Le visage se dessinera sur un canvas de dimensions (500,500) pixels, les couleurs à utiliser sont le noir et le blanc uniquement.

##### Références
* [Page de créations sur Domestika](https://www.domestika.org/fr/courses/4034-initiation-au-code-creatif-generez-des-objets-graphiques/community/forum/topics/210634-creez-votre-propre-visage-dans-le-style-de-bruno-munari)
