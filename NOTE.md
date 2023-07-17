<h1>Modélisation de donnée</h1>

## 1. Initialisation de git avec VS code

la commande :
``` sh
git init
```
nous permet de créer un depot git dans le dossier dans lequel ont travail

la commande :
``` sh
git status
```
nou permet de verifier que l'on a bien sauvegarder

Pour ajouter des fichiers non suivis :
```` bash
git add .
````

pour sauvegarder le travail commande :
``` bash
git commit -m "votre message de commit"
```

## 2. MERISE

Merise est une methde de modélisation de données. elle permet de représenter les données d'un systeme d'information.

Mersie est acronyme de : Méthode d'Etude et de Réalisatuion Informatique pour les systemes d'Entreprise.

Présentation Général
Cette methiode se caractérise par trois point clés:
- une approche dite systemique : on transforme les processus de l'entreprise en systelme d'information
- une séparation des donnnées et des traitements
- une approche nivelée

### 2.1 L'approche systemique

![Alt texte]()

Systeme de pilotage : 

- Il compose de l'ensemble des acteurs qui vont **piloter** le systeme d'information

systeme d'information :

- Il est composé de l'ensemble des acteurs qui vont **utiliser** le systeme d'information

le systeme operant :

- Il est compose de l'ensemble des acteurs qui vont **produire** les données su systeme d'information

### 2.2 La séparation des données et de traitements

La séparation des données et des traitementspermet de séparer les données du systeme d'informations et mles traitements effectués sur ces données.
Cette démarche se fait en 3 étapes :
- L'analyse des flux : on analyse les flux d'informations entre les acteurs du systeme d'information et les acteurs du systeme operant
- L'etude des documents interne (factures,bon de livraison,)
- M'etude des documents en externes (fournisseur, clients,)

Les differents types de d'informations:

- les infos de bases ou elementaire : ce sont les données de base du systeme d'information
- les informations calculées : ce sont les données calculées a partir des données de base
- les traitements ou les fonctions : ce sont les traitements effectués sur les donées de base pour obtenir les données calculées

En resume : vous devrez identifiiéses les données et les traitements effectués sur ces données.

### 2.3 L'approche nivelée

Pour effectuer la conception d'un SI, on va utiliser une approche nivelée. Cette approchze se compose de 4 niveaux :
- Le niveau conceptuel 
- Le niveau organisationnel
- Le niveau logique 
- Le niveau physique

### 2.4 Le niveau conceptuel

Le niveau conceptuel permet de modéliser les données de l'entreprise, 
On va utiliser le conceptuel de données (MCD) pour modéliser les données de l'entreprise, et le MTC pour modéliser les traitements effectués sur ces données.

### 2.5 Le niveau organisationnel

Le niveau organisationnel va permattre d'intergrer a l'analyse précédente toutes les notions de temporalite , de chronologie des operation s, de contraintes geographiques. On va utiliser le modele organisationnel deds traitements (MOT) et le modele organisationnel des données (MOD) pour modéliser les traitements de l'entreprise.

En résume on se pose les questionq suivantes a partire des données recuillies au niveau conceptuel :
- **Quand** les traitement sont-ils effectués ?
- **Où** les traitements sont-ils effectués ?
- Par **qui** les traitements sont-ils effectués ?

### 2.6 Le niveau logique

le niveau 