# Nemo

**Des pense-bêtes gratuits pour le bureau de Windows. Les notes sont enregistrées tout de suite sur ce PC et, une fois connecté, vous retrouvez les mêmes notes sur plusieurs PC et sur le web.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de différence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%207%20%2F%208%20%2F%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/nemo?lang=fr)

![Écran de Nemo](images/nemo-en.png)

## Présentation

Nemo vous permet de noter une idée sur une note et de la coller sur le bureau. Chaque note a un titre et un corps, et elle s'enregistre toute seule quand vous arrêtez de taper. Vous pouvez donner à chaque note sa couleur et l'épingler au-dessus des autres fenêtres ; sa position, sa taille et son épingle reviennent à l'identique au prochain lancement de Nemo.

Les notes sont **d'abord enregistrées sur ce PC** : vous pouvez donc utiliser Nemo sans vous connecter, et même sans connexion internet. Connectez-vous avec un compte Kilho.net et vos notes se synchronisent avec le serveur, pour voir et modifier les mêmes notes dans Nemo sur vos autres PC et dans [Web Memo](https://webmemo.kilho.net).

## Fonctionnalités

- **Notes sur le bureau** — les fenêtres de note n'encombrent ni la barre des tâches ni Alt+Tab, et restent sur le bureau quand vous fermez la fenêtre de liste.
- **Enregistrement automatique** — une note est enregistrée 3 secondes après la fin de la saisie, ou quand vous cliquez ailleurs. Il n'y a pas de bouton Enregistrer.
- **Se souvient de l'endroit où vous l'avez laissée** — position, taille, épingle et notes ouvertes sont mémorisées et restaurées au lancement suivant.
- **6 couleurs** — Par défaut · Jaune · Vert · Bleu · Violet · Rose. Dans la liste, chaque ligne prend la couleur de sa note : on les distingue d'un coup d'œil.
- **Toujours au premier plan** — une note épinglée n'est jamais cachée derrière d'autres fenêtres.
- **Recherche dans les notes** — la loupe de la fenêtre de liste cherche dans les titres et les corps.
- **Raccourci pour une nouvelle note** — appuyez sur **Ctrl+Shift+N** depuis n'importe quel programme pour ouvrir une nouvelle note. La touche peut être changée.
- **Fonctionne sans serveur** — la connexion est facultative. Quand vous vous déconnectez, les notes de ce PC restent.
- **Synchronisation entre PC et web** — une fois connecté, Nemo se synchronise avec le serveur 2 secondes après l'enregistrement, toutes les 10 minutes ou quand vous cliquez sur **Synchroniser**. Si la même note a été modifiée à deux endroits, aucune modification n'est perdue : les deux sont conservées, l'une en **copie en conflit**.
- **Connexion sécurisée par le navigateur** — vous ne saisissez jamais votre mot de passe dans Nemo. Vous vous connectez avec votre compte Kilho.net dans le navigateur que vous utilisez déjà (OAuth 2.0 + PKCE).
- **Emoji** — ajoutez des emoji dans les titres et les corps.
- **22 langues** — suit la langue d'affichage de Windows, ou choisissez-en une dans les Paramètres.

## Téléchargement / Installation

| Type | Lien |
|---|---|
| Programme d'installation | [Télécharger](https://down.kilho.net/nemo?lang=fr) |
| Portable (ZIP) | [Télécharger](https://down.kilho.net/nemo?lang=fr&nosetup) |

Une première installation avec le programme d'installation active **Lancer au démarrage**. Pour la version portable, décompressez le ZIP et lancez `Nemo.exe`. La version portable garde vos notes dans le même dossier que le programme : déplacer le dossier déplace vos notes avec lui.

## Utilisation

### Premiers pas

1. Lancez Nemo. La fenêtre de liste s'ouvre et une icône Nemo apparaît dans la zone de notification (barre d'état).
2. Faites un clic droit sur un espace vide de la liste ou sur l'icône de la zone de notification et choisissez **Nouvelle note**. (Vous pouvez aussi appuyer sur **Ctrl+Shift+N** n'importe où.)
3. La nouvelle note s'ouvre avec le champ de titre prêt. Tapez un titre et appuyez sur **Entrée** pour passer au corps.
4. Tapez le corps. Quand vous arrêtez de taper, la note est enregistrée 3 secondes plus tard et apparaît dans la liste.
5. Laissez la note où vous voulez sur le bureau. Faites glisser la barre de titre pour la déplacer et un bord pour la redimensionner.
6. Quand vous avez fini, cliquez sur le **✕** de la note. Elle est enregistrée et fermée. Pour la rouvrir, double-cliquez dessus dans la liste.

### Présentation de l'écran

**Fenêtre de liste**

| Élément | Description |
|---|---|
| Loupe (barre de titre) | Rechercher dans les notes. Cherche dans les titres et les corps ; **ÉCHAP** la ferme |
| Engrenage (barre de titre) | Paramètres |
| ✕ (barre de titre) | Cache la fenêtre de liste dans la zone de notification. Nemo continue de tourner |
| Liste des notes | Affichées dans l'ordre de création, chaque ligne dans la couleur de sa note. Double-cliquez pour ouvrir la note |
| Barre d'état, à gauche | **Notes : n** |
| Barre d'état, à droite — icône de nuage | Connexion au serveur. Survolez-la pour voir **Enregistré sur ce PC uniquement** · **Connecté au serveur (compte)** · **Dernière synchro** ; cliquez pour ouvrir la page **Serveur** des Paramètres |

**Fenêtre de note**

| Élément | Description |
|---|---|
| Barre de titre | Faites-la glisser pour déplacer la note. Cliquez deux fois sur le titre ou double-cliquez pour le renommer. Clic droit pour le menu de la note |
| Épingle | Active ou désactive **Toujours au premier plan**. Désactivée, elle apparaît barrée |
| ✕ | Enregistrer et fermer |
| Corps | Le texte de la note. Une barre de défilement apparaît quand la souris est dessus |
| Bords | Faites-les glisser pour redimensionner |

**Menu contextuel**

| Menu | Où | Rôle |
|---|---|---|
| **Nouvelle note** | Liste · Zone de notification | Ouvre une note vierge |
| **Liste** | Zone de notification (quand la fenêtre de liste est cachée) | Réaffiche la fenêtre de liste |
| **Modifier** | Liste (sur une note) · Barre de titre de la note | Ouvre la note / la renomme |
| **Supprimer** | Liste (sur une note) · Barre de titre de la note | Demande une fois, puis supprime |
| **Couleur ▸** | Liste (sur une note) · Barre de titre de la note | Choisissez l'une des 6 couleurs. Enregistré aussitôt |
| **Paramètres** | Liste · Zone de notification | Ouvre les Paramètres |
| **Kilho.net** | Liste · Zone de notification | Page de présentation de Nemo |
| **Quitter** | Liste · Zone de notification | Demande une fois, puis ferme Nemo. Les notes ouvertes reviennent au lancement suivant |

### Astuces pour les situations courantes

**Quand une idée vous vient en plein travail**
Même dans un autre programme, appuyez sur **Ctrl+Shift+N** et une nouvelle note s'affiche devant. Tapez un titre, appuyez sur Entrée, tapez le corps et laissez-la : elle s'enregistre toute seule.

**Quand vous voulez garder une note toujours visible**
Cliquez sur l'épingle de la note pour activer **Toujours au premier plan** ; les autres fenêtres ne la cacheront pas. Cliquez à nouveau pour désactiver. L'épingle est aussi restaurée au lancement suivant.

**Quand vos notes sont enfouies sous d'autres fenêtres**
Faites un clic gauche sur l'icône Nemo de la zone de notification pour ramener au premier plan toutes les notes ouvertes. La fenêtre de liste ne bouge pas. Si vous avez besoin de la fenêtre de liste, faites un clic droit sur l'icône et choisissez **Liste**.

**Quand vous voulez classer les notes par type**
Choisissez un code couleur : jaune pour les tâches, bleu pour le travail, etc. Faites un clic droit sur la barre de titre d'une note ou sur une note de la liste → **Couleur ▸**, et la note comme sa ligne dans la liste changent aussitôt de couleur.

**Quand vous avez trop de notes pour en retrouver une**
Cliquez sur la loupe dans la barre de titre de la fenêtre de liste et tapez ce que vous cherchez. Seules restent les notes qui contiennent ce texte dans le titre ou le corps. Appuyez sur **ÉCHAP** pour fermer la recherche et revoir toute la liste.

**Quand vous voulez seulement renommer une note**
Cliquez sur le titre de la note puis, un instant après, cliquez à nouveau (comme pour renommer un fichier dans l'Explorateur de fichiers), double-cliquez dessus, ou faites un clic droit sur la barre de titre → **Modifier**. **Entrée** valide, **Échap** rétablit l'ancien titre. Cliquer ailleurs conserve aussi ce que vous avez tapé.

**Quand vous voulez ranger la liste mais garder les notes**
Cliquez sur le **✕** de la fenêtre de liste ; elle passe dans la zone de notification et vos notes restent sur le bureau. Pour fermer complètement Nemo, choisissez **Quitter** dans le menu de la zone de notification.

**Les notes reviennent exactement où vous les avez laissées**
Même si vous éteignez Windows ou quittez Nemo avec des notes ouvertes, elles réapparaissent au même endroit et à la même taille au prochain lancement de Nemo. Si une note devait se retrouver hors de l'écran parce que la configuration des écrans a changé, elle est ramenée dans l'écran.

**Quand vous voulez voir vos notes à chaque démarrage du PC**
Activez **Lancer au démarrage** dans Paramètres → **Général** (c'est déjà activé avec le programme d'installation). Au démarrage de Windows, Nemo se lance discrètement dans la zone de notification sans la fenêtre de liste, et seules les notes laissées ouvertes apparaissent sur le bureau.

**Quand vous voulez les mêmes notes au bureau et à la maison**
Sur les deux PC, cliquez sur **Connexion** dans Paramètres → **Serveur**. Le navigateur s'ouvre ; connectez-vous avec votre compte Kilho.net et, quand la page « Connecté » s'affiche, fermez-la et revenez à Nemo. Dès lors, les notes se synchronisent seules 2 secondes après l'enregistrement et toutes les 10 minutes. Pour synchroniser tout de suite, cliquez sur **Synchroniser**.

**Quand vous êtes loin de votre PC**
Connectez-vous à [Web Memo](https://webmemo.kilho.net) avec le compte utilisé dans Nemo pour voir et modifier les mêmes notes. Les modifications faites sur le web arrivent dans les notes de Nemo à la synchronisation suivante.

**Quand la même note a été modifiée sur deux PC**
Rien n'est écrasé. Une version reste la note d'origine et l'autre devient une nouvelle note avec **(copie en conflit)** à la fin du titre. Comparez-les, fusionnez ce qu'il vous faut en une seule et supprimez l'autre.

**Quand vous avez déjà des notes d'avant la connexion**
À la connexion, les notes de ce PC montent vers ce compte et les notes du serveur descendent sur ce PC, le tout dans une seule liste. Si le PC a déjà été utilisé avec un autre compte, Nemo demande d'abord « Vous êtes connecté avec un autre compte. Fusionner les notes de ce PC avec ce compte ? » ; choisissez **Non** et Nemo ne se connecte pas.

**Quand vous voulez arrêter la synchronisation et garder les notes sur ce PC uniquement**
Cliquez sur **Déconnexion** dans Paramètres → **Serveur**. Les notes de ce PC restent, et la barre d'état passe à **Enregistré sur ce PC uniquement**. Les notes du serveur et de vos autres PC ne sont pas touchées.

**Quand vous n'avez pas internet**
Les notes sont toujours enregistrées d'abord sur ce PC : continuez à utiliser Nemo normalement. Une fois la connexion revenue, elles montent vers le serveur à la synchronisation suivante.

**Quand vous voulez un autre raccourci pour une nouvelle note**
Cliquez sur la case **Raccourci (nouvelle note)** dans Paramètres → **Général** ; elle affiche « Appuyez sur une touche ». Appuyez sur la combinaison voulue (par exemple Ctrl+Alt+M) et elle s'applique aussitôt. Si un autre programme utilise déjà cette touche, Nemo vous le signale : choisissez-en une autre.

**Quand vous voulez emporter Nemo sur une clé USB**
Décompressez la version portable sur la clé USB et lancez-la depuis la clé. Les notes sont enregistrées dans le même dossier : les mêmes notes s'ouvrent sur chaque PC où vous la branchez.

**Quand vous désinstallez puis réinstallez Nemo**
Désinstaller la version installée ne supprime pas vos notes. Réinstallez et vos notes sont toujours là.

**Quand vous éteignez Windows**
Nemo ne retarde jamais l'arrêt. Il enregistre les notes en cours et se ferme avec Windows.

**Quand vous relancez Nemo et ne voyez aucune fenêtre**
Une seule copie de Nemo tourne à la fois. Si vous le lancez alors qu'il tourne déjà, la fenêtre de liste sort de la zone de notification et passe au premier plan.

## Configuration

Ouvrez-la avec l'engrenage de la fenêtre de liste ou **Paramètres** dans le menu contextuel. Les changements s'appliquent aussitôt ; il n'y a pas de bouton OK.

| Page | Élément | Par défaut |
|---|---|---|
| Général | Lancer au démarrage | Activé avec le programme d'installation, désactivé en version portable |
| Général | Raccourci (nouvelle note) | Ctrl+Shift+N |
| Général | Langue | Système (langue d'affichage de Windows) |
| Serveur | Compte — Connexion / Déconnexion | Non connecté |
| Serveur | Synchronisation — heure de la dernière synchro, Synchroniser | Affiché uniquement une fois connecté |
| À propos | Version · Auteur · Site web · Licences | — |

Avec **Système**, la langue suit la langue d'affichage de Windows ; choisissez-en une dans la liste et elle change sur-le-champ. L'arabe s'affiche de droite à gauche.

## Configuration requise

- Windows 7 · 8 · 8.1 · 10 · 11 (32 bits · 64 bits)
- Aucun runtime supplémentaire nécessaire.
- Une connexion internet et un compte Kilho.net ne sont nécessaires que pour la synchronisation avec le serveur.

## Mises à jour

Nemo ne se met **pas** à jour tout seul. Au lancement, il vérifie si une nouvelle version existe et affiche un avis ; en appuyant sur **Oui**, la page de téléchargement s'ouvre et le programme se ferme. Les nouvelles versions sont publiées manuellement après vérification interne et annoncées sur la [page Nemo](https://kilho.net/nemo). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

## Licence

Nemo est un **freeware**. Vous pouvez l'utiliser gratuitement partout — au bureau, à la maison, dans les administrations ou à l'école — et le redistribuer librement.

## Liens

- Site web : <https://kilho.net/nemo>
- Page de Nemo : <https://nemo.kilho.net>
- Web Memo : <https://webmemo.kilho.net>
- Forum : <https://kilho.top/forum/qna>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
