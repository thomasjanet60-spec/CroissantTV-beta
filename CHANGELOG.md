# Journal des versions

Ce qui change d'une version à l'autre de la bêta, la plus récente en premier. Les fichiers à
télécharger sont sur la [page de la dernière version](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest).

## 1.0.101 — 14 novembre 2026

**TV en direct**
- Un seul bouton **Zoom** au-dessus du guide réunit la taille du guide et celle du texte.

**Films et Séries**
- **Playlists** (Premium) : en plus de Ma liste, jusqu'à 10 playlists par profil, nommées comme tu
  veux et synchronisées avec ton compte. Sur la fiche d'un titre, « Ma liste » propose Ma liste, tes
  playlists et « Nouvelle playlist… » ; la touche **Jaune** des grilles aussi, dès qu'une playlist
  existe. Tu les retrouves et les gères (renommer, supprimer) dans **Mon Croissant**.
- « Source » quitte la barre au-dessus de la grille : il est dans le volet des catégories, à droite
  du titre, au-dessus de « Rechercher ».
- Un seul bouton **Zoom** remplace « Grille » et « Texte ».
- Le nombre de rayons n'est plus affiché, pour laisser plus de place.

**Interface**
- Derniers textes traduits en anglais et en espagnol (exemple des polices du premier lancement,
  taille des enregistrements).

**Mac et Apple TV**
- Pas de nouvelle version cette fois : le Mac et le prototype Apple TV restent en 1.0.99, leurs
  fichiers sont toujours sur la page de la dernière version.

## 1.0.100 — 11 novembre 2026

**TV en direct**
- Nouvelle grille des catégories de chaînes : depuis le guide, **Retour** l'ouvre en grand, en
  colonnes, avec le nombre de chaînes de chaque catégorie. « ← Guide » (ou Gauche depuis la
  première colonne) rend le guide.
- « Changer de source » se trouve maintenant dans cette grille. La barre au-dessus du guide ne
  garde que « Ce soir », « Maintenant », la taille du guide et celle du texte.

**Lecture**
- Bouton **AUDIO** dans les commandes du lecteur, pour choisir la langue de la piste.
- « Reprendre au début » fonctionne aussi après un retour en arrière rapide dans le direct.

**Interface**
- La fenêtre Premium tient entièrement à l'écran, boutons compris.
- Mon Croissant : Bas depuis un rappel descend dans la liste au lieu de remonter au menu.
- Les titres qui portent une année entre parenthèses la gardent (« Nosferatu (1922) »).
- La langue choisie au premier lancement (anglais, espagnol) est conservée aux lancements
  suivants.
- Traductions anglaises et espagnoles complétées (lecteur, sous-titres, réglages).

**Mac et Apple TV**
- Pas de nouvelle version cette fois : le Mac et le prototype Apple TV restent en 1.0.99, leurs
  fichiers sont toujours sur la page de la dernière version.

## 1.0.99 — 7 novembre 2026

**Synchronisation**
- Bug de synchronisation multi-appareil corrigé.

**Guide et rappels**
- Améliorations du guide des programmes et des rappels.

**Lecture**
- Moins de refus du fournisseur quand plusieurs écrans demandent des données en même temps.
- Améliorations de la recherche dans le lecteur.

**Catalogue**
- Les versions d'un même film ou d'une même série sont mieux regroupées.

**Navigation et Windows**
- Défilement à la molette plus naturel.
- Lecture plus stable sur Windows.

**Mac et Apple TV**
- Première version **Mac** (macOS 14 et plus récent) : [guide Mac](guides/Mac.md). La correction de la
  synchronisation multi-appareil n'y est pas encore : elle arrivera sur Mac dans la prochaine version.
- **Prototype Apple TV** (le direct seulement), à installer depuis un Mac avec Xcode :
  [guide Apple TV](guides/Apple-TV.md). Il n'a pas encore été essayé sur une vraie Apple TV : dis-nous si
  l'installation fonctionne chez toi.

## 1.0.98 — 2 novembre 2026

Comprend aussi les nouveautés de la 1.0.97, qui n'a pas été publiée.

**Séries**
- « Reprendre une série », sur l'accueil, annonce le même épisode que la fiche de la série, et la
  fiche s'ouvre sur la version que tu étais en train de regarder.
- Quand une série existe en VOST et en version française ou MULTI (c'est souvent le cas des
  mangas), elle s'ouvre sur la version française plutôt que sur la VOST.

**Lecteur (Android TV et téléphone)**
- La piste audio que tu choisis est bien celle que tu entends, et l'audiodescription n'est plus
  prise d'office au démarrage d'un film ou d'un épisode.
- Le bouton Lecture/Pause montre toujours le bon état.

**Premier lancement**
- Nouvelle question : quelles langues garder dans les catalogues, d'après celles que propose ton
  abonnement.
- Sur **téléphone et tablette**, les mêmes questions qu'à la TV pour régler l'application à ton
  goût ; les icônes des barres d'Android suivent le thème choisi.
- Interface en anglais et en espagnol : les nouveaux écrans sont traduits.

**Mises à jour**
- Sur **Windows**, l'application sait maintenant installer elle-même ses prochaines versions.
- Sur **Android**, si l'installation est encore refusée après l'autorisation, l'application te
  propose de passer par Downloader.

**Support**
- « Contacter le support » : l'e-mail préparé indique le nom de ton appareil en clair et quelques
  informations techniques (mémoire, réseau, erreurs récentes) qui nous aident à comprendre un
  problème.

## 1.0.96 — 1er novembre 2026

**Mises à jour**
- Sur **Android TV** et **téléphone Android**, l'application propose elle-même la nouvelle
  version : **Paramètres › Système & à propos › Mises à jour**. Android demande toujours de
  confirmer l'installation.
- Sur **LG**, **Samsung** et **Windows**, l'application te prévient et explique comment installer
  la nouvelle version par-dessus l'ancienne.

**Favoris**
- Dans le groupe Favoris du guide des programmes, la touche **jaune** retire la chaîne
  sélectionnée ; **maintenue**, elle permet de réorganiser (Retour pour terminer).
- Plus de blocage en réorganisant les favoris : il fallait parfois forcer la fermeture de
  l'application.
- Sur Android TV, un appui court sur la touche jaune n'ouvre plus la réorganisation.

**Navigation**
- Navigation en boucle dans la liste des chaînes et dans les grilles de films et de séries : en
  bas, la flèche du bas repart en haut ; en haut, la flèche du haut passe par les boutons, puis
  redescend tout en bas.

**Catalogue**
- Les catégories cachées dans les Paramètres disparaissent aussi de « Tous les films »,
  « Toutes les séries » et « Toutes les chaînes ».
- Coche sur les affiches : **jaune** pour un film ou une série vus en entier, **grise** pour une
  série commencée.

**Sauvegarde**
- Sauvegarde de la configuration (Premium) : les playlists de chaînes en font maintenant partie.

## 1.0.95 — 30 octobre 2026

- Les questions du premier lancement ne règlent que le profil qui les lance, et n'apparaissent
  plus dans les profils enfants.
- **Passer le générique** : le bouton apparaît dans la rangée de commandes du lecteur pendant le
  générique.
- Questions du premier lancement : réponses plus espacées, icône redessinée.

## 1.0.94 — 30 octobre 2026

- **Nouveau : les premiers pas.** À la première ouverture, CroissantTV te pose quelques questions
  pour se régler à ton goût, avec un aperçu de chaque choix, puis un écran « C'est prêt ! ».
  « Terminer maintenant » garde les réglages par défaut pour la suite. Les questions se relancent
  depuis les Paramètres. Voir [Premiers pas](guides/Premiers-pas.md).
- Nouveau réglage **Au démarrage** : ce que CroissantTV affiche en s'ouvrant.
- DNS et proxy se règlent directement sur l'écran de la source.

## 1.0.93 — 29 octobre 2026

- Android TV, Google TV, Fire TV : installation et mise à jour avec le code **7153068** dans
  l'application Downloader.
- Corrections dans la fabrication des paquets.

## 1.0.92 — 29 octobre 2026

**La bêta arrive sur les TV Samsung et sur Windows.**

- **Profils** : l'écran « Qui regarde ? » fait peau neuve. Un pinceau sous chaque profil pour le
  personnaliser, et la création d'un profil en plein écran.
- **Sous-titres en ligne** : la recherche de sous-titres fonctionne de nouveau.
- **Replay** : la fin d'une émission ne fait plus de retour en arrière, et la reprise est plus
  fluide.
- **Enregistrement** (Premium, Android TV et Windows) : enregistre une chaîne, ou programme un
  enregistrement depuis le guide des programmes.
- **Nouveaux épisodes** (Premium) : une pastille « Nouvelle saison » ou « Nouvel épisode » sur les
  séries.
- **Bande-annonce** : le bouton fonctionne de nouveau.
- **Clé USB** (Android) : sauvegarde et restauration de ta configuration dans un fichier.
- **Connexion libérée** : quand tu quittes CroissantTV sans l'arrêter, il coupe maintenant le flux.
  Ton abonnement est libre pour un autre appareil.
- **Profils protégés par un code** : ils se reverrouillent après 5 minutes passées hors de
  l'application.
- Et de nombreuses corrections : synchronisation des profils et des réglages entre appareils,
  épisode suivant, sport, traductions anglaise et espagnole.

## 1.0.88 — 20 octobre 2026

Première version bêta : TV LG, Android TV, téléphones et tablettes Android.
