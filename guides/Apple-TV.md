# Installer CroissantTV sur une Apple TV (prototype)

[← Retour à l'accueil](../README.md) · [Questions fréquentes](../FAQ.md)

> [!WARNING]
> **Version d'essai très limitée.** La version Apple TV est un **prototype** : elle lit une playlist M3U et
> affiche les chaînes en **direct**, c'est tout. Pas encore de connexion Xtream, de guide des programmes, de
> films et séries, de favoris ni de profils.

> [!IMPORTANT]
> **Ce guide n'a pas encore été suivi jusqu'au bout sur une vraie Apple TV.** L'application a été essayée
> dans le simulateur Apple TV de Xcode (version 1.0.99, 07/11/2026). L'appairage, la signature avec un
> identifiant Apple gratuit et l'installation sur l'appareil sont décrits d'après la documentation d'Apple
> et marqués *(pas encore essayé)*. Si tu les suis, dis-nous ce que tu vois vraiment.

**Pourquoi c'est plus long que sur les autres appareils ?** Une Apple TV n'installe **aucune** application
non signée : il n'existe pas de fichier à télécharger puis ouvrir, comme sur un Mac ou une TV Android.
L'application doit être **compilée sur ton Mac, puis signée avec ton propre identifiant Apple**. Un
identifiant Apple gratuit suffit, avec ces limites fixées par Apple :

| Limite d'un identifiant Apple gratuit | Ce que ça veut dire pour toi |
|---|---|
| L'application expire **7 jours** après son installation | Elle ne s'ouvre plus : il faut refaire l'étape 4 chaque semaine |
| **3 applications** au plus par appareil | Si tu installes déjà 3 applications de cette façon, il faut en retirer une |
| **10 identifiants d'application** par semaine | Sans effet si tu n'installes que CroissantTV |
| **3 appareils** au plus | L'Apple TV en compte un |

---

## Ce qu'il te faut

- un **Mac** avec **Xcode** (gratuit, sur l'App Store, environ 10 Go) ;
- un **identifiant Apple** (celui de ton iPhone convient, aucun abonnement n'est demandé) ;
- une **Apple TV 4K ou HD** sur le **même réseau Wi-Fi** que le Mac ;
- une connexion Internet : Xcode télécharge la bibliothèque de lecture vidéo à la première compilation.

## Étape 1 — Télécharger le kit

Télécharge **CroissantTV-Kit-AppleTV.zip** et double-clique dessus : un dossier
**CroissantTV-Kit-AppleTV** s'ouvre. Il contient ce guide en PDF, le projet Xcode et le script
`installer-appletv.sh`.

## Étape 2 — Ajouter ton identifiant Apple dans Xcode *(pas encore essayé)*

1. Ouvre **Xcode**. La première fois, accepte la licence et laisse-le installer ses composants ; quand il
   le propose, coche **tvOS** pour télécharger aussi le nécessaire Apple TV.
2. Menu **Xcode › Settings…** (ou **Réglages…**), onglet **Accounts** (**Comptes**), bouton **+** en bas à
   gauche, **Apple ID**, puis connecte-toi.
3. Ton compte apparaît avec une équipe nommée **« (ton nom) (Personal Team) »**. Clique sur
   **Manage Certificates…** puis **+** › **Apple Development** si la liste est vide.
4. Il te faut le **Team ID** de cette équipe : 10 lettres et chiffres. Pour le lire, ouvre l'application
   **Terminal** (dans Applications › Utilitaires) et colle :

   ```
   security find-certificate -c "Apple Development" -p | openssl x509 -noout -subject
   ```

   Le Team ID est la valeur après `OU=`.

## Étape 3 — Appairer l'Apple TV avec le Mac *(pas encore essayé)*

1. Sur l'Apple TV : **Réglages › Télécommandes et appareils › Application Télécommande et appareils**.
   Reste sur cet écran.
2. Sur le Mac, dans Xcode : menu **Window › Devices and Simulators**. L'Apple TV apparaît à gauche :
   clique dessus, puis **Pair**.
3. Un code à 6 chiffres s'affiche sur la TV : tape-le sur le Mac.

## Étape 4 — Installer CroissantTV

1. Dans le Terminal, va dans le dossier du kit. Tape `cd ` (avec l'espace), fais glisser le dossier
   **CroissantTV-Kit-AppleTV** dans la fenêtre du Terminal, puis appuie sur <kbd>Entrée</kbd>.
2. Lance le script avec ton Team ID :

   ```
   bash installer-appletv.sh TONTEAMID
   ```

   La première compilation prend plusieurs minutes. À la fin, le script affiche la liste des Apple TV
   appairées *(pas encore essayé)*.
3. Relance-le en ajoutant le nom de ton Apple TV, tel qu'il apparaît dans cette liste :

   ```
   bash installer-appletv.sh TONTEAMID "Apple TV du salon"
   ```

   CroissantTV s'installe et s'ouvre sur la TV *(pas encore essayé)*.

**Si le script affiche :**

| Message | Que faire |
|---|---|
| « Xcode introuvable » | Xcode n'est pas installé, ou le Mac ne le trouve pas : tape la commande `sudo xcode-select -s …` que le script affiche (avec le chemin de ton Xcode s'il n'est pas dans Applications), puis ton mot de passe |
| « No Accounts » ou « No profiles for… » | L'identifiant Apple n'est pas encore ajouté dans Xcode : refais l'étape 2 |

**Si le script n'arrive pas à installer :** double-clique sur **CroissantTV.xcodeproj** (si le Mac
prévient que le projet vient d'Internet, confirme l'ouverture). Dans Xcode, clique
sur **CroissantTV** en haut de la colonne de gauche, onglet **Signing & Capabilities** : choisis ton équipe
**Personal Team** dans **Team**, et remplace le **Bundle Identifier** par
`com.croissanttv.app.` suivi de ton Team ID en minuscules. En haut de la fenêtre, choisis ton Apple TV comme
destination, puis menu **Product › Run** *(pas encore essayé)*.

## Étape 5 — Chaque semaine

Au bout de 7 jours, CroissantTV ne s'ouvre plus sur l'Apple TV : c'est la limite d'un identifiant Apple
gratuit. Refais l'**étape 4** (l'Apple TV reste appairée, la compilation est plus rapide la deuxième
fois). Ta playlist devrait rester enregistrée *(pas encore essayé)*.

## Utiliser CroissantTV sur l'Apple TV

- À la première ouverture, saisis l'adresse de ta playlist M3U avec la télécommande, puis **Charger**.
  **Liste de démonstration** montre quelques chaînes publiques, sans rien enregistrer.
- Navigue entre les catégories et les chaînes avec la télécommande, appuie au centre pour lire.
- Pendant la lecture : **▲ / ▼** pour changer de chaîne, **⏯** pour la pause, **Menu** ou **‹** pour
  revenir à la liste.

## Désinstaller CroissantTV

Sur l'écran d'accueil de l'Apple TV, sélectionne CroissantTV, **appuie longuement au centre** de la
télécommande, puis choisis **Supprimer**.
