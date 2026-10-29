# Installer CroissantTV sur un ordinateur Windows

[← Retour à l'accueil](../README.md) · [Questions fréquentes](../FAQ.md)

**Compte 5 minutes.** Il faut un ordinateur sous **Windows 10 ou Windows 11** (64 bits).

> [!NOTE]
> **Mac : pas encore.** La version pour Mac est en préparation.

> [!NOTE]
> **Pourquoi Windows affiche-t-il des avertissements ?** Windows se méfie de tout programme récent qui n'a
> pas encore de « signature numérique » payante d'éditeur. C'est le cas de CroissantTV pendant la bêta. Ces
> messages sont normaux tant que tu télécharges CroissantTV **depuis cette page et nulle part ailleurs**.

---

## Étape 1 — Télécharger

Télécharge l'un des deux, au choix :

- **[CroissantTV-Windows-Setup.exe](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV-Windows-Setup.exe)** : l'installeur seul (environ 90 Mo) ;
- **[CroissantTV-Kit-Windows.zip](https://github.com/thomasjanet60-spec/CroissantTV-beta/releases/latest/download/CroissantTV-Kit-Windows.zip)** : l'installeur et ce guide en PDF. Fais un clic droit dessus, **Extraire tout…**, **Extraire**.

Le navigateur peut prévenir que **« ce fichier n'est pas fréquemment téléchargé »** :

- **Edge :** passe la souris sur le message, clique sur les **trois points (…)**, puis **Conserver**, puis **Afficher plus**, puis **Conserver quand même** ;
- **Chrome :** clique sur **Conserver** (ou **Télécharger quand même**).

## Étape 2 — Installer

1. Double-clique sur **CroissantTV-Windows-Setup.exe** (dans **Téléchargements**, ou dans le dossier du kit sous le nom `3-CroissantTV-Windows-Setup.exe`).
2. Si Windows affiche **« Windows a protégé votre ordinateur »** : clique sur **Informations complémentaires**, puis sur **Exécuter quand même**.
3. Une **fenêtre noire** s'ouvre et installe CroissantTV : quelques secondes. Aucun droit d'administrateur n'est demandé.
4. Quand elle affiche **« Terminé. CroissantTV est installé. »**, appuie sur la touche <kbd>Entrée</kbd> pour la fermer.
5. Un raccourci **CroissantTV** t'attend **sur le bureau** et dans le **menu Démarrer**. Double-clique dessus.

Au premier lancement, CroissantTV te guide : il te demande ton abonnement IPTV, ou te propose la **démo** pour découvrir l'application sans abonnement.

> [!WARNING]
> **La fenêtre noire parle de « WebView2 introuvable » ?** CroissantTV a besoin de ce composant gratuit de
> Microsoft pour afficher son interface. Il est déjà présent sur Windows 11 et sur la plupart des Windows 10
> à jour. S'il manque, installe-le depuis
> **[la page officielle de Microsoft](https://go.microsoft.com/fwlink/p/?LinkId=2124703)**, puis relance CroissantTV.

## Utiliser CroissantTV au clavier et à la souris

CroissantTV a été pensé pour la télécommande ; sur ordinateur, le clavier la remplace :

| Télécommande | Clavier |
|---|---|
| Flèches | <kbd>←</kbd> <kbd>↑</kbd> <kbd>→</kbd> <kbd>↓</kbd> |
| OK | <kbd>Entrée</kbd> |
| Retour | <kbd>Échap</kbd> ou <kbd>Retour arrière</kbd> |
| Touches rouge, verte, jaune, bleue | <kbd>F1</kbd>, <kbd>F2</kbd>, <kbd>F3</kbd>, <kbd>F4</kbd> |
| Plein écran | <kbd>F11</kbd> |

La souris marche aussi : un clic pour choisir.

---

## Mettre à jour CroissantTV

Quand une nouvelle version est annoncée, télécharge le nouvel installeur (même lien) et lance-le comme la
première fois. Il ferme CroissantTV s'il est ouvert et remplace l'ancienne version. **Tes sources, profils
et réglages sont conservés.**

## Désinstaller CroissantTV

**Paramètres › Applications › Applications installées** (Windows 10 : **Applications et fonctionnalités**),
cherche **CroissantTV**, puis **Désinstaller**. Une fenêtre bleue (PowerShell) fait le ménage.

> [!CAUTION]
> La désinstallation efface aussi tes **sources, profils et réglages** enregistrés sur cet ordinateur.

## En cas de souci

| Ce que tu vois | Ce qu'il faut faire |
|---|---|
| « Windows a protégé votre ordinateur » sans bouton **Exécuter quand même** | Clique d'abord sur **Informations complémentaires** : le bouton apparaît en dessous. |
| « Le contrôle intelligent des applications a bloqué une application » (*Smart App Control*) | Ce réglage de Windows 11 bloque tout programme sans signature, sans exception. La version Windows ne peut donc pas s'installer sur ce PC pour l'instant. Ne désactive pas cette protection pour CroissantTV : dis-le-nous, cela nous aide à prioriser la signature. |
| Ton antivirus met le fichier en quarantaine | Les programmes récents et non signés déclenchent parfois une fausse alerte. Écris-nous avec le nom de l'antivirus et le message exact. |
| La fenêtre noire se ferme sur « L'installation a échoué » | Note le message affiché, ferme CroissantTV s'il est ouvert, et relance l'installeur. Si ça recommence, écris-nous avec ce message. |
| CroissantTV s'ouvre sur une fenêtre vide | Installe WebView2 (encadré de l'étape 2), puis relance CroissantTV. |

Toujours bloqué ? Écris-nous à **support@croissanttv.fr** en indiquant ta version de Windows et l'étape où tu
t'arrêtes ; une capture d'écran aide beaucoup. D'autres réponses dans les **[questions fréquentes](../FAQ.md)**.
