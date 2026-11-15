<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/Lang-🇬🇧_English-blue?style=for-the-badge" alt="English"></a>
  <a href="./README.fr.md"><img src="https://img.shields.io/badge/Lang-🇫🇷_Français-lightgrey?style=for-the-badge" alt="Français"></a>
</div>

# Mohamed

Computer Science engineering student at Sup Galilée (Université Sorbonne Paris Nord) and former R&D intern at LIPN (CNRS UMR 7030).

I focus on critical systems, DevSecOps, infrastructure, and edge AI, with hands-on work spanning containerized GPU/LLM backends, Linux hardening, embedded C/C++, and full-stack web engineering. Looking for an engineering apprenticeship starting in 2027.

## Core Stack

- **Systems & Infrastructure**: Linux, Docker, Docker Compose, Nginx, GitHub Actions
- **Languages**: C, C++, Python, TypeScript, PHP, Java, SQL
- **Backend & Data**: FastAPI, Next.js, Node.js, PostgreSQL, MySQL, Prisma

## Pinned Projects

- **[secure-gpu-upscaler](https://github.com/Git-MohamedB/secure-gpu-upscaler)** (`Python`, `FastAPI`, `PyTorch`, `Docker`)
  Hardened CUDA inference microservice built around Real-ESRGAN (x4plus anime 6B) to handle untrusted uploads safely: bounded 10 MB streaming, magic-bytes verification, Pillow lazy header checks against decompression bombs (> 2048x2048), FP16 VRAM-bounded 512x512 tiling, and a non-root container (`UID 10001`).

- **[mnemosyne](https://github.com/Git-MohamedB/mnemosyne)** (`PHP MVC`, `MySQL`, `JavaScript`)
  One-year academic analytics platform built for IUT de Villetaneuse (where I led core architecture and development): normalizes anonymized ScoDoc exports across 6 university departments, visualizes multi-year student cohort flows via Sankey diagrams, and exports PDF/JSON reports behind PDO prepared queries, CSRF tokens, and bcrypt auth.

- **[Sentinel](https://github.com/Git-MohamedB/Sentinel)** (`Python`, `Docker`, `Nginx`, `Ollama`)
  Two-stage local IDS/honeypot in Docker Compose: an exposed Nginx container logs requests while a Python watcher filters suspicious patterns with regex heuristics and queries a local `llama3:8b` model over Ollama to confirm threats and record banned IPs with automated summary reporting.

- **[Secure-IoT-Vault](https://github.com/Git-MohamedB/Secure-IoT-Vault)** (`C++`, `ESP32`, `IoT`)
  Cyber-physical access control proof of concept on ESP32 DevKit with a 4x4 matrix keypad, I2C 16x2 LCD, and SG90 servo lock: avoids plaintext PIN storage via FNV-1a digest checks, blocks brute-force attempts with a non-blocking 10 s `millis()` lockout after 3 failures, and emits serial audit logs.

- **[planifive](https://github.com/Git-MohamedB/planifive)** (`Next.js`, `TypeScript`, `Prisma`, `PostgreSQL`)
  Full-stack platform to organize 5-a-side football sessions without scattered group polls: players vote on weekly time slots, balanced teams are generated from technical/stamina scores, and Discord webhooks/bots automate match calls and MVP voting, alongside a zero-DB demo mode. ([Live demo](https://planifive.vercel.app/))

## Other Public Work

- **[BOTC](https://github.com/Git-MohamedB/BOTC)** (`TypeScript`, `Discord.js`, `Prisma`): Discord storyteller assistant for Blood on the Clocktower night queues, votes, and real-time Grimoire state.
- **[Jeu-Echecs-Java](https://github.com/Git-MohamedB/Jeu-Echecs-Java)** (`Java`): Object-oriented console chess engine with full move rules, captures, move history, and clock.

## Contact

- 🔗 [LinkedIn](https://www.linkedin.com/in/mohamedlink10n/)
