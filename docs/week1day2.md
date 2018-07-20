---
id: week1day2
title: Week1Day2
sidebar_label: Week1Day2
---

# Week1Day2

## C'est quoi l'HTML

L'HTML est un langage informatique utilisé sur l'internet. Ce langage est utilisé pour créer des pages web. L'acronyme signifie HyperText Markup Language, ce qui signifie en français "langage de balisage d'hypertexte". Cette signification porte bien son nom puisqu'effectivement ce langage permet de réaliser de l'hypertexte à base d'une structure de balisage.

Ce n'est pas à proprement parlé un langage de programmation, mais plutôt un langage qui permet de mettre en forme du contenu. Les balises permettent de mettre en forme le texte et de placer des éléments interactif, tel des liens, des images ou bien encore des animations. Ces éléments ne sont pas dans le code source d'une page codé en HTML mais "à coté" et la page en HTML ne fait que reprendre ces éléments.
Pour visualiser une page en HTML il est nécessaire d'utiliser un navigateur web.

La plupart du temps d'autres langages informatique sont associé à une page codé en HTML. Par exemple le CSS, qui permet de mettre en forme le contenu d'une page codé en HTML. Il y a également des langage informatique qui dépendent entièrement du HTML, tel le Javascript.

## Les Balises

Il ne suffit pas d'écrire « simplement » du texte dans l'éditeur, il faut aussi donner des instructions à l'ordinateur. En HTML, on utilise pour cela des balises.

Les pages HTML sont remplies de ce qu'on appelle des balises. Celles-ci sont invisibles à l'écran pour vos visiteurs, mais elles permettent à l'ordinateur de comprendre ce qu'il doit afficher.

Les balises se repèrent facilement. Elles sont entourées de « chevrons », c'est-à-dire des symboles ` < ` et ` > ` , comme ceci : ` <balise> `

Elles indiquent la nature du texte qu'elles encadrent. Elles veulent dire par exemple : « Ceci est le titre de la page », « Ceci est une image », « Ceci est un paragraphe de texte », etc.

### Les balises en paires

Elles s'ouvrent, contiennent du texte, et se ferment plus loinElles s'ouvrent, contiennent du texte, et se ferment plus loin

```
    <titre> Titre de la page </titre>
```

On distingue une balise ouvrante ` <titre> ` et une balise fermante ` </titre> ` qui indique que le titre se termine.

### Les balises orphelines

Ce sont des balises qui servent le plus souvent à insérer un élément à un endroit précis (par exemple une image). Il n'est pas nécessaire de délimiter le début et la fin de l'image, on veut juste dire à l'ordinateur « Insère une image ici ».

```
    <image />
```

## Les attributs

Les attributs sont un peu les options des balises. Ils viennent les compléter pour donner des informations supplémentaires. L'attribut se place après le nom de la balise ouvrante et a le plus souvent une valeur, comme ceci :

```
    <balise attribut="valeur">
```

À quoi cela sert-il ? Prenons la balise<image />que nous venons de voir. Seule, elle ne sert pas à grand chose. On pourrait rajouter un attribut qui indique le nom de l'image à afficher :

```
    <image nom="photo.jpg" />
```

## Structure de base

Ici present nous avons la structure de base d'une page HTML:

```
    <!Doctype html>
    <html>
        <head>
            <meta charset='utf-8'>
            <title>
                Ma premiere page web
            </title>
        </head>
        <body>
            <p>
                Hello World!!!
            </p>
        </body>
    </html>
```

## Differente partie d'une structure HTML

### Le doctype

```
    <!DOCTYPE html>
```

La toute première ligne s'appelle le doctype. Elle est indispensable car c'est elle qui indique qu'il s'agit bien d'une page web HTML.
Ce n'est pas vraiment une balise comme les autres (elle commence par un point d'exclamation). Vous pouvez considérer que c'est un peu l'exception qui confirme la règle

### La balise html

```
    <html>

    </html>
```

C'est la balise principale du code. Elle englobe tout le contenu de votre page. Comme vous pouvez le voir, la balise fermante ` </html> `se trouve tout à la fin du code !

### L'entete

```
    <head>

    </head>
```

cette section donne quelques informations générales sur la page comme son titre, l'encodage (pour la gestion des caractères spéciaux), etc. Cette section est généralement assez courte. Les informations que contient l'en-tête ne sont pas affichées sur la page, ce sont simplement des informations générales à destination de l'ordinateur. Elles sont cependant très importantes !



### Le corps

```
    <body>

    </body>
```

c'est là que se trouve la partie principale de la page. Tout ce que nous écrirons ici sera affiché à l'écran. C'est à l'intérieur du corps que nous écrirons la majeure partie de notre code.

### L'encodage

```
    <meta charset='utf-8'>
```

Cette balise indique l'encodage utilisé dans votre fichier .html.

 L'encodage indique la façon dont le fichier est enregistré. C'est lui qui détermine comment les caractères spéciaux vont s'afficher (accents, idéogrammes chinois et japonais, caractères arabes, etc.).


### Le titre

```
    <title> </title>
```

C'est le titre de votre page, probablement l'élément le plus important ! Toute page doit avoir un titre qui décrit ce qu'elle contient.

Il faut savoir que le titre apparaît aussi dans les résultats de recherche, comme sur Google (figure suivante).

### Les commentaires

```
    <!-- Ceci est un commentaire -->
```

Un commentaire en HTML est un texte qui sert simplement de mémo. Il n'est pas affiché, il n'est pas lu par l'ordinateur, cela ne change rien à l'affichage de la page.

## Quelques balises

#### Contributeurs à cette leçon.

Ex:

> Emmanuel Fleuriné <br>
> Sergio Suzerain Osson <br>
> Pierre Valen's Mizaine 

#### Sources

> http://glossaire.infowebmaster.fr/html/
>https://openclassroomscom/fr/courses/1603881-apprenez-a-creer-votre-site-web-avec-html5-et-css3/1604361-votre-premiere-page-web-en-html
