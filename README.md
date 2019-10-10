# Diaporama-Poo-Responsif
tutoriel pour un slider Poo simple et responsif

** Fichier HTML **
- lien <script> pour Jquery
- lien <link> FontAwesome => https://fontawesome.com/
- Créer une section à l'emplacement où vous souhaitez créer votre slider (ici #slide)
- Créer l'id correspondant à votre slider (id="diap1") dans la balise de votre choix (ici <img>)
- Ecrivez vos flèches d'action dans une div (en identifiant chacune d'entre elle par un id)

** Fichier CSS **
- Supprimer les margin et padding éventuel sur votre emplacement de slider (ici #slide)
- Déterminer la taille de votre slider ( width 100% + height 100vh on fullwidth responsive)
- Positionner vos flèches d'action ( position: absolute + float: left/right + top: 50%...)

** Fichier JS **
- Créer un objet et déterminer ses caractéristiques avec le constructor (ici class slider )
- Créer la fonction d'animation (ici launchSlider() )
- Détailler les fonctions Next() et Prev()
- Initialiser le tableau comprenant vos images ( let slideImages_1 = ['slider1', 'slider2'...] )
- Initialiser votre nouvel objet et ses caractériqtiques propres (id cible, tableau d'images, répertoire, durée)
- Activer les fonctions Prev() et Next() au clic ou flèche du clavier

** Voilà, vous avez créer un slider Javascript orienté object, simple, réutilisable et totalement responsif**
---------------------------------------------------------------------------------------------------------------------

//English version//

#Responsive Slideshow POO
tutorial for a simple and responsive POO Slideshow

** HTML File **
- Link <script> for Jquery
- Link <link> FontAwesome => https://fontawesome.com/
- Create section where you want create your slider (here #slide)
- Create the id corresponding to your slider (id="diap1") in the tag of your choice (here <img>)
- Write your action arrows in a div (identifying each onewith an id)

** CSS File **
- Remove any margin and padding on your slider location (here #slide)
- Determine the size of your slider (width 100% and height 100vh for fullwidth and responsive)
- Position your action arrows (position: absolute + float: left/right + top: 50%...)

** JS File **
- Create an object and determine its characteristics with constructor (here class slider)
- Create animation function (here launchSlider() )
- Detail the Next() and Prev() functions
- Initialize the array including your pictures ( let slideImages_1 = ['slider1', 'slider2'...] )
- Initialize your new object and its own characteristics ( target id, pictures array, directory, duration)
- Activate Prev() and Next() function at click or press keyboard

** That's it, you've created and object-oriented, simple, reusable and fully responsive Javascript slideshow **
