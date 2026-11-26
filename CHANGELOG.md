# Journal des versions

Ce qui change d'une version à l'autre de la bêta, la plus récente en premier. Les fichiers à
télécharger sont sur la [page de la dernière version](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest).

## 1.0.116 — 26 novembre 2026

Pour LG, Samsung, Android, Android TV et Windows.

**Listes**
- Depuis l'Accueil et la recherche, tu choisis où ranger un titre dès qu'une de tes playlists du
  même type existe.
- Dans Films et Séries, **Mes listes** les montre en tuiles : Ma liste, puis tes playlists. OK ouvre
  la liste, Retour revient sur sa tuile.
- Les playlists de **films** et de **séries** sont maintenant séparées.

**Profils**
- La bulle du profil déroule tes profils et **Gérer les profils**.
- Quand deux profils utilisent la même source, passer de l'un à l'autre ne recharge plus
  l'application.

**Trakt**
- Un appareil relié s'adresse maintenant directement à Trakt pour le nom du compte, la
  synchronisation et les recommandations, qui échouaient en passant par notre serveur.

**Lecture**
- Replay : après une coupure répétée au même endroit, la lecture passe à la minute suivante au lieu
  de tourner en boucle.
- Un film demandé puis aussitôt remplacé par une chaîne ne s'ouvre plus par-dessus.
- **Android et Android TV** : le menu **Audio** propose les pistes des chaînes et du replay, et
  ouvrir la fiche d'un film ne change plus la langue d'une chaîne.

**Affichage**
- **Rechercher** passe en tête de la barre d'onglets (sauf si tu avais déjà rangé tes onglets).
- L'Accueil a un élément sélectionné dès sa première ouverture, et la coche des menus se voit de
  nouveau.
- Les pictos TV, Films et Séries sont redessinés.

**Mac et Apple TV** : pas de nouvelle version cette fois. Les fichiers proposés restent ceux de la
1.0.99.

## 1.0.115 — 25 novembre 2026

Petite version, le jour même de la 1.0.114, pour LG, Samsung, Android, Android TV et Windows.

**Android et Android TV**
- La **normalisation du son** (Paramètres, Léger ou Fort) est maintenant calculée par
  l'application elle-même, et non plus par le téléviseur. Le volume reste le même ; elle marche
  aussi sur les appareils plus anciens (avant Android 9).
- Si l'image se fige en lecture, le journal envoyé au support dit précisément ce que faisait le son
  à ce moment-là : ça nous aide à trouver la cause.

**Mises à jour**
- Une nouvelle version est maintenant **proposée dès le lancement**, sur l'écran « Qui regarde ? »,
  avant le chargement de tes chaînes. Si le site ne répond pas, l'application démarre quand même
  au bout de quelques secondes. Rien ne change si tu as choisi « Ne pas vérifier ».

**Fiche d'un film ou d'une série**
- Le bouton **Version** garde toute sa largeur : son libellé (avec le débit) tient sur une ligne,
  deux au plus pour les plus longs, et ne déborde plus de son cadre.

**Trakt**
- **Chaque profil relie son propre compte Trakt** (Paramètres › Trakt). Le compte relié avant
  cette version reste celui du premier profil ; les autres profils démarrent sans compte.
- **Premium** : le compte Trakt d'un profil le suit sur tous tes appareils reliés à ton compte
  CroissantTV, sans retaper de code. Se déconnecter de Trakt le fait sur tous ces appareils.
- **Retirer des recommandations** : sur un titre des rangées « Films recommandés pour vous » et
  « Séries recommandées pour vous », depuis son volet ou avec la touche jaune (Options). Le titre
  disparaît et le suivant prend sa place ; les titres qui lui ressemblent remontent moins. Avec un
  compte Trakt, le titre est aussi masqué de tes recommandations sur Trakt.

**Mac et Apple TV** : pas de nouvelle version cette fois. Les fichiers proposés restent ceux de la
1.0.99.

## 1.0.114 — 25 novembre 2026

Cette version sort en même temps pour LG, Samsung, Android, Android TV et Windows. Elle soigne la
lecture des films en 4K, les Tendances et Trakt. (La 1.0.113 n'a pas été publiée : tout ce
qu'elle contenait est ici.)

**Films et séries en 4K (LG et Samsung)**
- Un film en 4K très lourd ne saute plus dans le vide quand la connexion faiblit : l'application
  attend de reconstituer une réserve, puis reprend là où elle s'était arrêtée.
- Chaque ouverture d'une version repart d'un compteur neuf : la lecture n'est plus coupée à tort.
- Le **débit** de chaque version s'affiche dans la liste des versions, sur le bouton Version et
  dans la fiche technique.
- Quand la lecture échoue, le message dit mieux pourquoi.

**Tendances et Trakt**
- La rangée « Pourraient vous plaire » reste là même quand Trakt refuse un instant, et se
  construit à partir de ce que tu regardes.
- Trakt reçoit enfin les **épisodes** que tu as vus. Pour envoyer ce que tu avais déjà vu :
  Paramètres › Trakt › **Envoyer mes vus et Ma liste vers Trakt**, une fois par appareil relié.

**Paramètres**
- « Sauvegarder votre configuration » et « Contacter le support » se font en étapes numérotées,
  avec une bulle « comment scanner ». Le journal n'est plus dans les réglages : il part avec le
  message au support.
- Le bouton « ? Aide » est plus discret.

**Affiches**
- Quand le fournisseur n'a pas d'affiche, la carte montre le nom du titre au lieu d'un cadre vide.

**Réseau (Windows)**
- Résolution DNS : avis clair pour Quad9 (coupé en France) ; DNS.WATCH, NextDNS et AdGuard
  fonctionnent de nouveau.

**Android et Android TV**
- Si l'image se fige en lecture, l'application relance un lecteur neuf au même endroit.

**Mac et Apple TV** : pas de nouvelle version cette fois. Les fichiers proposés restent ceux de la
1.0.99.

## 1.0.112 — 22 novembre 2026

Cette version sort en même temps pour LG, Samsung, Android, Android TV et Windows. Elle
réorganise l'accueil, la navigation à la télécommande et le lecteur. (La 1.0.111 n'a pas été
publiée : tout ce qu'elle contenait est ici.)

**Accueil et navigation**
- En tête de l'Accueil, deux onglets : **Mon accueil** et **Tendances**.
- La flèche **haut** remonte jusqu'à la barre des onglets depuis n'importe quel écran, et la
  flèche **bas** te ramène là où tu étais.
- **Retour** remonte pas à pas jusqu'à « Fermer CroissantTV ? » (réglage « Demander avant de
  fermer l'application »).
- Dans le Guide TV, la liste des chaînes boucle de la dernière à la première.
- Les rangées apparaissent en fondu ; les cartes « En ce moment sur vos chaînes » sont plus
  compactes et le nom de la chaîne tient sur deux lignes.

**Aide**
- Un bouton **? Aide** à côté de ton profil, au même endroit sur tous les onglets, et en haut des
  Paramètres : il explique les touches de l'écran où tu es. La touche Bleue fait toujours la même
  chose.

**Lecteur**
- **GUIDE** est le premier bouton de la rangée ; les boutons ▼ / ▲ disparaissent (les touches,
  elles, changent toujours de chaîne).
- **Rechercher la VOD** (la loupe) cherche le programme en cours dans tes films et séries. Un
  résultat ouvre désormais la **fiche** du titre ; une série n'apparaît qu'une fois, plus épisode
  par épisode.

**Paramètres**
- Dans les listes de catégories, une ligne **Tout décocher** (puis « Tout cocher »).
- Les Options (touche Jaune) qui règlent une taille ou un thème restent ouvertes et montrent la
  valeur choisie.
- La fiche d'une source propose directement le **DNS** et le **proxy SOCKS5**.
- « Qui regarde ? » : le crayon « Personnaliser » passe au-dessus de chaque profil.

**Sport et Tendances**
- La rangée des directs s'appelle **Événements diffusés**.
- Le Sport et les Tendances s'affichent plus vite au démarrage.

**Sources**
- Quand le serveur de ton fournisseur refuse l'accès (identifiants, ligne coupée…), l'application
  le dit clairement au lieu d'afficher « relais HTTP 404 », et ne réessaie plus en boucle.

**Téléphone Android**
- Même présentation que sur le téléviseur : cartes, rangées, lecteur (GUIDE en tête, loupe
  « VOD »), fiche avec « Titres associés » et « Similaires » ; sur tablette, « Aller à » et
  « Revenir au présent » dans le guide.

**Mac et Apple TV** : pas de nouvelle version cette fois. Les fichiers proposés restent ceux de la
1.0.99.

## 1.0.110 — 21 novembre 2026

Cette version sort en même temps pour LG, Samsung, Android, Android TV et Windows. Elle simplifie
les touches de couleur et rend de la place à l'écran.

**Touches de couleur : le même sens partout**
- **Rouge** : rechercher. **Vert** : ajouter le titre ou la chaîne à ta liste ou à tes favoris,
  ou l'en retirer. **Jaune** : les options de l'écran (zoom, tri, réorganiser, sources,
  contacter le support…). **Bleu** : l'aide, qui rappelle ce que font les touches là où tu es.
- Sur Windows : <kbd>F3</kbd> rouge, <kbd>F2</kbd> vert, <kbd>F9</kbd> jaune, <kbd>F1</kbd> bleu.

**Plus de place à l'écran**
- La bande des raccourcis en bas de l'écran disparaît : les affiches des films et des séries ne
  sont plus coupées, le guide TV et les tableaux du Sport s'agrandissent.

**Paramètres**
- « Dépannage » s'appelle désormais **Réseau**.
- Nouvelle ligne **Fermer l'application**, sous « Réglages avancés ».
- Sur certains téléviseurs, l'ouverture des Paramètres pouvait clignoter longtemps pendant que le
  guide TV se chargeait : ça ne devrait plus arriver.

**Téléphone Android**
- L'onglet Sport n'affiche plus « Erreur d'affichage : tr is not a function ».

**Windows**
- Si « Installer » la mise à jour échoue avec « native-tls: unable to find any user specified
  roots… », installe une fois cette version à la main (`CroissantTV-Windows-Setup.exe`, par-dessus
  l'ancienne) : les mises à jour suivantes passeront.

**Mac et Apple TV** : pas de nouvelle version cette fois. Les fichiers proposés restent ceux de la
1.0.99.

## 1.0.109 — 21 novembre 2026

Cette version sort en même temps pour LG, Samsung, Android, Android TV et Windows. Elle retouche
surtout les grilles de films et séries, les Tendances et le lecteur.

**Films et séries**
- Le panneau d'information à droite des grilles est redessiné : plus lisible, mieux rempli, avec
  la catégorie, le titre, la note, l'année, la durée et les genres bien séparés. La carte « Au
  hasard » change aussi.
- Nouveau choix **Automatique** dans « Qualité des jaquettes » : la netteté des affiches suit
  leur taille à l'écran. C'est le réglage d'une nouvelle installation ; si tu avais déjà choisi
  « Réduites (fluide) », il reste.
- L'œil passe en bas à gauche de l'affiche, et la 4K prend un dégradé jaune orangé.
- Quand tu ajoutes un titre à une liste, le cœur apparaît tout de suite, sans changer de page.
- Au retour d'une fiche, la sélection revient sur l'affiche d'où tu venais, et non sur « Mon accueil ».

**Tendances**
- Elles s'ouvrent aussitôt, avec la dernière sélection gardée, puis se mettent à jour quand
  Trakt répond. Le rang est dans un coin de l'affiche, avec un filet or, argent et bronze pour
  les trois premiers.

**Guide TV et fiches**
- Les cadres du guide et des fiches sont redessinés pour alléger l'affichage.

**Lecteur**
- Si le flux se coupe en plein épisode ou en plein replay, le lecteur reprend tout seul au même
  endroit, après quelques secondes, au lieu d'afficher « Lecture impossible ».

**Compte**
- À l'appairage avec ton compte, l'appareil porte son vrai nom (par exemple « Philips
  TPM191E · Android 12 ») au lieu de « CroissantTV — Android ».

**Mac et Apple TV**
- Pas de nouvelle version cette fois : le Mac et le prototype Apple TV restent en 1.0.99. Leurs
  fichiers sont toujours sur la page de la dernière version.

## 1.0.108 — 19 novembre 2026

Cette version sort en même temps pour LG, Samsung, Android, Android TV et Windows. Elle refait
une bonne partie de l'apparence de l'application.

**Films et séries**
- Les pastilles des affiches sont redessinées et suivent la taille des affiches ; la 4K est en
  doré. Un **œil** montre ce que tu as commencé (gris) ou déjà vu (jaune), un **cœur** les titres
  de tes listes et de tes favoris.
- Le bouton de catégorie au-dessus des grilles est plus simple, et le panneau d'information à
  droite des grilles s'arrête maintenant aux acteurs.
- Une langue masquée dans les réglages masque aussi ses catégories.
- Quand une série existe en plusieurs versions, l'application ouvre en priorité celle qui a le
  plus d'épisodes dans ta langue, et reconnaît mieux la version originale.
- « Versions affichées », « Noms des films & séries » et le masquage d'une langue du catalogue
  font maintenant partie de **Premium**. « Version à ouvrir en priorité » et « Qualité maximale »
  restent gratuites.

**Accueil**
- Les cartes « En ce moment sur tes chaînes » montrent la qualité (HD, FHD, 4K…) quand le nom de
  la chaîne l'indique.
- Le défilement de l'Accueil et des grilles est plus fluide sur les TV LG.
- Les **Tendances** restent affichées quand Trakt ne répond pas.

**Guide TV**
- « Maintenant » devient « **Revenir au présent** », affiché seulement quand tu t'es éloigné du
  direct.
- Le bouton zoom fait tourner trois tailles, **Petit, Moyen et Grand**, texte compris. Ton ancien
  réglage est repris au plus proche.
- « Aujourd'hui » devient « **Aller à** » : après la date, tape l'heure avec les chiffres de la
  télécommande.

**Lecteur**
- Le **guide pendant une chaîne** (bouton Guide) est refait : la catégorie en tête, ◄ ► pour en
  changer, le logo de chaque chaîne, le programme en cours avec sa progression et le suivant.
  Retour le ferme. Si tu choisis une chaîne d'une autre catégorie, ▲ ▼ zappent ensuite dans
  celle-ci.
- Boutons **Audio** et **Sous-titres** en pictogrammes, plus de loupe dans les lecteurs de films et
  de séries, pas de « Précédent » sur le premier épisode d'une série. Le nom de la source ne
  s'affiche plus que sur les chaînes.
- Séries : une seule proposition « Passer le résumé », et le générique de début est mieux reconnu.

**Windows**
- Le curseur devient une main sur tout ce qui se clique, la barre du bas parle d'« Entrée » et de
  la touche ⌫, et chaque fenêtre a sa petite croix de fermeture.
- Un bouton de **volume** dans le lecteur, et un bouton « Catégories » au-dessus du guide TV.

**Mac et Apple TV**
- Pas de nouvelle version cette fois : le Mac et le prototype Apple TV restent en 1.0.99. Leurs
  fichiers sont toujours sur la page de la dernière version.

## 1.0.107 — 18 novembre 2026

Cette version sort en même temps pour LG, Samsung, Android, Android TV et Windows.

**Samsung**
- Corrigé : la rangée **« Reprendre »** restait vide, car la position des films et des épisodes
  n'était pas enregistrée sur certaines TV Samsung.
- L'aperçu de la chaîne dans le Guide TV, parfois mal cadré ou à moitié noir, est recadré à chaque
  changement de taille. Nous n'avons pas pu l'essayer sur une vraie TV Samsung : si le problème
  reste, passe par « **Contacter le support** » dans les Paramètres, le journal joint dit
  maintenant ce que la TV a reçu.

**Aide**
- « **Contacter le support** » joint maintenant ton journal tout seul : son code est dans le sujet
  de l'e-mail, tu n'as rien à envoyer en plus.

**Séries**
- Quand tu passes à l'épisode suivant pendant le générique de fin, l'application s'en sert pour
  proposer plus tôt l'épisode suivant, sur cette série, à tous les utilisateurs.

**Mac et Apple TV**
- Pas de nouvelle version cette fois : le Mac et le prototype Apple TV restent en 1.0.99. Leurs
  fichiers sont toujours sur la page de la dernière version.

## 1.0.106 — 18 novembre 2026

Cette version sort en même temps pour LG, Samsung, Android, Android TV et Windows. Elle réunit
tout ce qui a changé depuis la 1.0.103 : sur Android, une partie est déjà arrivée par la mise à
jour automatique.

**Tendances**
- Nouvel écran **Tendances** (la flamme de l'accueil) : les films et les séries du moment selon
  Trakt, pris uniquement dans ton catalogue. Films et séries sont séparés, avec leur rang et un
  choix par genre ; OK ouvre un volet avec la bande-annonce.
- Dans la fiche d'un film ou d'une série, une rangée de **titres similaires**, eux aussi pris dans
  ton catalogue.
- La **bande-annonce** se regarde dans l'application, sans la quitter (« Regarder ici ») ; le code QR
  pour la voir sur ton téléphone reste proposé.

**Films, séries et lecteur**
- **Recherche** directement dans les onglets Films et Séries ; la barre du haut se replie quand tu
  descends dans la grille.
- Nouveau bouton **« Passer le résumé »** (ou « Passer l'aperçu ») dans le lecteur. Il ne part
  jamais tout seul.
- L'épisode suivant démarre plus vite après le générique.
- Les chapitres de certains films ne sont plus proposés par erreur comme sous-titres.

**Guide TV et accueil**
- Le Guide TV affiche la qualité des chaînes (HD, FHD, 4K…) en pastilles, le nom de la chaîne en
  entier, une ligne sélectionnée bien visible, et prend la couleur de ton thème.
- Tes favoris n'entrent plus d'eux-mêmes dans les rangées de l'accueil ; les séparateurs de
  catégorie de certains fournisseurs ne finissent plus dans tes favoris.

**Sport**
- Le tennis est mieux suivi ; les affiches ne montrent plus de rencontres déjà jouées ; chaque sport
  a ses propres libellés ; la chaîne proposée pour un match est d'abord celle de ta langue.

**Ton compte et la synchronisation**
- Entre tes appareils reliés au même compte, un changement arrive en une seconde environ.
- « Mon compte » : les textes sont plus grands et se parcourent à la télécommande. « Envoyer mes
  listes » te dit pourquoi le site refuse, s'il refuse.
- Corrigé : la bascule jour / nuit restée active remplaçait le thème de ton profil.

**Samsung**
- Corrigé : sur certaines TV Samsung, l'application pouvait se fermer toute seule une dizaine de
  secondes après l'ouverture de l'accueil. Nous pensons avoir trouvé la cause, sans avoir pu
  l'essayer sur une vraie TV : dis-nous si ça t'arrive encore, et sur quel écran.

**Mac et Apple TV**
- Pas de nouvelle version cette fois : le Mac et le prototype Apple TV restent en 1.0.99. Leurs
  fichiers sont toujours sur la page de la dernière version.

## 1.0.103 — 15 novembre 2026

Cette version réunit tous les travaux récents : elle sort en même temps pour LG, Samsung, Android,
Android TV et Windows.

**Paramètres**
- Les Paramètres sont plus faciles à parcourir. Par défaut, tu ne vois que l'essentiel : un
  interrupteur « Réglages avancés » en bas de la liste affiche tout le reste. Ce choix est propre à
  chaque appareil.
- Les rubriques ont de nouveaux noms : **Profils et comptes**, **Chaînes et guide TV**, **Contrôle
  parental**, **Dépannage** et **Application**. Plusieurs lignes ont aussi un nom plus clair.
- Les réglages sont rangés là où on les attend : « Au démarrage » avec les profils, le tri et les
  chaînes cachées avec les chaînes, les connexions de l'abonnement avec les sources. Les réglages qui
  apparaissaient deux fois n'existent plus qu'une seule fois.
- Trois réglages en remplacent six : l'horloge du lecteur (masquée, heure, ou heure et date), les
  infos techniques (masquées, étiquettes ou résolution) et l'épisode suivant (jamais, à la fin, ou
  dès le générique de fin). Toutes les tailles sont réunies sur un seul écran, tous les réglages des
  sous-titres sur un autre.
- La taille des affiches se règle maintenant avec le Zoom des grilles ; deux lignes qui ne servaient
  plus à rien ont disparu.
- Ce qui dépend de l'appareil (par exemple l'affichage des réglages avancés) ne se recopie plus sur
  tes autres appareils.
- « Effacer toutes les données » demande d'abord confirmation, remet l'appareil à zéro et le détache
  de ton compte, sans rien effacer sur le compte. Supprimer une source demande aussi confirmation.
- Corrigé : « Marquer les animes comme vus » (MyAnimeList) s'affichait activé alors que rien n'était
  envoyé ; la bascule jour / nuit respecte le thème de ton profil ; le tri des chaînes reste en place
  après une mise à jour du catalogue ; les lignes qui n'ont aucun effet sur ton appareil sont grisées.
- Téléphone : les écrans des Paramètres suivent les mêmes changements.

**Reprendre et synchronisation**
- « Reprendre » : une série reste dans la rangée tant que son dernier épisode n'est pas vu en entier,
  et revient quand tu la relances. Un film déjà vu que tu relances puis que tu coupes revient aussi ;
  si tu en as fini une autre version depuis, il ne revient plus.
- Ton compte recopie davantage de choses d'un appareil à l'autre (par exemple ta dernière chaîne).
- « Effacer toutes les données » sur un appareil relié à ton compte te prévient, puis détache
  l'appareil : ton compte reste intact.

**Samsung**
- La lecture passe d'abord par le lecteur de la télévision elle-même, et non plus par celui de
  l'application : l'image arrive plus vite.
- L'animation d'ouverture, les codes QR et la lecture par les autres moteurs étaient bloqués par une
  règle de sécurité de la télévision : c'est corrigé.
- Quand ton fournisseur refuse une chaîne, le message s'affiche en quelques secondes au lieu d'une
  minute, et l'application ne s'acharne plus sur le même lien.
- Si l'application se coupe encore toute seule, dis-nous sur quelle chaîne et à quelle heure : ça
  nous aide à retrouver la cause.

**Mac et Apple TV**
- Pas de nouvelle version cette fois : le Mac et le prototype Apple TV restent en 1.0.99. Leurs
  fichiers sont toujours sur la page de la dernière version.

## 1.0.102 — 15 novembre 2026

**Démarrage**
- L'application s'ouvre plus vite : elle reprend tout de suite ce qu'elle avait gardé (chaînes, films,
  séries, guide) et se met à jour derrière, sans te faire attendre. Si ton fournisseur est en panne ou
  lent, tu retrouves ta liste de chaînes, tes films et tes séries au lieu d'un écran vide.
- Le guide des programmes ne se vide plus quand il se met à jour. Application ouverte longtemps (une
  nuit, par exemple), il se renouvelle tout seul.
- L'Accueil garde ses rangées de films et de séries quand le guide arrive, et Sport se dessine plus
  légèrement, y compris juste après le démarrage.

**Sport**
- Quand les scores en direct ne répondent pas, Sport affiche « Impossible d'actualiser » au lieu de
  « Rien ne se joue en ce moment ».

**Sources**
- Portail Stalker : après des échecs répétés, l'application attend moins longtemps avant de
  réessayer (de 20 secondes à 15 minutes), et « Recharger la source », « Enregistrer et se connecter »
  ou la modification d'une source relancent tout de suite.
- Adresse d'une source (serveur, portail, M3U) : quand le champ est prérempli avec « http:// », le
  curseur se place à la fin et ce que tu tapes ne passe plus devant.
- « Qui regarde ? » : si tu crées ou retires un profil depuis un autre appareil de ton compte, l'écran
  déjà ouvert se met à jour.

**Sous-titres et Premium**
- La recherche de sous-titres passe uniquement par les serveurs de CroissantTV : plus aucune clé de
  service n'est livrée dans l'application.
- Premium : sur un appareil qui n'est pas relié à un compte, seule la période de découverte de 48 h
  ouvre les fonctions Premium.

**Android, Android TV et téléphone**
- L'application n'est plus « débogable » : son inspecteur n'est plus accessible de l'extérieur.
  Elle s'installe par-dessus la version précédente, comme d'habitude.
- Téléphone : playlists des films et séries depuis l'interface du téléphone ; « Passer le générique »
  revient dans la barre du lecteur quand la pastille a disparu ; la mise à jour du catalogue en
  arrière-plan attend que ton doigt soit levé et que les panneaux soient fermés.

**Windows**
- La mise à jour intégrée échouait avec « La mise à jour a échoué » (certificat du site refusé) :
  c'est corrigé. Pour en profiter, installe cette version par-dessus la tienne, une dernière fois, de
  la façon habituelle.

**Interface**
- « Verrouiller (parental) » et plusieurs infobulles s'affichent maintenant dans la langue choisie.

**Samsung, Mac et Apple TV**
- Pas de nouvelle version cette fois : le Samsung reste en 1.0.101, le Mac et le prototype Apple TV en
  1.0.99. Leurs fichiers sont toujours sur la page de la dernière version.

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
