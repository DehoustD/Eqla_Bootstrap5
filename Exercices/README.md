# Exercices sur Bootstrap

Pour les exercices, je vous demanderai de faire vos Exercices dans le dépôt que nous avons créé EqlaExercices. Il se trouve soit dans le répertoire "Mes Documents" ou "Mes dépôts". Peut-être l'avez-vous mis ailleurs.

A chaque fin de cours ou exercice terminé, faites un git push. (Évidemment n'oubliez pas le git add et le git commit bien entendu...)

Comme ça, je verrai comment vous progressez.

Dans le dépôt EqlaExercices, il y a un répertoire nommé Bootstrap. Vous y mettrez les différents exercices.

Chaque exercice sera nommé par exemple Exercice1.html, Exercice2.html, etc.

## Exercice n°1 - Intégration des fichiers Bootstrap: css et js
### Partie 1 - Création du fichier Exercice1.html
Créez un fichier nommé Exercice1.html dans le répertoire EqlaExercices\Bootstrap.  
Créez ce fichier html comme vous l'avez vu avec Serge.

### Partie 2 - Ajout d'un titre
Mettez comme titre: Exercice1

### Partie 3 - Ajout du doctype
N'oubliez pas que pour Bootstrap il faut absolument de l'html5. Pour cela, vous devez mettre en toute première ligne de votre fichier html ceci: [<!doctype html>](https://developer.mozilla.org/fr/docs/Glossary/Doctype "Qu'est-ce que le doctype sur Mozilla ?")

### Partie 4 - Ajout du fichier css de Bootstrap

Dans la balise [\<head>](https://developer.mozilla.org/fr/docs/Web/HTML/Element/head "Element head sur Mozilla"), ajoutez le fichier suivant:
- [bootstrap.min.css](Files/bootstrap.min.css?raw=1) (Il faut donc le télécharger et le mettre dans le répertoire de vos exercices)

Pour rappel, utilisez la balise [\<link>](https://developer.mozilla.org/fr/docs/Web/HTML/Element/link "Element link sur Mozilla") avec les bons attributs.

### Partie 5 - Ajout du fichier js de Bootstrap

Juste avant la fermeture de la balise [\<body>](https://developer.mozilla.org/fr/docs/Web/HTML/Element/body "Element body sur Mozilla"), ajoutez le fichier suivant:
- [bootstrap.bundle.min.js](Files/bootstrap.bundle.min.js?raw=1) (Il faut donc le télécharger et le mettre dans le répertoire de vos exercices)

Pour rappel, utilisez la balise [\<script>](https://developer.mozilla.org/fr/docs/Web/HTML/Element/script#exemples "Element script sur Mozilla") avec les bons attributs.

### Partie 6 - Ajout des tag meta nécessaires
Dans la balise head, ajoutez les tags [\<meta>](https://developer.mozilla.org/fr/docs/Web/HTML/Element/meta "Element meta sur Mozilla") suivants:
```html
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
```

### Partie 7 - Ajout d'un titre 1
Mettez le texte suivant en titre1: Hello World from Exercice 1 !

### Partie 8 - Envoi sur GitHub
Si cela vous semble bon, dans un terminal envoyez vos modifications sur GitHub.