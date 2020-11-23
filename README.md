# Pydiderot
Apprendre et enseigner python

## A propos
Le projet Pydiderot fournit et documente des outils pour l'enseignement et l'apprentissage de l'algorithmique dans le secondaire.

Il est organisé en 3 volets:
- Un environement de dévellopement [PydiderotIDE](https://github.com/Pydiderot/pydiderotIDE)
- Des bibliothèques [Pydiderotlibs](https://pydiderotlibs.readthedocs.io/)
- Des documents ressources pour les professeurs [Pydago](https://github.com/Pydiderot/pydago)

Toutes les productions sont sous licences libre MIT. C'est un travail collaboratif dont les discussions et choix sont publics. 

## Genèse

Ce projet a été initié en 2018 par des enseignant du lycée Denis Diderot en se basant sur les constats suivant:
    - Les professeurs de mathématiques doivent enseigner l'algorithmique. 
    - Il n'éxiste pas d'outil satisfaisant pour effecture cet apprentissage confortablement.
    - De nombreux collègues dévouvrent l'algorithmique.
    
A L'époque, notre choix c'est porté sur le langage Python ce qui a été confirmé par les nouveaux programmes de 2019.

## Pydiderot IDE

La première étape a été de choisir un environnement de dévellopement qui réponde au critères suivants:
- Logiciel libre
- Interface particulièrement simple pour ne pas perdre les élèves et les professeurs néophytes.
- Logiciel multiplateforme facilement installable de différentes manières sous de multiples systèmes d'exploitations et matériels.
- Logiciel activement maintenu, extensible, fournissant une documentation de qualité.
    
Notre choix c'est porté sur l'IDE Thonny car il répondait parfaitement au cahier des charges ci-dessus.
    
Nous avons donc déployé Thonny au lycée et fournissons depuis une version portable correspondante pour que les élèves puisse facilement s'entrainer à la maison.
    
Nous avons en avril 2019 mis en place la traduction du logiciel Thonny (voir [issue](https://github.com/thonny/thonny/issues/668) et [PR](https://github.com/thonny/thonny/pull/736)) qui est depuis traduit dans une vingtaine de langues dont le francais.
    

## Pydiderotlibs
Il nous a paru ensuite nécessaire de construire des librairies permettant de cacher des difficultés liées au langage de programmation afin de pouvoir cibler certains points pédagogiques.

Par exemple, la librairie entrée permet de s'affranchir des difficultés liés aux problèmes de typage sur des entrés utilisateurs. On peut également citer la librairie repère permettant de construire un traceur de courbe aussi simplement que:
 
```python3 
creer_fenetre()
x = -10
while x < 10:
  point(x, x*x)
  x  = x + 0.1
```

Nous invitons le lecteur curieux à parcourir la documentation de [Pydiderotlibs](https://pydiderotlibs.readthedocs.io/) afin de découvrir les bibliothèques proposées en détail.

Ces bibliothèques sont installés au lycée au présentes dans l'environement PydiderotIDE.

## Pydago

Afin de former nos collègues, nous avons créé des documents supports de formations.
Ces documents sont accessibles publiquement sur [Pydago](https://pydago.readthedocs.io/). C'est une base de travail que ne demande qu'a être enrichie.

## Participez

Comme annoncé, ce projet est un travail collaboratif initié par des enseignants du lycée Diderot à Marseille. Nous serions ravis de travailler avec vous et toute aide est la bienvenue.
Si vous pensez participer nous vous en remercions et fournissons ce [guide](CONTRIBUTING.md) pour vous aider.


