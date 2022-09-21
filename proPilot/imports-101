# Réaliser un import massif - pas à pas

### 1 - Accéder à l’espace d’import massif de données dans l’interface d’administration de proPilot


!!!warning Attention
Cette fonctionnalité est réservée aux administrateurs bénéficiant de droits spécifiques (droits PMO)
!!!

Depuis l’interface utilisateur de proPilot, dans la bannière de gauche, cliquez sur l’onglet « Admin » puis sur l’onglet « Importer ».

![Trouver le module d'admin dans l'interface proPilot](https://storage.crisp.chat/users/helpdesk/website/1142b705eb802000/adminimportpropilot_1pwn97s.png)

Vous arrivez sur la page d'imports massifs de l'administration de proPilot. 


![](https://storage.crisp.chat/users/helpdesk/website/1142b705eb802000/moduledimportpropilotpng_1bwfswf.png)

### 2 - Télécharger le modèle d'import

Chaque périmètre ministériel a une structure bien spécifique. Ils ont ainsi chacun leur modèle de données distinct, qu’il convient de télécharger.
* Chaque fichier dispose d’une clef de sécurité empêchant de charger le fichier généré pour un périmètre dans un autre
* Le chargement par import massif se réalise par niveau : **périmètre ministériel** puis **maille géographique** (région ou département)

Dans la partie supérieure de cette page, vous pouvez télécharger les fichiers d'import à tous les niveaux.
Dans le menu déroulant, choisissez dans un premier temps, le niveau correspondant, puis le type de fichier d'import souhaité.
* Cliquez sur « Sélection d’un niveau top» afin de choisir le périmètre ministériel concerné.
* Cliquez sur « Sélection d’une structure » afin de choisir la maille régionale ou départementale.
* Cliquez sur « Sélection d’un type d’import ».
- En cliquant sur « properties », vous téléchargerez le fichier d’import pour les **données qualitatives**.
- En cliquant sur « financials », vous téléchargerez le fichier d’import pour les **données quantitatives**.

➢ Cliquez sur le bouton **« *Télécharger le template* »** pour obtenir le **fichier d'import** qui est le fichier à remplir.

!!!warning Attention
Les fichiers d'import sont en format Excel, merci de les ré-importer dans le proPilot sous ce format.
Les formats .ods de Libre Office ne sont pas pris en compte.
!!!


### 3 - Import de données qualitatives

Chaque ministère est décomposé par niveaux pour assurer la déclinaison territoriale: réformes, régions, départements...
Pour chaque niveau, les entités sont identifiées grâce à **leur nom, un code et le code de l’entité supérieure dite « Parent »**. Il convient de télécharger ces informations pour le ministère ou la réforme concernée pour remplir les trois premières colonnes du fichier Excel (Nom du parent, nom et code de l’entité).

!!!warning Attention
**Les colonnes Réforme Code / Région Name / Région Code ne peuvent être modifiées ou supprimées pour réaliser l'import.**
!!!


#### 3.a - Télécharger le fichier d'export

1 - Dans l’interface utilisateur, téléchargez le fichier d’export en allant dans la bannière de gauche sur :
* **« *Attribution* »** (1) puis sélectionnez le **périmètre** (2)
* Sur la page à droite, cliquez sur la **réforme** (3)
![](https://hackmd.io/_uploads/Sy_JoDnQq.jpg)

2 - Dans le sous-menu, cliquez sur ***« Exporter »***
![](https://hackmd.io/_uploads/SyfJ6Dhmq.jpg)


3 - Cliquez sur le bouton **« *Générer un nouveau rapport* »**

4 - Puis sur **« *Télécharger* »**
![](https://hackmd.io/_uploads/ryQCnvnmc.jpg)

5 - **Ouvrez le fichier d’export (Excel)**

#### 3.b - Récupérer les colonnes d'identification

1 - Allez sur l'onglet « Région Properties » ou « Département Properties » suivant le niveau d'import que vous souhaitez réaliser

2 - Les colonnes indispensables pour l'identification sont :
* pour la maille départementale : Réforme Code | Département Name | Département Code
* pour la maille régionale : Réforme Code | Région Name | Région Code

3 - Copiez / collez ces colonnes d'identification dans le **fichier d’import** téléchargé précédemment.


#### 3.c Saisissez les informations qualitatives

1 - **Dans le fichier d'import**, saisissez les données qualitatives dans les colonnes correspondantes.

2 - **Les colonnes non renseignées peuvent être supprimées**

3 - Enregistrez le fichier modifié (sous format Excel).

!!!info Bonnes pratiques lors de la saisie
* UTILISER LE TEMPLATE correspondant au périmètre. Bien que les colonnes soient identiques, une clé de sécurité ne permet pas d'utiliser les template de façon indifférenciée. Par exemple, le template 'Handicap' ne peut être utilisé pour les réformes 'Solidarité'.
* NE PAS MODIFIER les données des colonnes d'identification.
* SUPPRIMER du fichier d'import les colonnes qui ne sont pas mises à jour.
* ATTENTION AUX CELLULES VIDES : en important des cellules vides vous pouvez supprimer les informations qualitatives qui auraient déjà pu être importées ou saisies.
* Sur un même fichier d'import, vous pouvez renseigner plusieurs région ou plusieurs département (en fonction de la maille choisie) tant que le périmètre ministériel et la maille géographique sont respectés.
* RESPECTER le format Excel du fichier (pas de .ods)
!!!

#### 3.d Importez le fichier complété

1 - Dans le menu à gauche cliquez sur ***Admin*** puis ***Importer***. Un nouvel onglet 'AdminPropilot' s'ouvre dans votre navigateur (comme pour le téléchargement des templates d'import).

2 -Dans la partie **« *Importer des fichiers* »**
* « Sélectionnez un niveau top» afin de choisir le périmètre ministériel concerné.
* « Sélectionnez une structure » afin de choisir la maille souhaitée : Région / Département.
* « Sélectionnez un type d’import » :
    * **Properties** pour les données qualitatives
    * **Financials** pour les données quantitatives

3 - En cliquant sur **« *Browse File* »**, sélectionnez le fichier Excel complété. Ou faites un glisser/déposer dans le rectangle bleu.

4 - Ne cochez aucune des cases disponibles une fois le fichier sélectionné.

5 - Cliquez sur **« *Importer des fichiers* »**. 


### 4. Import de données quantitatives


### 5. Vérifier mon import massif

#### 5.a Vérification technique

1. Une fois l'import réalisé, cliquez sur 'SUIVI' dans la bannière de gauche,

2. puis sur la tuile 'JOBS'.

3. Le status de votre import doit être 'Succès'.

4. En cas d'erreur, vous pouvez trouver plus d'information en cliquant sur "Détails".

!!!info Les différents statuts possible suite à l’import
* Errors : 
    * Lorsque le fichier n'est pas traitable. Par exemple ; lorsque vous avez téléchargé le fichier pour le ministère de l'intérieur et que vous l'importez pour le ministère du travail,
    * le format du fichier n'est pas respecté,
    * le code n'est pas correct (cf. colonnes d'identification),
    * une cellule obligatoire est on renseignée,

* Warnings : Lorsque le proPilot est capable de traiter une partie de l'information. Par exemple, une propriété de type menu déroulant, telle que la météo, mal orthographiée.

* Success : Lorsque le fichier est correctement rempli et qu'aucune erreur n'a été détectée.
!!!

#### 5.b Vérification dans l’interface utilisateur

1. Retournez sur l'onglet 'ProPilot' de votre navigateur.

2. Rendez-vous sur une des réformes modifiées (en utilisant par exemple le Région code ou Département code dans la barre de recherche).

3. Les mises à jour et la date de dernière mise à jour s'affichent dans les tuiles.
