# DeskCut

**[FranÃ§ais](#franÃ§ais) Â· [English](#english)**

---

## FranÃ§ais

DeskCut est un lanceur et tableau de bord pour Windows 11 : une petite fenÃªtre toujours Ã  portÃ©e de
main, ouverte par un raccourci clavier ou depuis la zone de notification, qui regroupe vos raccourcis,
la surveillance de votre rÃ©seau, le suivi de votre temps, vos notes et vos schÃ©mas.

Ce dÃ©pÃ´t ne contient que les installeurs. Le code source n'est pas public.

### TÃ©lÃ©charger

**[TÃ©lÃ©charger la derniÃ¨re version](https://github.com/manubg17/DeskCut-releases/releases/latest)**

Dans la page de la version, sous *Assets*, prenez le fichier qui se termine par **`_x64-setup.exe`**.

- **Configuration requise** : Windows 11 (64 bits). Aucun autre logiciel Ã  installer.
- **Avertissement Windows** : l'installeur n'est pas signÃ© par un certificat de code. Windows
  SmartScreen affiche donc Â« Windows a protÃ©gÃ© votre ordinateur Â» : cliquez sur *Informations
  complÃ©mentaires*, puis *ExÃ©cuter quand mÃªme*.
- **AprÃ¨s l'installation** : DeskCut se loge dans la zone de notification. Cliquez sur son icÃ´ne, ou
  utilisez le raccourci clavier `Ctrl+K` (modifiable dans les paramÃ¨tres).

### Mises Ã  jour

DeskCut vÃ©rifie au dÃ©marrage si une nouvelle version existe et la propose dans
*ParamÃ¨tres â†’ Mises Ã  jour*. Le tÃ©lÃ©chargement est vÃ©rifiÃ© par signature avant d'Ãªtre installÃ©.
AprÃ¨s chaque mise Ã  jour, une fenÃªtre Â« NouveautÃ©s Â» prÃ©sente ce qui a changÃ© ; le dÃ©tail de chaque
version figure aussi sur la [page des versions](https://github.com/manubg17/DeskCut-releases/releases).

### Ce que fait DeskCut

| Module | En bref |
|---|---|
| **Raccourcis** | Lancer applications, sites web, sessions SSH et commandes systÃ¨me ; copier des textes prÃ©dÃ©finis. CatÃ©gories, Ã©pinglage, recherche au clavier. |
| **Moniteurs** | VÃ©rifier pÃ©riodiquement des sites web et des adresses IP, avec Ã©tat et temps de rÃ©ponse. |
| **Journal** | Suivre son temps : chronomÃ¨tre, entrÃ©es manuelles, client et projet, export CSV. |
| **Connaissances** | Commandes, extraits de code, procÃ©dures, liens : classÃ©s par type, copiÃ©s d'un clic. |
| **NOC** | Processeur, mÃ©moire, disques, connexion Internet, latence, dÃ©bit. Scan du rÃ©seau local avec historique, comparaison entre scans et schÃ©ma gÃ©nÃ©rÃ©. |
| **Tableaux** | Croquis Ã  main levÃ©e et cartes mentales, ou diagrammes (organigrammes, UML, rÃ©seaux). Chaque tableau s'ouvre dans sa propre fenÃªtre et s'enregistre tout seul. |
| **Notes et fichiers** | Notes, tÃ¢ches avec rappels, liens entre Ã©lÃ©ments, recherche dans le contenu de vos fichiers (PDF, Word, Excelâ€¦). |

L'interface est disponible en franÃ§ais et en anglais.

### Vos donnÃ©es

- **Tout est stockÃ© sur votre ordinateur**, dans `%APPDATA%\deskcut\DeskCut\config`. DeskCut n'a pas
  de compte et n'envoie pas vos donnÃ©es sur un serveur.
- **Ce qui sort de votre poste**, et seulement cela : la recherche d'une mise Ã  jour (ce dÃ©pÃ´t), les
  vÃ©rifications que vous configurez vous-mÃªme (moniteurs, cibles de ping, scan de votre rÃ©seau), la
  lecture de votre adresse IP publique affichÃ©e dans la barre de titre, et les retours que vous
  choisissez d'envoyer.
- **Scan rÃ©seau** : il ne porte que sur des rÃ©seaux privÃ©s, dans la limite de 1 024 adresses, et ne
  dÃ©marre jamais seul. N'analysez que les rÃ©seaux que vous administrez ou pour lesquels vous avez
  une autorisation.

### Un problÃ¨me, une idÃ©e ?

Utilisez le formulaire intÃ©grÃ© : *ParamÃ¨tres â†’ Mises Ã  jour â†’ Envoyer un retour*. Aucun compte n'est
nÃ©cessaire. Le message est transmis Ã  l'auteur ; il ne contient ni votre nom ni votre adresse, sauf
si vous les Ã©crivez. Les informations techniques jointes (version de DeskCut, langue, version de
Windows) sont affichÃ©es avant l'envoi et peuvent Ãªtre dÃ©cochÃ©es.

### Licence et crÃ©dits

DeskCut n'est pas un logiciel libre : tous droits rÃ©servÃ©s. Vous pouvez le tÃ©lÃ©charger et l'utiliser ;
vous ne pouvez pas le redistribuer ni le modifier.

DeskCut embarque des logiciels libres, dont :

- l'Ã©diteur de croquis [Excalidraw](https://github.com/excalidraw/excalidraw) (licence MIT) ;
- un Ã©diteur de diagrammes basÃ© sur [draw.io](https://github.com/jgraph/drawio) (licence Apache 2.0),
  dont les fichiers sont repris sans modification. Â« draw.io Â» est une marque dÃ©posÃ©e de JGraph Ltd ;
  DeskCut n'est ni affiliÃ© Ã  JGraph ni approuvÃ© par elle ;
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

DeskCut checks at startup whether a new version exists and offers it in *Settings â†’ Updates*. The
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
| **Notes and files** | Notes, tasks with reminders, links between items, search inside your files (PDF, Word, Excelâ€¦). |

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

Use the built-in form: *Settings â†’ Updates â†’ Send feedback*. No account is needed. The message is
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
