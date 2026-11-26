# DeskCut

**[Français](#français) · [English](#english)**

---

## Français

DeskCut est un lanceur et tableau de bord pour Windows 11 : une fine colonne d'icônes au bord de
l'écran ouvre, dans un panneau, vos raccourcis, la surveillance de votre réseau, le suivi de votre
temps, vos tâches, vos notes et vos schémas. Le panneau s'ouvre aussi par un raccourci clavier ou depuis
la zone de notification, et certains modules s'ouvrent dans leur propre fenêtre. Le bouton « + » du
menu crée un raccourci, une tâche, une note ou un chrono depuis n'importe où, et la dictée écrit votre
texte dans n'importe quelle application, puis en garde l'historique.

Ce dépôt ne contient que les installeurs. Le code source n'est pas public.

### Télécharger

**[Télécharger la dernière version](https://github.com/manubg17/DeskCut-releases/releases/latest)**

Dans la page de la version, sous *Assets*, prenez le fichier qui se termine par **`_x64-setup.exe`**.

- **Configuration requise** : Windows 11 (64 bits). Aucun autre logiciel à installer.
- **Avertissement Windows** : l'installeur n'est pas signé par un certificat de code. Windows
  SmartScreen affiche donc « Windows a protégé votre ordinateur » : cliquez sur *Informations
  complémentaires*, puis *Exécuter quand même*.
- **Après l'installation** : la colonne d'icônes apparaît au bord droit de l'écran et DeskCut se loge
  dans la zone de notification. Le raccourci clavier `Ctrl+K` (modifiable dans les paramètres) ouvre
  les raccourcis.

### Mises à jour

DeskCut vérifie au démarrage si une nouvelle version existe et la propose dans
*Paramètres → Mises à jour*. Le téléchargement est vérifié par signature avant d'être installé.
Après chaque mise à jour, une fenêtre « Nouveautés » présente ce qui a changé ; le détail de chaque
version figure aussi sur la [page des versions](https://github.com/manubg17/DeskCut-releases/releases).

### Ce que fait DeskCut

| Module | En bref |
|---|---|
| **Raccourcis** | Lancer applications, sites web, sessions SSH et commandes système ; copier des textes prédéfinis. Catégories, épinglage, recherche au clavier. S'ouvre aussi dans sa propre fenêtre. |
| **Surveillance** | Vos sites web et adresses IP vérifiés en continu, même panneau fermé, avec une notification Windows en cas de panne et au rétablissement, et l'historique des pannes. Processeur, mémoire, disques, connexion Internet, latence, débit ; scan du réseau local avec historique, comparaison entre scans et schéma généré. S'ouvre aussi dans sa propre fenêtre. |
| **Journal** | Suivre son temps : chronomètre, entrées manuelles, client et projet, totaux du jour et de la semaine, export CSV. S'ouvre aussi dans sa propre fenêtre. |
| **Connaissances** | Commandes, extraits de code, procédures, liens : classés par type, copiés d'un clic. |
| **Tableaux** | Croquis à main levée et cartes mentales, ou diagrammes (organigrammes, UML, réseaux). Chaque tableau s'ouvre dans sa propre fenêtre et s'enregistre tout seul ; la liste des tableaux aussi. |
| **Tâches** | Tâches avec échéances et rappels, liées à vos notes et fichiers. S'ouvre aussi dans sa propre fenêtre. |
| **Notes** | Notes liées à vos tâches et fichiers. S'ouvre aussi dans sa propre fenêtre. |
| **Recherche** | Une recherche dans vos notes, vos tâches et le contenu de vos fichiers (PDF, Word, Excel…). |
| **Fichiers** | L'index des fichiers de vos dossiers, avec aperçu. |
| **Dictée** | Maintenir un raccourci, parler, relâcher : le texte est collé au curseur. La transcription est faite par votre propre serveur Whisper. Désactivée par défaut. Les dictées sont gardées dans un historique ; l'IA de votre choix (votre propre serveur, ou Claude avec votre clé) en tire un résumé, un rapport ou une liste de tâches. S'ouvre aussi dans sa propre fenêtre. |

L'interface est disponible en français et en anglais.

### Vos données

- **Tout est stocké sur votre ordinateur**, dans `%APPDATA%\deskcut\DeskCut\config`. DeskCut n'a pas
  de compte et n'envoie pas vos données sur un serveur.
- **Ce qui sort de votre poste**, et seulement cela : la recherche d'une mise à jour (ce dépôt), les
  vérifications que vous configurez vous-même (moniteurs, cibles de ping, scan de votre réseau), la
  lecture de votre adresse IP publique affichée dans la barre de titre, l'enregistrement de votre
  voix envoyé à votre propre serveur Whisper quand vous dictez, le texte des dictées que vous
  choisissez d'envoyer à l'IA (votre propre serveur, ou Anthropic si vous activez Claude avec votre
  clé), et les retours que vous choisissez d'envoyer.
- **Scan réseau** : il ne porte que sur des réseaux privés, dans la limite de 1 024 adresses, et ne
  démarre jamais seul. N'analysez que les réseaux que vous administrez ou pour lesquels vous avez
  une autorisation.

### Un problème, une idée ?

Utilisez le formulaire intégré : le bouton en forme de bulle en haut du panneau, à côté des
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

DeskCut is a launcher and dashboard for Windows 11: a slim column of icons at the edge of the screen
opens, in a panel, your shortcuts, the monitoring of your network, your time tracking, your tasks, your
notes and your diagrams. The panel also opens with a keyboard shortcut or from the notification area, and
some modules open in a window of their own. The "+" button of the menu creates a shortcut, a task, a note
or a timer from anywhere, and dictation writes your text in any application, then keeps a history of it.

This repository only holds the installers. The source code is not public.

### Download

**[Download the latest version](https://github.com/manubg17/DeskCut-releases/releases/latest)**

On the release page, under *Assets*, take the file ending in **`_x64-setup.exe`**.

- **Requirements**: Windows 11 (64-bit). Nothing else to install.
- **Windows warning**: the installer is not signed with a code-signing certificate, so Windows
  SmartScreen shows "Windows protected your PC": click *More info*, then *Run anyway*.
- **After installing**: the column of icons appears at the right edge of the screen and DeskCut sits in
  the notification area. The keyboard shortcut `Ctrl+K` (it can be changed in the settings) opens the
  shortcuts.

### Updates

DeskCut checks at startup whether a new version exists and offers it in *Settings → Updates*. The
download's signature is verified before it is installed. After each update, a "What's new" window
shows what changed; the details of every version are also on the
[releases page](https://github.com/manubg17/DeskCut-releases/releases).

### What DeskCut does

| Module | In short |
|---|---|
| **Shortcuts** | Launch applications, websites, SSH sessions and system commands; copy predefined texts. Categories, pinning, keyboard search. Also opens in a window of its own. |
| **Monitoring** | Your websites and IP addresses checked all the time, even with the panel closed, with a Windows notification when one goes down and when it is back, and the history of outages. CPU, memory, disks, Internet connection, latency, throughput; scan of the local network with history, comparison between scans and a generated diagram. Also opens in a window of its own. |
| **Journal** | Track your time: timer, manual entries, client and project, day and week totals, CSV export. Also opens in a window of its own. |
| **Knowledge** | Commands, code snippets, procedures, links: sorted by type, copied in one click. |
| **Boards** | Freehand sketches and mind maps, or diagrams (flowcharts, UML, networks). Each board opens in its own window and saves itself; so does the list of boards. |
| **Tasks** | Tasks with due dates and reminders, linked to your notes and files. Also opens in a window of its own. |
| **Notes** | Notes linked to your tasks and files. Also opens in a window of its own. |
| **Search** | One search across your notes, your tasks and the content of your files (PDF, Word, Excel…). |
| **Files** | The index of the files of your folders, with a preview. |
| **Dictation** | Hold a shortcut, speak, release: the text is pasted at the cursor. The transcription is done by your own Whisper server. Off by default. Dictations are kept in a history; the AI of your choice (your own server, or Claude with your key) turns them into a summary, a report or a task list. Also opens in a window of its own. |

The interface is available in French and in English.

### Your data

- **Everything is stored on your computer**, in `%APPDATA%\deskcut\DeskCut\config`. DeskCut has no
  account and does not send your data to a server.
- **What leaves your machine**, and only this: the update check (this repository), the checks you set
  up yourself (monitors, ping targets, the scan of your network), the lookup of your public IP
  address shown in the title bar, the recording of your voice sent to your own Whisper server when
  you dictate, the text of the dictations you choose to send to the AI (your own server, or Anthropic
  if you turn Claude on with your key), and the feedback you choose to send.
- **Network scan**: it only covers private networks, up to 1,024 addresses, and never starts by
  itself. Only scan networks you administer or have permission to scan.

### A problem, an idea?

Use the built-in form: the speech-bubble button at the top of the panel, next to the settings. No account is needed. The message is
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
