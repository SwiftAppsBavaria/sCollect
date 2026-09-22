# Politique de confidentialité de sCollect

Mise à jour : 2026-09-16

## En bref

sCollect ne collecte, n’enregistre et ne transmet **aucune** donnée personnelle. L’app
travaille exclusivement sur votre Mac. Il n’y a ni comptes, ni connexion au cloud, ni
services d’analyse, ni publicité.

## Quelles données l’app traite

sCollect lit et écrit les fichiers médias dans les dossiers que vous lui avez expressément
confiés — par une sélection dans la fenêtre d’ouverture ou en les faisant glisser sur la
fenêtre. Sont lus le nom du fichier, sa taille, sa date et ses métadonnées ; sont écrites
les informations que vous saisissez dans l’éditeur.

Sans votre sélection, l’app n’accède à aucun fichier. macOS l’impose par la sandbox de
l’app.

## Ce que l’app dépose sur votre Mac

- **La bibliothèque elle-même** dans le dossier que vous avez choisi pour elle : les données
  du catalogue, les pochettes et un journal des synchronisations pas encore exécutées.
- **Les réglages et les positions des fenêtres** dans le dossier protégé de l’app.
- **L’autorisation de macOS de rouvrir vos dossiers au prochain démarrage.** Ce sont des
  chemins de dossiers qui sont enregistrés, pas des contenus de fichiers. C’est le seul
  moyen pour que l’app n’ait pas à redemander à chaque démarrage.
- **Un journal de diagnostic** avec les horodatages et le nombre d’opérations. Il reste
  sur votre Mac ; vous pouvez l’enregistrer et le transmettre si vous signalez une erreur.

Tout cela disparaît lorsque vous supprimez l’app et sa bibliothèque.

## Deux autorisations qui peuvent soulever des questions

**L’accès au réseau.** L’app le demande parce que macOS affiche vide la fenêtre d’aide
intégrée sans cette autorisation — l’aide est présentée par un composant du système qui
en a besoin, même s’il ne charge que des fichiers du programme lui-même. sCollect
n’appelle de lui-même **aucune adresse sur Internet**, ne télécharge rien et ne signale
rien.

Les bibliothèques sur des volumes réseau (SMB, NFS) sont atteintes par l’app via le
système de fichiers de votre Mac, et non par une connexion propre.

**Le pilotage d’Apple Music.** Lors de l’exportation d’une playlist, sCollect
ouvre Apple Music avec le fichier créé. macOS demande votre accord pour cela, et il est
demandé la première fois. L’app ne pilote aucun autre programme.

## Vos fichiers

sCollect modifie les métadonnées dans exactement les fichiers qui appartiennent à votre
bibliothèque et les déplace, lors du classement, à l’intérieur des dossiers que vous avez
autorisés.

**Les éléments liés restent intacts** — ils se trouvent en dehors de la bibliothèque, et
l’app n’y écrit rien.

Les fichiers supprimés passent d’abord dans une corbeille propre à la bibliothèque, d’où
ils peuvent être récupérés. Ils ne sont définitivement supprimés que lorsque vous la videz.

## Aucune transmission, aucune analyse

Il n’y a pas de publicité, pas de services d’analyse, pas de rapports de plantage à des
tiers et pas de comptes.

## Contact

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
