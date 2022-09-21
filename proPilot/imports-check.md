---
icon: tools
date: 2022-09-20
tags:
  - proPilot
  - tuto
categories:
  - proPilot
---

#  Importer des données quantitatives

Guide de l'import de données sur proPilot 2/2
(_Temps de lecture : 2 min_)
*  Vérifier la mise à jour d'une série de données de votre indicateur ou de votre réforme 
*  Connaître la liste d'erreurs à ne pas commettre


### Périmètre de la mise à jour

Assurez-vous d'avoir d'abord suivi la procédure décrite ici : [Réaliser un import massif - pas à pas](/fr/article/realiser-un-import-massif-pas-a-pas-rdr738/)

_Nous traiterons ici des imports massifs de type Financials -indicateurs-, afin de vous assurer que vous avez_ :

* Mis à jour des valeurs actuelles sur plusieurs mois
* Mis à jour des valeurs actuelles pour plusieurs départements à la fois
* Mis à jour des valeurs actuelles ou des valeurs cibles sur l'ensemble des départements pour une réforme

### Check-list : 

* Utiliser strictement le template fourni par l'outil proPilot pour réaliser cet import et respecter l'ordre des colonnes : 

![structure des colonnes du fichier d'import](https://storage.crisp.chat/users/helpdesk/website/1142b705eb802000/templateimportsfaqpng_1jhpg8r.png)

Par exemple ici pour un template permettant de mettre à jour des valeurs par département. Il faut conserver l'ordre des colonnes : 
- Département Name : le nom du département ET l'intitulé de la réforme 
`Ain / Déployer le pass Culture`	
- Département Code : toujours sous la forme d'un trigramme, un code de trois lettres qui identifie la réforme ET le n° du département
`DPC-D01`
- Effect : l'intitulé de l'indicateur
- Type : Valeur Cible ou Valeur Actuelle

* Sur ce template, ne pas écraser ou modifier les mentions de la première ligne d'en-tête. Exemple, ne pas aller dans la cellule E1 « Jan 2017 » car alors le format est reconnnu comme une date et transformé en « jan-17 ». 
* Il faut réimporter les valeurs existantes que l'on ne souhaite pas changer, l'outil proPilot écrase par défaut les valeurs qui ne sont pas réimportées par un import massif

!!!danger Attention
Au moment de réaliser l'import : faire attention à **ne pas utiliser un fichier Excel avec des formules** dans les cellules, (proPilot ne gère pas les formules).
!!!

* Au cours des copier-coller entre les fichiers source et les fichiers d’import, il faut **être vigilant à ne pas « écraser » certains formats préremplis dans le template** :
- ne pas écraser les listes déroulantes : colonnes Effect et Type sur les templates Financials et colonne Météo sur les templates météo

![Ne pas effacer la liste déroulante "Effect"](https://storage.crisp.chat/users/helpdesk/website/1142b705eb802000/image_ut0d71.png)


![Attention à la liste déroulante sous la colonne "cible"](https://storage.crisp.chat/users/helpdesk/website/1142b705eb802000/image_1gvxwul.png)
