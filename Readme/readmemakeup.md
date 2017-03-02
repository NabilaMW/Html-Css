### *Etape 01 - Réception du Mocku*p

Lors de la réception du mockup, on commence par __*identifier la future structure Html*__ qui va accueillir notre code;

* __Header__ → titre

* __Section__ → paragraphe de présentation + photo

* __Section__ → gallerie avec 3 images.

### *Etape 02 - mise en place du Html*

*On commence par:*
1. créer la structure de dossier qui va accueillir nos fichier.

    *Dossier de travail → Biographie*

    *dossier img → accueillir les fichiers images.*

    *fichier index.html → fichier de base qui va être chargé par votre navigateur comme étant l'écran d’accueil.*

+ Dans Atom,

  a.  Ouvrir le fichier index.html puis taper __html + tab ( tabulation )__
__la structure principale de l’index s'écrit automatiquement.__

  b. Mettre un titre dans la balise `<title>`

  c. Définir les sections comme ce qui à été définis à la réception du mockup
  ```html  
<header>
<section>
<section>
```

d. Remplir les bloques / sections avec les éléments html qui doivent être affiché à cet endroit. On met en place tous les éléments en Html avant de passer au style

img / p / div….
La structure peut-être amené à évoluer au fur et à mesure de votre travail et de vos besoins.

### *Etape 03 - mise en place du Style*

Créer une balise __style__ au début du __body__, au dessus du __header__.

Nous allons utiliser un système de __class et d’ID__
Les class vont nous *permettre de dupliquer du style d’un élément à un autre*

__Les ID :__ nous permettent d’identifier précisément un élément.
L’ID *est unique* et ne peut apparaître qu’une seul fois dans le document.

### *Bilan*

- En portant une réflexion sur le mockup, __vous devez connaître le nombre de class dont vous aurez besoin__.

- On travail sur les grands ensemble :
Reperer les elements qui ont un visuel ou des comportement similaires.

- Toujours travailler du général au particulier.
Structure général > section / section > ensembles par sections (titres, img...) > Élément dans le détail ( si besoin )
