<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/Lang-🇬🇧_English-lightgrey?style=for-the-badge" alt="English"></a>
  <a href="./README.fr.md"><img src="https://img.shields.io/badge/Lang-🇫🇷_Français-blue?style=for-the-badge" alt="Français"></a>
</div>

# Mohamed

Élève-ingénieur en informatique à Sup Galilée (Université Sorbonne Paris Nord) et ancien stagiaire R&D au LIPN (CNRS UMR 7030).

Je travaille sur les systèmes critiques, le DevSecOps, l'infrastructure et l'IA embarquée/locale, entre services GPU/LLM conteneurisés, durcissement Linux, C/C++ simulé (Wokwi) et développement web fullstack. À la recherche d'une alternance ingénieur à partir de 2027.

## Stack Technique

- **Systèmes & Infrastructure** : Linux, Docker, Docker Compose, Nginx, GitHub Actions
- **Langages** : C, C++, Python, TypeScript, PHP, Java, SQL
- **Backend & Données** : FastAPI, Next.js, Node.js, PostgreSQL, MySQL, Prisma

## Projets Épinglés

- **[secure-gpu-upscaler](https://github.com/Git-MohamedB/secure-gpu-upscaler)** (`Python`, `FastAPI`, `PyTorch`, `Docker`)
  Microservice d'inférence GPU durci autour de Real-ESRGAN (x4plus anime 6B) conçu pour traiter des uploads non fiables : lecture streamée bornée à 10 Mo, validation par magic bytes, inspection paresseuse Pillow contre les decompression bombs (> 2048x2048), tuilage VRAM FP16 en 512x512 et exécution conteneur non-root (`UID 10001`).

- **[mnemosyne](https://github.com/Git-MohamedB/mnemosyne)** (`PHP MVC`, `MySQL`, `JavaScript`)
  Plateforme d'analyse de cohortes développée sur un an pour l'IUT de Villetaneuse (architecture MVC et développement principal) : importe et normalise des exports ScoDoc anonymisés sur 6 départements, trace les flux d'étudiants en diagrammes de Sankey et génère des exports PDF/JSON sécurisés (PDO préparé, jetons CSRF, bcrypt).

- **[Sentinel](https://github.com/Git-MohamedB/Sentinel)** (`Python`, `Docker`, `Nginx`, `Ollama`)
  IDS et honeypot local en deux étages sous Docker Compose : un serveur Nginx exposé journalise le trafic HTTP pendant qu'un watcher Python pré-filtre les motifs suspects par regex et sollicite `llama3:8b` via Ollama en local pour qualifier les attaques, journaliser les bannissements et générer des rapports.

- **[Secure-IoT-Vault](https://github.com/Git-MohamedB/Secure-IoT-Vault)** (`C++`, `Wokwi`, `Simulation ESP32`)
  Preuve de concept de contrôle d'accès conçue et exécutée en simulation sous Wokwi (ESP32 virtuel, clavier matriciel 4x4, écran LCD I2C 16x2, servomoteur SG90) : vérification du PIN par empreinte FNV-1a sans stockage en clair, verrouillage anti-bruteforce non bloquant de 10 s via `millis()` après 3 erreurs et traces d'audit sur port série.

- **[planifive](https://github.com/Git-MohamedB/planifive)** (`Next.js`, `TypeScript`, `Prisma`, `PostgreSQL`)
  Application fullstack d'organisation de matchs de futsal remplaçant les sondages manuels : votes sur créneaux hebdomadaires, génération d'équipes équilibrées selon niveau technique et cardio, synchronisation Discord (webhooks, bot, CRON) et mode démo isolé sans écriture en base. ([Démo en ligne](https://planifive.vercel.app/))

## Autres Dépôts Publics

- **[BOTC](https://github.com/Git-MohamedB/BOTC)** (`TypeScript`, `Discord.js`, `Prisma`) : Bot Discord d'aide au Conteur pour gérer l'ordre des nuits, les votes et le Grimoire sur Blood on the Clocktower.
- **[Jeu-Echecs-Java](https://github.com/Git-MohamedB/Jeu-Echecs-Java)** (`Java`) : Jeu d'échecs console en POO avec règles complètes, captures, historique et pendule.

## Contact

- 🔗 [LinkedIn](https://www.linkedin.com/in/mohamedlink10n/)
