# Vuln-Scanner 🔍

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Overview 📋

Vuln-Scanner è uno strumento open-source per il testing di sicurezza, progettato per aiutare i tester a individuare vulnerabilità comuni nelle applicazioni web. Il tool esegue la scansione di siti web alla ricerca di problemi come SQL Injection, Cross-Site Scripting (XSS), errori del server, File Inclusion, CSRF, header HTTP non sicuri e Directory Traversal. Inoltre, verifica la presenza di pannelli di login e analizza le porte aperte sul dominio target.

**Repository:** [https://github.com/L0THBROK/Vuln-Scanner](https://github.com/L0THBROK/Vuln-Scanner)

---

## Features 🚀

- **Scansione Web Completa:** Ricerca vulnerabilità comuni nei siti web.
- **Crawling Intelligente:** Esplora automaticamente i link interni per una scansione approfondita.
- **Port Scanning:** Individua le porte aperte del dominio target.
- **Output User-Friendly:** Messaggi colorati ed effetto "typewriter" per una migliore esperienza utente.
- **Design Modulare:** Facilmente estendibile per integrare ulteriori test di sicurezza.

---

## Requirements ⚙️

- **Python 3.x**
- [requests](https://pypi.org/project/requests/)
- [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
- [termcolor](https://pypi.org/project/termcolor/)

Per installare tutte le dipendenze, usa il file `requirements.txt`:

```bash
pip install -r requirements.txt