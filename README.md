<div align="right">
  <a href="./README.md"><img src="https://img.shields.io/badge/Lang-🇬🇧_English-blue?style=for-the-badge" alt="English"></a>
  <a href="./README.fr.md"><img src="https://img.shields.io/badge/Lang-🇫🇷_Français-lightgrey?style=for-the-badge" alt="Français"></a>
</div>

# Mohamed

Computer Science engineering student at Sup Galilée (Université Sorbonne Paris Nord) and former R&D intern at LIPN (CNRS UMR 7030).

I focus on critical systems, DevOps, Cloud, and DevSecOps, with hands-on work spanning hardened GPU/LLM services, Linux/nftables firewalling, Prometheus observability, simulated embedded C/C++ (Wokwi), and full-stack web engineering. Looking for a 2-month IT summer internship (July - August 2027) and an engineering apprenticeship starting September 2027.

## Core Stack

- **Systems & Infrastructure**: Linux, Docker, Docker Compose, Nginx, nftables, Prometheus, Trivy, GitHub Actions
- **Languages**: Python, Go, TypeScript, C, C++, PHP, Java, SQL
- **Backend & Data**: FastAPI, Next.js 16, Node.js, PostgreSQL, MySQL, Prisma

## Pinned Projects

- **[secure-gpu-upscaler](https://github.com/Git-MohamedB/secure-gpu-upscaler)** (`Python`, `FastAPI`, `PyTorch`, `Docker`, `Trivy`)
  Hardened CUDA inference microservice built around Real-ESRGAN (x4plus anime 6B) to handle untrusted uploads safely: bounded 10 MB streaming, magic-bytes verification, Pillow lazy header checks against decompression bombs (> 2048x2048), SHA-256 model weight verification, FP16 VRAM-bounded 512x512 tiling, structured JSON logs, non-root container (`UID 10001`), CPU API CI tests, and Trivy scans.

- **[mnemosyne](https://github.com/Git-MohamedB/mnemosyne)** (`PHP MVC`, `MySQL`, `JavaScript`)
  One-year academic analytics platform built for IUT de Villetaneuse (where I led core architecture and development): normalizes anonymized ScoDoc exports across 6 university departments, visualizes multi-year student cohort flows via Sankey diagrams, and exports PDF/JSON reports behind PDO prepared queries, CSRF tokens, and bcrypt auth.

- **[Sentinel](https://github.com/Git-MohamedB/Sentinel)** (`Go`, `Python`, `Docker`, `Nginx`, `nftables`, `Prometheus`, `Ollama`)
  Hardened local HTTP honeypot and IDS in Docker Compose: an unprivileged read-only Nginx container logs HTTP traffic (with rotation tracking) while a Python watcher applies regex pre-filtering, bounded async queuing, structured JSON logs, and local `llama3:8b` analysis over Ollama (failing safe on ambiguous verdicts), paired with a Go `firewall-agent` sidecar enforcing `nftables` TTL bans and exposing Prometheus `/metrics`.

- **[Secure-IoT-Vault](https://github.com/Git-MohamedB/Secure-IoT-Vault)** (`C++`, `Wokwi`, `Simulated ESP32`)
  Access-control proof of concept built and simulated on Wokwi (virtual ESP32 DevKit with 4x4 matrix keypad, I2C 16x2 LCD, and SG90 servo): avoids plaintext PIN storage and redacts serial PIN output via FNV-1a digest checks, blocks brute-force attempts with a rollover-safe non-blocking 10 s `millis()` lockout after 3 failures, and emits serial audit logs.

- **[planifive](https://github.com/Git-MohamedB/planifive)** (`Next.js 16`, `TypeScript`, `Prisma`, `PostgreSQL`)
  Full-stack platform to organize 5-a-side football sessions without scattered group polls: weekly slot voting, balanced teams from technical/stamina scores, hardened Discord OAuth2 (fail-closed guild check), RBAC admin/auth guards, HMAC-signed Discord worker requests, zero-DB demo mode, and TypeScript/Trivy CI. ([Live demo](https://planifive.vercel.app/))

## Other Public Work

- **[BOTC](https://github.com/Git-MohamedB/BOTC)** (`TypeScript`, `Discord.js`, `Prisma`): Discord storyteller assistant for Blood on the Clocktower night queues, votes, and real-time Grimoire state.
- **[Jeu-Echecs-Java](https://github.com/Git-MohamedB/Jeu-Echecs-Java)** (`Java`): Object-oriented console chess engine with full move rules, captures, move history, and clock.

## Contact

- 🔗 [LinkedIn](https://www.linkedin.com/in/mohamedlink10n/)
