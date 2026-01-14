# Cours Géomatique - L3 Géographie

# Modalités d'examen     
## Contrôle continu + examen terminal 
→ Deux cartes à produire / traitement de données en général    
  
## Barème : 
Contextualisation du traitement des données dans une problématique de recherche 
Cohérence du code et des explications
Clarté du code / commentaires
Lisibilité de la carte
**Les notes seront harmonisées** → Si tout le monde se plante, ce sera probablement plus de ma faute que de la vôtre. 

## Important !
* Si vous utilisez un outil d'intelligence artificielle, je le saurai, et ce n'est pas autorisé. L'intérêt n'est pas du tout que vous deveniez des programmateurs de génie, mais que vous compreniez 1- Ce que vous faites ; 2- Comment vous le faites et 3- Ce que le traitement des données via un outil de programmation peut vous apporter.
* Vous n'avez pas besoin de m'écrire des notebooks extrêmement compliqués. Ce que j'attends et que j'évaluerai principalement, c'est votre aptitude à traiter des données, pas votre compétence en programmation.
* N'hésitez pas à faire des cellules de code entrecoupées de cellules de texte : c'est plus lisible et compréhensible
* Pour vous évaluer, je lancerai l'intégralité de votre code. Si certaines cellules ne fonctionnent pas, je débugguerai si besoin, mais je saurai aussi d'où vient l'erreur, ce qui peut m'amener à considérer que vous n'avez simplement pas fait le travail vous mêmes.


# Installation de Python 

### A ne faire qu'une seule fois !
Récupérer minconda : [Sélectionnez Miniconda](https://www.anaconda.com/download/success)    
Lancer le .exe     
Accepter les conditions     
Sélectionner "Just for me"     
Next     
Sélectionner "Create shortcuts" et "Clear the package cache upon completion     
Install     

Une fois miniconda installé :     
Dans la barre de recherche, taper "Anaconda Prompt", et ouvrir le programme     
Dans l'invite de commandes, taper :     
```
setx CONDA_ENVS_PATH ".\.conda\envs"
```
Entrée.     

Puis     
```
setx CONDA_PKGS_DIR ".\.conda\pkgs"
```
Entrée.     

Enfin, créer un environnement conda :     
```
conda create --prefix .\.conda\envs\Python_TD python=3.10 notebook pip
```
Et appuyer sur entrée     
Acceptez les termes et conditions (```a>Entrée>a>Entrée>a>Entrée```)      
Conda va créer un environnement qui s'appelle "TD_Python" et installer tout ce qu'il faut pour bosser.      

### A refaire à chaque fois !
Activer l'environnement :      
Toujours dans Anaconda Prompt, taper et éxecuter :     
```
conda activate Python_TD
```
Pour lancer un notebook, après avoir activé l'environnement :
```
jupyter notebook
```

# Plan du cours
## Apprentissage des bases de Python et des humanités numériques 
Cours 1 (bases de Python) :    
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Lmarito/Geo_L3/tree/main/HEAD?urlpath=%2Fdoc%2Ftree%2FCours_1.ipynb)

## Applications dans des contextes donnés : OCR, carto, à voir selon vos besoins 
Cours 2 (données ouvertes, cartographie, OCR et analyses textuelles) :     

## On pourra faire des cours dédiés à vos problématiques !
- Idée globale : vous codez, je passe vous voir, et je vous oriente 
*OU*
- Vous m'indiquez des besoins généraux, et je vous produis un cours dessus 




## Public
Géographie - L3

## Volume
18h HETD

## Objectifs
Manipulation et traitement de données via notebooks Jupyter

### Points clés
- Python et algorithmique
- Trouver des données ouvertes 
- OCR ? 
- Import des données 
- Curation des données 
- Enrichissement des données 
- Filtrage des données 
- etc 
