# Aide de sCollect

## Ce que fait l’app

sCollect gère des collections de médias — musique, films, vidéos personnelles, livres
audio, podcasts, e-books — et des objets de collection qui ne sont pas des fichiers
médias, comme des pièces ou des timbres. C’est vous qui décidez du nom des catégories,
sous **Réglages → Libellés de catégories**.

Ce que vous saisissez dans l’éditeur, l’app l’écrit **dans le fichier lui-même**, et pas
seulement dans son propre catalogue.

## Premiers pas

1. Au premier démarrage, choisissez un dossier pour la bibliothèque. C’est là que se
   trouveront ensuite les données du catalogue et, si vous le souhaitez, les fichiers
   médias.
2. Faites entrer des fichiers ou des dossiers par **Fichier → Importer des fichiers** (⌘O)
   ou **Fichier → Importer un dossier** (⇧⌘O), ou glissez-les sur la fenêtre.
3. À l’importation, vous décidez pour chaque passage si les fichiers sont **copiés vers la
   bibliothèque** ou seulement **liés**.

## Gérés ou liés ?

| | |
|---|---|
| **Géré** | Le fichier se trouve dans la bibliothèque. sCollect le classe, le nomme selon votre schéma et écrit les tags. |
| **Lié** | Le fichier reste là où il est. sCollect mémorise l’emplacement et **ne touche pas au fichier**. |

La colonne « Lié » dans la liste montre ce qu’il en est.

## Questions fréquentes

**Une entrée porte un triangle d’avertissement orange.**
Son fichier était introuvable lors du dernier passage de **Fichier → Bibliothèque → Marquer
les éléments manquants**. L’entrée ne peut alors pas être modifiée — il n’y a rien où
écrire. Le menu contextuel propose **Rechercher le fichier…** ; le fichier trouvé est
ramené dans la bibliothèque.

**Le menu contextuel indique « Disque non connecté », grisé.**
Ce n’est alors pas le fichier qui manque, mais le disque. sCollect distingue
expressément les deux cas : ce qui n’est pas connecté ne peut pas non plus être vérifié
— et n’est donc pas marqué comme manquant. Branchez le disque et relancez le passage.

**Un type de média est gris et ne peut pas être changé.**
Son dossier n’est pas accessible en ce moment. sCollect verrouille de tels types plutôt
que de déposer les fichiers ailleurs en silence. Dès que le disque est de retour, le
verrou disparaît.

**L’éditeur affiche « Un champ diffère du fichier ».**
Dans un champ, le fichier porte autre chose que la bibliothèque — le plus souvent parce
qu’un autre programme l’a modifié entre-temps. Le bandeau au-dessus des champs montre
lesquels sont concernés, et vous décidez champ par champ si la valeur du fichier est
reprise.

**Je ne trouve pas un champ dont j’ai besoin.**
Pour les objets de collection, il existe trois champs librement nommables. Leur nom se
règle par catégorie sous **Réglages → Libellés de champs**.

**Puis-je reprendre ma collection iTunes ou Musique ?**
Oui. sCollect lit le XML iTunes, notes et playlists comprises. Les titres sont
associés par leurs chemins de fichiers ; les notes existantes ne sont pas écrasées.

**Comment faire ressortir ma collection ?**
Par le **sCollect-XML** — il est sans perte et sert en même temps de sauvegarde. À côté
de cela, il y a l’exportation en XML iTunes et en playlist pour Apple Music.

**Que fait la synchronisation avec les copies ?**
Une bibliothèque peut déclarer d’autres bibliothèques comme copies. Les modifications du
fonds principal y sont reportées, fichiers et tags compris. Si une copie est hors ligne,
la modification attend et est rattrapée plus tard.

⚠️ **Ce n’est pas une sauvegarde.** Un fichier supprimé est aussi supprimé dans les
copies — c’est le but d’une synchronisation. Au cas où quelque chose tournerait mal, il
vous faut en plus une véritable sauvegarde.

**Mon fichier perd-il en qualité lors de l’écriture des tags ?**
Non. Les données audio et image sont reprises telles quelles ; rien n’est réencodé. Là
où c’est possible, sCollect ne modifie que les quelques octets du tag au lieu de
réécrire le fichier.

**Puis-je annuler une modification ?**
⌘Z ramène les entrées supprimées. Les modifications de métadonnées, non — faites donc une
sauvegarde avant un grand traitement par lots.

## Quelque chose ne va pas ?

sCollect écrit un journal dans le dossier de votre bibliothèque — il retient ce que l’app a
fait et quand. Joignez-le à votre description de l’erreur.

## Contact

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
