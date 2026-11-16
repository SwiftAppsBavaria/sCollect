# Politique de confidentialité de sCollect

Mise à jour : 2026-11-16

## En bref

sCollect ne collecte, n’enregistre et ne transmet **aucune** donnée personnelle. L’app
travaille exclusivement sur votre Mac ou votre PC Windows. Il n’y a ni comptes, ni connexion au cloud, ni
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

## Sous Windows

Les sections ci-dessus décrivent le Mac. Sous Windows, sCollect enregistre les éléments suivants exclusivement en local :

Dans le dossier de données de l’app (`%LOCALAPPDATA%\Packages\<paquet>\LocalState` et `Settings`) :

- **Les réglages, la position de la fenêtre et la vue** — les bibliothèques ouvertes récemment, la sélection dans la barre
  latérale, les derniers titres lus, les colonnes et le tri.
- **La correspondance entre les dossiers Mac d’une bibliothèque et des dossiers de votre PC** (chemins de dossiers uniquement).
- **Des aides à la saisie** — les valeurs que vous avez déjà utilisées dans des champs comme le genre ou la langue, proposées
  comme suggestions.
- **Un identifiant aléatoire de ce PC.** Il distingue vos ordinateurs pour les copies d’une bibliothèque et ne contient rien sur
  vous.
- **Un journal de diagnostic** avec les horodatages, les opérations et les chemins des fichiers concernés, et un **journal des
  erreurs** (`fehler.log`, sept jours). Tous deux restent sur votre PC ; vous pouvez les transmettre si vous signalez une
  erreur.

Dans le dossier de la bibliothèque que vous avez choisi : les données du catalogue, les pochettes, la corbeille de la
bibliothèque et — si elle a des copies — leurs emplacements et les synchronisations pas encore exécutées. Tant que sCollect a
une bibliothèque ouverte, il y dépose en outre un **fichier de verrouillage** contenant le **nom de votre PC**, afin que deux
ordinateurs n’écrivent pas en même temps dans la même bibliothèque. Si la bibliothèque se trouve sur un lecteur réseau, les
autres utilisateurs de ce lecteur peuvent voir ce nom.

Ce qui se trouve dans le dossier de données de l’app est supprimé lorsque vous désinstallez l’app ; la bibliothèque reste
jusqu’à ce que vous la supprimiez vous-même.

sCollect ne lit et n’écrit des fichiers médias que dans les dossiers que vous lui confiez. L’app n’établit aucune connexion
réseau propre, n’utilise aucun service d’analyse et n’affiche aucune publicité. Les fichiers que Windows ne lit pas lui-même
sont transmis au programme par défaut pour ce type de fichier, que vous choisissez dans Windows. Pour convertir et raccourcir le
son et la vidéo, l’app utilise le FFmpeg fourni avec elle, là aussi uniquement sur votre PC.

Si vous envoyez une playlist à iTunes, sCollect ouvre iTunes pour Windows avec cette playlist ; l’app ne pilote aucun autre
programme. Si vous exportez une playlist pour VLC ou un appareil, l’app copie ses fichiers dans le dossier que vous choisissez.

## Microsoft Store

Sous Windows, l’achat, le téléchargement et les mises à jour passent par le Microsoft Store ; la déclaration de confidentialité
de Microsoft s’y applique.

## Aucune transmission, aucune analyse

Il n’y a pas de publicité, pas de services d’analyse, pas de rapports de plantage à des
tiers et pas de comptes.

## Contact

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
