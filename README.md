# Mohamed — Développeur Fullstack & Systèmes

Je construis surtout des applications web (TypeScript, PHP, Python), avec un vrai intérêt pour la sécurité applicative, Docker et les projets plus bas niveau.

### Projets principaux

* **[Planifive](https://github.com/Git-MohamedB/planifive)** · `Next.js` `TypeScript` `Prisma` `SQLite`
  Application web pour organiser des matchs de foot à 5 sans se perdre dans les sondages WhatsApp : chacun vote sur les créneaux de la semaine, les matchs passent à 10 joueurs automatiquement, et un algorithme compose deux équipes équilibrées selon le niveau technique et le cardio. Stats perso, MVP du mois et notifications Discord incluses — [démo en ligne](https://planifive.vercel.app/).

* **[Secure GPU Upscaler](https://github.com/Git-MohamedB/secure-gpu-upscaler)** · `Python` `FastAPI` `PyTorch` `Docker`
  Microservice d'upscaling d'images sur GPU pensé pour encaisser des requêtes non fiables : upload streamé plafonné à 10 Mo, contrôle des magic bytes, blocage des *decompression bombs* (> 2048×2048) avant décodage, tiling VRAM en FP16 et conteneur Docker rootless.

* **[Mnémosyne](https://github.com/Git-MohamedB/mnemosyne)** · `PHP MVC` `MySQL` `JavaScript` `Docker`
  Outil de suivi de cohortes BUT développé pour l'IUT de Villetaneuse (j'y ai assuré le développement principal). Permet d'importer les exports ScoDoc, de visualiser les passages d'une année à l'autre via des diagrammes de Sankey, de filtrer par promo ou dette et d'exporter des bilans en PDF/JSON.

* **[BOTC — Bot Discord](https://github.com/Git-MohamedB/BOTC)** · `TypeScript` `Discord.js` `Prisma` `SQLite`
  Outil pour aider le Conteur à animer des parties de *Blood on the Clocktower* sur Discord : déroule l'ordre des actions de nuit en messages privés, gère les votes et génère un Grimoire visuel mis à jour en temps réel.

* **[Sentinel](https://github.com/Git-MohamedB/Sentinel)** · `Python` `Docker` `Nginx` `Ollama`
  Petit système de détection d'intrusion monté en Docker : un serveur Nginx sert de leurre, un script Python filtre les requêtes suspectes dans les logs et les fait évaluer en local par Llama 3 pour bannir automatiquement les IP.

* **[Secure IoT Vault](https://github.com/Git-MohamedB/Secure-IoT-Vault)** · `C / C++` `ESP32`
  Preuve de concept de serrure connectée sur ESP32 (clavier matriciel 4×4, écran LCD, servomoteur) : le code PIN est vérifié via hachage FNV-1a sans stockage en clair, avec verrouillage de 10 secondes après 3 essais ratés.

---

### Autres projets

* **[Catastrophes climatiques (BDD)](https://github.com/Git-MohamedB/Base-De-Donnees-Catastrophes-Climatiques)** · `PostgreSQL` `SQL` — Nettoyage d'un jeu de données CSV et modélisation en schéma relationnel normalisé (5 tables).
* **[Jeu d'échecs console](https://github.com/Git-MohamedB/Jeu-Echecs-Java)** · `Java` — Projet universitaire en POO avec déplacements complets, captures, historique des coups et pendule.
* **[LoL Balancer](https://github.com/Git-MohamedB/lolbalancer)** · `JavaScript` — Petit outil web pour répartir des joueurs en équipes équilibrées selon leurs rôles.
* **[Visualiseur d'équations différentielles](https://github.com/Git-MohamedB/visualiseur-equation-differentielle)** · `HTML` `JavaScript` — Visualisation interactive et résolution numérique d'EDO dans le navigateur.

---

Le code de mon portfolio perso reste en privé pour l'instant, mais je peux montrer une démo sur demande.

* Contact : [LinkedIn](https://www.linkedin.com/in/mohamedlink10n/)
