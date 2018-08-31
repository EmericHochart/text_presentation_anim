Cr�ez un texte de pr�sentation anim� pour n'importe quel site
Utilisez CSS et Javascript pour accueillir vos visiteurs avec un titre anim� s�duisant.

1. D�but du document HTML
Commencez le projet par le document HTML.
D�finissez le contenur du document HTML ainsi que ses parties enfant et body int�rieures.
Stockez dans la partie HEAD les r�f�rences vers les fichiers CSS et Javascript externes.
Stockez dans la partie BODY le contenu visible � l'�cran.

2. Contenu HTML
Utilisez un conteneur de texte dont la classe est "opening".

3. Javascript
Cr�ez un fichier code.js.
Le javascript sert � ce que le CSS puisse avoir d'avantage de contr�le sans que l'on ait � complexifier l'HTML.
On remplacera le texte des �l�ments conteneur dont la classe est "opening" afin qu'il se trouve antre des balises span
L'objectif est ici de permettre � CSS de g�rer la pr�sentation des mots de mani�re ind�pendante.

4. D�but du CSS
Cr�er un fichier styles.css.
Le document et le corps de la page ont un arri�re plan noir.
On �vite un conflit potentiel avec la couleur par d�faut du texte, lui aussi noir,en donnant � ce dernier la couleur blanche.

5. Mots d'ouverture
Gr�ce � l'�tape 3, chaque texte � l'int�rieur de conteneur "opening" se trouve maintenant dans un �l�ment span.
Dans cette �tape chaque mot devient invisible par d�faut avec une marge sur sa droite.
Nous appliquons de plus deux animations.

6. D�calage de l'animation
Pour cet effet, il faut que chaque texte se trouvant dans le conteneur opening commence � un moment diff�rent.
Pour cela, nous utilisons l'attribut "animation-delay" ainsi que le s�lecteur "nth-child"
Dans notre exemple (index.html), nous pr�cisons des d�calages pour chaque span �tant un quatri�me enfant, ainsi que pour les 3 �l�ments enfants se trouvant entre elles.

7. D�finitions d'animation
Nous avons besoin de 2 animations de la cinqui�me �tape.
L'animation "animateOpen" rend le mot compl�tement invisible, 
tandis que l'animation "flash" utilise une ombre blanche qui doit s'afficher d'un coup autour du texte en trai nde dispara�tre.

Ressources: Webdesign N�88

