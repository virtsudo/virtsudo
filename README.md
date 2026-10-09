# Bekhzod Anvarov

**Cybersecurity & Machine Learning Graduate — Politecnico di Torino**  
Self-supervised learning (JEPA) · Network intrusion detection

📍 Turin, Italy · 📬 virtsudo@proton.me · [LinkedIn](https://www.linkedin.com/in/virtsudo)

---

## About

Computer Engineering graduate (MSc, Cybersecurity track) from Politecnico di Torino, working where security meets deep learning. My thesis applied a Joint-Embedding Predictive Architecture (JEPA) to network intrusion detection, testing on real backbone traffic how self-supervised representations hold up as traffic drifts over the years. I also build across the stack — bare-metal C and ARM assembly, Rust/Tauri desktop apps, full-stack web — with 5+ years of Python.

**Focus:** Deep learning for anomaly detection · Self-supervised learning (JEPA) · Network intrusion detection · Post-quantum cryptography · Penetration testing

**Open to:** junior roles · research collaborations in cybersecurity and ML · remote-friendly teams

---

## Master's thesis

**JEPA Representation Learning for Intrusion Detection on Real-World Drifting Network Traffic**  
Politecnico di Torino, 2026 · Supervisors: Prof. Guido Marchetto, Prof. Alessio Sacco, Cristiano Serra, MSc

> Does a representation learned from unlabeled network traffic hold up better than raw flow features when an intrusion classifier meets traffic recorded years later?

- **Built** the full pipeline in Python: preprocessing, a self-supervised JEPA model in PyTorch trained on unlabeled network traffic, classifiers and evaluation. Replaced the benchmark's scaling, which erased most of the detail in the flow features.
- **Tested** on real Internet backbone traffic from 2011, 2016 and 2021 (MAWIFlow benchmark): four classifiers, from logistic regression to XGBoost, trained on each year and tested on every year, once on raw flow features and once on the learned representation.
- **Found** that the representation makes anomalous traffic easier to separate with a simple linear model, but does not reduce the performance drop across years; between 2011 and the later years the labels changed meaning, not the traffic. Also found that the benchmark's published metrics contradict its published samples for two of the three years.

**Stack:** Python · PyTorch (CUDA) · scikit-learn · XGBoost · Polars · NumPy · Matplotlib

---

## Tech stack

**Programming**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java/Kotlin](https://img.shields.io/badge/Java%2FKotlin_%28Android%29-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![JavaScript/TypeScript](https://img.shields.io/badge/JavaScript%2FTypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![ARM Assembly](https://img.shields.io/badge/ARM_Assembly_%28Cortex--M3%29-0091BD?style=flat-square&logo=arm&logoColor=white)

**Machine learning**  
![PyTorch](https://img.shields.io/badge/PyTorch_%28CUDA%29-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Security tools**  
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4CAF50?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)

**Databases, tools & environments**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_shell-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![JetBrains](https://img.shields.io/badge/JetBrains_IDEs-000000?style=flat-square&logo=jetbrains&logoColor=white)

---

## Projects

| Repo | What it is | Stack |
|------|-----------|-------|
| [dl-cybersecurity-labs](https://github.com/virtsudo/dl-cybersecurity-labs) | Three labs: an FFNN for network intrusion detection; FFNN, RNN and GNN models for malware classification; BERT fine-tuning for SSH log analysis and MITRE ATT&CK tactic tagging | Python · PyTorch · Jupyter · Hugging Face |
| [rust-rescuing-surplus-food](https://github.com/virtsudo/rust-rescuing-surplus-food) | Cross-platform desktop app with a Rust backend and React frontend: browse establishments, reserve surplus food bags, schedule pickups — no Node.js server | Rust (Tauri v2) · React · TypeScript · SQLite |
| [arm-pacman-game](https://github.com/virtsudo/arm-pacman-game) | Bare-metal Pac-Man on the LandTiger board, no OS or framework: GPIO joystick input, interrupt-driven pause/resume, pixel-level rendering on the 240×320 LCD | C · ARM Cortex-M3 Assembly · LPC1768 |
| [reactjs-rescuing-surplus-food](https://github.com/virtsudo/reactjs-rescuing-surplus-food) | Full-stack SPA with session-based authentication, a RESTful API and a two-server architecture | React · TypeScript · Node.js · Express · SQLite · Passport.js |

---

## Education

| Degree | Institution | Period |
|--------|------------|--------|
| MSc Computer Engineering — Cybersecurity track | Politecnico di Torino | 2022 – 2026 |
| BSc Computer Engineering | Politecnico di Torino | 2019 – 2022 |

**MSc coursework:** AI and cybersecurity (deep learning, deep NLP, anomaly detection, traffic classification) · Security verification and testing (vulnerability assessment, penetration testing, static analysis, formal protocol verification) · Information systems security (PKI, IPsec, firewalls and IDS, VPNs, TLS, SSH) · Cybersecurity (SAML/OIDC, trusted execution environments, forensics) · Cryptography (AES, RSA, SHA-3, ECDH) · Post-quantum cryptography (lattice-, code- and hash-based, NIST standards) · Computer network technologies

**Languages:** Uzbek (native) · Russian (C1) · English (B2) · Italian (B1)

---

## Activity

[![GitHub followers](https://img.shields.io/github/followers/virtsudo?style=flat-square&label=Followers)](https://github.com/virtsudo?tab=followers)
[![GitHub stars](https://img.shields.io/github/stars/virtsudo?style=flat-square&label=Total%20stars)](https://github.com/virtsudo?tab=repositories)

---

*Open to junior roles and research collaborations in cybersecurity and ML. Remote-friendly.*
