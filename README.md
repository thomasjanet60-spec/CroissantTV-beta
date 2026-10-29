<p align="center">
  <img src="images/logo.png" alt="CroissantTV" width="420">
</p>

# CroissantTV — version bêta

Bienvenue, et merci de tester **CroissantTV** !

CroissantTV est un lecteur pour regarder **ton abonnement IPTV** : chaînes en direct avec le guide des
programmes, films, séries, replay et sport, sur ta TV, ton téléphone ou ton ordinateur, avec un profil pour
chaque membre de la famille.

> [!IMPORTANT]
> CroissantTV **ne fournit aucune chaîne ni aucun film** : il lit l'abonnement que tu as déjà (Xtream, M3U ou
> portail Stalker). Pas d'abonnement ? Le mode **Démo** te fait découvrir l'application.

**Version actuelle : 1.0.92**, bêta du 29 octobre 2026.

## 1. Choisis ton appareil

| Ton appareil | Ce que tu télécharges | Le guide pas à pas |
|---|---|---|
| **TV LG**, 2020 ou plus récente | [Kit LG](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV-Kit-LG.zip), sur un ordinateur | [Installer sur LG](guides/LG.md) |
| **TV Samsung**, 2019 ou plus récente | [Kit Samsung](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV-Kit-Samsung.zip), sur un ordinateur | [Installer sur Samsung](guides/Samsung.md) |
| **Android TV, Google TV, Fire TV** (TV, boîtier ou clé) | rien : tout se fait sur la TV | [Installer sur Android TV](guides/Android-TV.md) |
| **Téléphone ou tablette Android** | [CroissantTV.apk](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV.apk), sur le téléphone | [Installer sur téléphone](guides/Telephone-tablette.md) |
| **Ordinateur Windows** 10 ou 11 | [Kit Windows](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV-Kit-Windows.zip) | [Installer sur Windows](guides/Windows.md) |

Chaque **kit** est un fichier `.zip` qui contient l'application **et son guide en PDF**, à suivre étape par
étape (celui de LG contient aussi le logiciel à installer sur l'ordinateur). Les liens donnent toujours la
dernière version.

**Pas encore disponible :** iPhone, iPad, Apple TV et Mac (en préparation).

Tous les guides et la FAQ dans un seul PDF, à imprimer si tu préfères le papier :
**[Guide-installation-CroissantTV-beta.pdf](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/Guide-installation-CroissantTV-beta.pdf)**

## 2. Une question ?

Les réponses aux questions les plus courantes sont dans la **[FAQ](FAQ.md)** : compatibilité, sécurité,
ajout de ton abonnement, coupures, mises à jour…

## 3. Un problème, une idée ?

- **Depuis l'application :** dans les **Paramètres**, « **Contacter le support** » affiche un QR code qui ouvre sur ton téléphone un e-mail déjà rempli avec les informations techniques de l'appareil.
- **Par e-mail :** **support@croissanttv.fr**.

Indique ton appareil (marque et modèle), la version de CroissantTV, ce que tu faisais et ce que tu as vu ;
une photo de l'écran aide beaucoup. Les idées et les remarques sont aussi les bienvenues !

---

## Nouveautés de la version 1.0.92

**La bêta arrive sur les TV Samsung et sur Windows.**

- **Profils** : l'écran « Qui regarde ? » fait peau neuve. Un pinceau sous chaque profil pour le personnaliser, et la création d'un profil en plein écran.
- **Sous-titres en ligne** : la recherche de sous-titres fonctionne de nouveau (elle ne marchait plus dans la 1.0.88).
- **Replay** : la fin d'une émission ne fait plus de retour en arrière, et la reprise est plus fluide.
- **Enregistrement** (Premium, Android TV et Windows) : enregistre une chaîne, ou programme un enregistrement depuis le guide des programmes.
- **Nouveaux épisodes** (Premium) : une pastille « Nouvelle saison » ou « Nouvel épisode » sur les séries.
- **Bande-annonce** : le bouton fonctionne de nouveau.
- **Clé USB** (Android) : sauvegarde et restauration de ta configuration dans un fichier.
- **Connexion libérée** : quand tu quittes CroissantTV sans l'arrêter, il coupe maintenant le flux. Ton abonnement est libre pour un autre appareil.
- **Profils protégés par un code** : ils se reverrouillent après 5 minutes passées hors de l'application.
- Et de nombreuses corrections : synchronisation des profils et des réglages entre appareils, épisode suivant, sport, traductions anglaise et espagnole.

**Tu as la 1.0.88 ?** Installe la 1.0.92 par-dessus, comme expliqué dans la partie « Mettre à jour » de ton
guide : tes sources, profils et réglages sont conservés.

**Ce qu'on aimerait que tu essaies en priorité :** l'installation elle-même (surtout sur Samsung et Windows),
l'écran « Qui regarde ? », le replay et, si tu as le Premium, l'enregistrement.

---

## Fichiers seuls (pour les habitués)

| Fichier | Pour |
|---|---|
| [CroissantTV.apk](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV.apk) | Android TV, Google TV, Fire TV (Fire OS), téléphones et tablettes Android 5 et plus |
| [CroissantTV-LG.ipk](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV-LG.ipk) | TV LG webOS 5 et plus, en mode développeur |
| [CroissantTV-Samsung.wgt](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV-Samsung.wgt) | TV Samsung Tizen 5.0 et plus, à signer pour ta TV (Apps2Samsung le fait) |
| [CroissantTV-Windows-Setup.exe](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV-Windows-Setup.exe) | Windows 10 et 11, 64 bits |

Toutes les versions et leurs empreintes SHA-256 : **[page des versions](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases)**.

Les logiciels tiers cités dans les guides appartiennent à leurs auteurs : [webOS Dev Manager](https://github.com/webosbrew/dev-manager-desktop)
(licence Apache 2.0, fourni dans le kit LG) et [Apps2Samsung](https://github.com/Apps2Samsung/Apps2Samsung) (licence MIT).
