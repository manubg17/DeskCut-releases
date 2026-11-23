# DeskCut

**[Français](#français) · [English](#english)**

---

## Français

DeskCut est un lanceur et tableau de bord pour Windows 11 : une petite fenêtre toujours à portée de
main, ouverte par un raccourci clavier ou depuis la zone de notification, qui regroupe vos raccourcis,
la surveillance de votre réseau, le suivi de votre temps, vos notes et vos schémas.

Ce dépôt ne contient que les installeurs. Le code source n'est pas public.

### Télécharger

**[Télécharger la dernière version](https://github.com/manubg17/DeskCut-releases/releases/latest)**

Dans la page de la version, sous *Assets*, prenez le fichier qui se termine par **`_x64-setup.exe`**.

- **Configuration requise** : Windows 11 (64 bits). Aucun autre logiciel à installer.
- **Avertissement Windows** : l'installeur n'est pas signé par un certificat de code. Windows
  SmartScreen affiche donc « Windows a protégé votre ordinateur » : cliquez sur *Informations
  complémentaires*, puis *Exécuter quand même*.
- **Après l'installation** : DeskCut se loge dans la zone de notification. Cliquez sur son icône, ou
  utilisez le raccourci clavier `Ctrl+K` (modifiable dans les paramètres).

### Mises à jour

DeskCut vérifie au démarrage si une nouvelle version existe et la propose dans
*Paramètres → Mises à jour*. Le téléchargement est vérifié par signature avant d'être installé.
Après chaque mise à jour, une fenêtre « Nouveautés » présente ce qui a changé ; le détail de chaque
version figure aussi sur la [page des versions](https://github.com/manubg17/DeskCut-releases/releases).

### Ce que fait DeskCut

| Module | En bref |
|---|---|
| **Raccourcis** | Lancer applications, sites web, sessions SSH et commandes système ; copier des textes prédéfinis. Catégories, épinglage, recherche au clavier. |
| **Moniteurs** | Vérifier périodiquement des sites web et des adresses IP, avec état et temps de réponse. |
| **Journal** | Suivre son temps : chronomètre, entrées manuelles, client et projet, export CSV. |
| **Connaissances** | Commandes, extraits de code, procédures, liens : classés par type, copiés d'un clic. |
| **NOC** | Processeur, mémoire, disques, connexion Internet, latence, débit. Scan du réseau local avec historique, comparaison entre scans et schéma généré. |
| **Tableaux** | Croquis à main levée et cartes mentales, ou diagrammes (organigrammes, UML, réseaux). Chaque tableau s'ouvre dans sa propre fenêtre et s'enregistre tout seul. |
| **Notes et fichiers** | Notes, tâches avec rappels, liens entre éléments, recherche dans le contenu de vos fichiers (PDF, Word, Excel…). |

L'interface est disponible en français et en anglais.

### Vos données

- **Tout est stocké sur votre ordinateur**, dans `%APPDATA%\deskcut\DeskCut\config`. DeskCut n'a pas
  de compte et n'envoie pas vos données sur un serveur.
- **Ce qui sort de votre poste**, et seulement cela : la recherche d'une mise à jour (ce dépôt), les
  vérifications que vous configurez vous-même (moniteurs, cibles de ping, scan de votre réseau), la
  lecture de votre adresse IP publique affichée dans la barre de titre, et les retours que vous
  choisissez d'envoyer.
- **Scan réseau** : il ne porte que sur des réseaux privés, dans la limite de 1 024 adresses, et ne
  démarre jamais seul. N'analysez que les réseaux que vous administrez ou pour lesquels vous avez
  une autorisation.

### Un problème, une idée ?

Utilisez le formulaire intégré : le bouton en forme de bulle dans la barre de titre, à côté des
paramètres. Aucun compte n'est
nécessaire. Le message est transmis à l'auteur ; il ne contient ni votre nom ni votre adresse, sauf
si vous les écrivez. Les informations techniques jointes (version de DeskCut, langue, version de
Windows) sont affichées avant l'envoi et peuvent être décochées.

### Licence et crédits

DeskCut n'est pas un logiciel libre : tous droits réservés. Vous pouvez le télécharger et l'utiliser ;
vous ne pouvez pas le redistribuer ni le modifier.

DeskCut embarque des logiciels libres, dont :

- l'éditeur de croquis [Excalidraw](https://github.com/excalidraw/excalidraw) (licence MIT) ;
- un éditeur de diagrammes basé sur [draw.io](https://github.com/jgraph/drawio) (licence Apache 2.0),
  dont les fichiers sont repris sans modification. « draw.io » est une marque déposée de JGraph Ltd ;
  DeskCut n'est ni affilié à JGraph ni approuvé par elle ;
- [Tauri](https://tauri.app) (licences MIT et Apache 2.0).

---

## English

DeskCut is a launcher and dashboard for Windows 11: a small window always within reach, opened with a
keyboard shortcut or from the notification area, that brings together your shortcuts, the monitoring
of your network, your time tracking, your notes and your diagrams.

This repository only holds the installers. The source code is not public.

### Download

**[Download the latest version](https://github.com/manubg17/DeskCut-releases/releases/latest)**

On the release page, under *Assets*, take the file ending in **`_x64-setup.exe`**.

- **Requirements**: Windows 11 (64-bit). Nothing else to install.
- **Windows warning**: the installer is not signed with a code-signing certificate, so Windows
  SmartScreen shows "Windows protected your PC": click *More info*, then *Run anyway*.
- **After installing**: DeskCut sits in the notification area. Click its icon, or use the keyboard
  shortcut `Ctrl+K` (it can be changed in the settings).

### Updates

DeskCut checks at startup whether a new version exists and offers it in *Settings → Updates*. The
download's signature is verified before it is installed. After each update, a "What's new" window
shows what changed; the details of every version are also on the
[releases page](https://github.com/manubg17/DeskCut-releases/releases).

### What DeskCut does

| Module | In short |
|---|---|
| **Shortcuts** | Launch applications, websites, SSH sessions and system commands; copy predefined texts. Categories, pinning, keyboard search. |
| **Monitors** | Check websites and IP addresses at regular intervals, with status and response time. |
| **Journal** | Track your time: timer, manual entries, client and project, CSV export. |
| **Knowledge** | Commands, code snippets, procedures, links: sorted by type, copied in one click. |
| **NOC** | CPU, memory, disks, Internet connection, latency, throughput. Scan of the local network with history, comparison between scans and a generated diagram. |
| **Boards** | Freehand sketches and mind maps, or diagrams (flowcharts, UML, networks). Each board opens in its own window and saves itself. |
| **Notes and files** | Notes, tasks with reminders, links between items, search inside your files (PDF, Word, Excel…). |

The interface is available in French and in English.

### Your data

- **Everything is stored on your computer**, in `%APPDATA%\deskcut\DeskCut\config`. DeskCut has no
  account and does not send your data to a server.
- **What leaves your machine**, and only this: the update check (this repository), the checks you set
  up yourself (monitors, ping targets, the scan of your network), the lookup of your public IP
  address shown in the title bar, and the feedback you choose to send.
- **Network scan**: it only covers private networks, up to 1,024 addresses, and never starts by
  itself. Only scan networks you administer or have permission to scan.

### A problem, an idea?

Use the built-in form: the speech-bubble button in the title bar, next to the settings. No account is needed. The message is
passed on to the author; it holds neither your name nor your address unless you write them. The
technical information attached (DeskCut version, language, Windows version) is shown before sending
and can be unticked.

### Licence and credits

DeskCut is not open-source software: all rights reserved. You may download and use it; you may not
redistribute or modify it.

DeskCut includes open-source software, among which:

- the [Excalidraw](https://github.com/excalidraw/excalidraw) sketch editor (MIT licence);
- a diagram editor based on [draw.io](https://github.com/jgraph/drawio) (Apache 2.0 licence), whose
  files are included unmodified. "draw.io" is a registered trademark of JGraph Ltd; DeskCut is not
  affiliated with or endorsed by JGraph;
- [Tauri](https://tauri.app) (MIT and Apache 2.0 licences).
