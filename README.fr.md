<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/Lang-🇬🇧_English-lightgrey?style=for-the-badge" alt="English"></a>
  <a href="./README.fr.md"><img src="https://img.shields.io/badge/Lang-🇫🇷_Français-blue?style=for-the-badge" alt="Français"></a>
</div>

# Mohamed

Élève-ingénieur en informatique à Sup Galilée (Université Sorbonne Paris Nord) et ancien stagiaire R&D au LIPN (CNRS UMR 7030).

Je travaille sur les systèmes critiques, le DevOps, le Cloud et le DevSecOps : microservices GPU/LLM durcis, pare-feu Linux/nftables, observabilité Prometheus, C/C++ simulé (Wokwi) et développement web fullstack. À la recherche d'un stage d'été de 2 mois en informatique (juillet - août 2027) et d'une alternance ingénieur à partir de septembre 2027.

## Stack Technique

- **Systèmes & Infrastructure** : Linux, Docker, Docker Compose, Nginx, nftables, Prometheus, Trivy, GitHub Actions
- **Langages** : Python, Go, TypeScript, C, C++, PHP, Java, SQL
- **Backend & Données** : FastAPI, Next.js 16, Node.js, PostgreSQL, MySQL, Prisma

## Projets Épinglés

- **[secure-gpu-upscaler](https://github.com/Git-MohamedB/secure-gpu-upscaler)** (`Python`, `FastAPI`, `PyTorch`, `Docker`, `Trivy`)
  Microservice d'inférence GPU durci autour de Real-ESRGAN (x4plus anime 6B) conçu pour traiter des uploads non fiables : lecture streamée bornée à 10 Mo, validation par magic bytes, inspection paresseuse Pillow contre les decompression bombs (> 2048x2048), vérification SHA-256 des poids, tuilage VRAM FP16 en 512x512, logs JSON structurés, conteneur non-root (`UID 10001`), tests API CI CPU et scan Trivy.

- **[mnemosyne](https://github.com/Git-MohamedB/mnemosyne)** (`PHP MVC`, `MySQL`, `JavaScript`)
  Plateforme d'analyse de cohortes développée sur un an pour l'IUT de Villetaneuse (architecture MVC et développement principal) : importe et normalise des exports ScoDoc anonymisés sur 6 départements, trace les flux d'étudiants en diagrammes de Sankey et génère des exports PDF/JSON sécurisés (PDO préparé, jetons CSRF, bcrypt).

- **[Sentinel](https://github.com/Git-MohamedB/Sentinel)** (`Go`, `Python`, `Docker`, `Nginx`, `nftables`, `Prometheus`, `Ollama`)
  Honeypot HTTP et IDS local durci sous Docker Compose : conteneur Nginx unprivileged en lecture seule exposant une surface leurre (suivi de rotation de logs), watcher Python avec file bornée, regex, logs JSON et analyse locale `llama3:8b` via Ollama (sans auto-bannissement sur verdict ambigu), et sidecar Go `firewall-agent` appliquant les bannissements `nftables` avec TTL et métriques Prometheus `/metrics`.

- **[Secure-IoT-Vault](https://github.com/Git-MohamedB/Secure-IoT-Vault)** (`C++`, `Wokwi`, `Simulation ESP32`)
  Preuve de concept de contrôle d'accès conçue et exécutée en simulation sous Wokwi (ESP32 virtuel, clavier matriciel 4x4, écran LCD I2C 16x2, servomoteur SG90) : empreinte FNV-1a sans PIN en clair ni fuite sur port série, verrouillage anti-bruteforce non bloquant de 10 s sûr au débordement `millis()` après 3 erreurs et traces d'audit série.

- **[planifive](https://github.com/Git-MohamedB/planifive)** (`Next.js 16`, `TypeScript`, `Prisma`, `PostgreSQL`)
  Application fullstack d'organisation de matchs de futsal : votes sur créneaux, équipes équilibrées, OAuth2 Discord fail-closed sur vérification de guilde, contrôles RBAC admin/auth, worker Discord signé HMAC, mode démo isolé sans BDD et CI TypeScript + Trivy. ([Démo en ligne](https://planifive.vercel.app/))

## Autres Dépôts Publics

- **[BOTC](https://github.com/Git-MohamedB/BOTC)** (`TypeScript`, `Discord.js`, `Prisma`) : Bot Discord d'aide au Conteur pour gérer l'ordre des nuits, les votes et le Grimoire sur Blood on the Clocktower.
- **[Jeu-Echecs-Java](https://github.com/Git-MohamedB/Jeu-Echecs-Java)** (`Java`) : Jeu d'échecs console en POO avec règles complètes, captures, historique et pendule.

## Contact

- 🔗 [LinkedIn](https://www.linkedin.com/in/mohamedlink10n/)
