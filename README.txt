Créez un texte de présentation animé pour n'importe quel site
Utilisez CSS et Javascript pour accueillir vos visiteurs avec un titre animé séduisant.

1. Début du document HTML
Commencez le projet par le document HTML.
Définissez le conteneur du document HTML ainsi que ses parties enfants et body intérieures.
Stockez dans la partie HEAD les réfèrences vers les fichiers CSS et Javascript externes.
Stockez dans la partie BODY le contenu visible à l'écran.

2. Contenu HTML
Utilisez un conteneur de texte dont la classe est "opening".

3. Javascript
Créez un fichier code.js.
Le javascript sert à ce que le CSS puisse avoir d'avantage de contrôle sans que l'on ait à complexifier l'HTML.
On remplacera le texte des élèments conteneur dont la classe est "opening" afin qu'il se trouve entre des balises span
L'objectif est ici de permettre à CSS de gérer la présentation des mots de manière indépendante.

4. Début du CSS
Créer un fichier styles.css.
Le document et le corps de la page ont un arrière plan noir.
On évite un conflit potentiel avec la couleur par défaut du texte, lui aussi noir,en donnant à ce dernier la couleur blanche.

5. Mots d'ouverture
Grâce à l'étape 3, chaque texte à l'intérieur du conteneur "opening" se trouve maintenant dans un élément span.
Dans cette étape chaque mot devient invisible par défaut avec une marge sur sa droite.
Nous appliquons de plus deux animations.

6. Décalage de l'animation
Pour cet effet, il faut que chaque texte se trouvant dans le conteneur opening commence à un moment différent.
Pour cela, nous utilisons l'attribut "animation-delay" ainsi que le sélecteur "nth-child"
Dans notre exemple (index.html), nous précisons des décalages pour chaque span étant un quatrième enfant, ainsi que pour les 3 éléments enfants se trouvant entre elles.

7. Définitions d'animation
Nous avons besoin de 2 animations de la cinquième étape.
L'animation "animateOpen" rend le mot complètement invisible, 
tandis que l'animation "flash" utilise une ombre blanche qui doit s'afficher d'un coup autour du texte en train de disparaître.

Ressources: Webdesign N°88

