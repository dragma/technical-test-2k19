# Le jeu du bouche à oreille

## Sujet

Votre mission, si vous l'acceptez, sera de se marrer un bon coup en manipulant les API [text to speech](https://www.ibm.com/watson/services/text-to-speech/) et [speech to text](https://www.ibm.com/watson/services/speech-to-text/) d'IBM.
Vous allez devoir éprouver ces services en recréant le jeu du bouche à oreille, en mixant les langues. 
Il y a des chances qu'on observe de belles choses ! :D

### Déroulement d'une partie

- Au début de la partie un nombre de tour est décidé par l'utilisateur.
- L'utilisateur écrit ensuite une phrase / paragraphe de la taille de son choix, et determine la langue du texte.
- Le tour est composé :
  - D'un [text to speech](https://www.ibm.com/watson/services/text-to-speech/) dans une langue différente de la langue du texte.
  - Puis d'un [speech to text](https://www.ibm.com/watson/services/speech-to-text/) dans la langue du texte
- À chaque tour, le texte généré ainsi qu'une note comparative (sur l'échelle de votre choix, avec l'algorithme de votre choix) par rapport au texte précédent doit être sauvegardé sur un serveur distant (db, fichier plat, jpg, comme vous voulez :))
- En fin de partie, un récapitulatif des tours devra être affiché, ainsi que la note globale.

## Consignes

### Variantes sur la règle du jeu

Vous devrez tout faire pour que ces services se comprennent le moins possible si jamais les résultats sont trop parfaits (parce que sinon ça sera pas marrant ! **=]** ).

### Technos

Les technologies à utiliser sont (évidemment)  a minima :

- `react-native`
- `nodejs`

Libre à vous ensuite d'utiliser la manière que vous voulez pour stocker les état et résultats.

L'aspect graphique n'est pas très important. Cela dit, si vous avez des envies créatrices, ne vous privez pas :D !

La performance et l'optimisation est un plus pas (du tout) obligatoire. Le but est que je puisse voir comment vous codez / commitez sur un thème, qui, je l'espère, sera aussi décalé que sympathique.

L'exercice sera à me remettre sur un repo github ou gitlab au choix !

### API

Le pricing de cette API autorise une utilisation gratuite [jusqu'à 500 minutes par mois](https://www.ibm.com/cloud/watson-speech-to-text/pricing). Il faut simplement se créer un compte.

[Documentation text-to-speach](https://cloud.ibm.com/apidocs/text-to-speech?code=node)
[Documentation speech-to-text](https://cloud.ibm.com/apidocs/speech-to-text?code=node)

---

Bon courage !

[![Bon chance](https://img.youtube.com/vi/7OGpsoJ1kwk/0.jpg)](https://www.youtube.com/watch?v=7OGpsoJ1kwk)

