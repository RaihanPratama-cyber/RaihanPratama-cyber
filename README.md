# Raihan Pratama

Cyber Security student at Politeknik Caltex Riau — Teknologi Rekayasa Komputer, class 3 TRK A, Pekanbaru.

I build defensive security tools. Most of what I make comes from something I ran into in the lab: a phishing page, a flooded network, a website with no security headers. I rebuild it as a tool that explains what it found, with evidence, instead of just saying "dangerous".

## What I've built

| Project | What it does | Tests |
| --- | --- | --- |
| [phishing-url-detector-ai](https://github.com/RaihanPratama-cyber/phishing-url-detector-ai) | Checks a URL with 16 features, a rule engine and Logistic Regression, and explains the verdict. Catches the EC Council Lab 2 example `end-authenticat.tftpd.net` as phishing (62.1). | 6/6 |
| [phishing-email-analyzer](https://github.com/RaihanPratama-cyber/phishing-email-analyzer) | Reads a `.eml` file before you click anything in it: SPF/DKIM/DMARC, sender spoofing, link tricks, urgency language, dangerous attachments with SHA-256. Works fully offline. | 48/48 |
| [ai-skill-scanner](https://github.com/RaihanPratama-cyber/ai-skill-scanner) | Scans an AI agent skill from GitHub before you install it: credential theft, exfiltration, `curl \| bash`, obfuscated code, prompt injection. | 36/36 |
| [soc-dashboard-network-intrusion-detector](https://github.com/RaihanPratama-cyber/soc-dashboard-network-intrusion-detector) | SOC dashboard that detects MAC flooding, DHCP starvation, ARP poisoning and port scans, with alerts, logs and graphs. Built from my WKJ labs. | 18/18 |
| [web-vulnerability-scanner](https://github.com/RaihanPratama-cyber/web-vulnerability-scanner) | Scans a website for missing security headers, insecure cookies, reflected XSS, SQL error probes and exposed `.git` / `.env` files, with a risk score and fix advice. | 23/23 |
| [safe-inbox-guardian](https://github.com/RaihanPratama-cyber/safe-inbox-guardian) | Checks a NAS inbox for phishing-style files, explains the risk with evidence, and quarantines only what you approve. Built for the UGREEN Hackathon 2026 on AI NAS, Round 1 submitted. | 6/6 |
| [jagasehat](https://github.com/RaihanPratama-cyber/jagasehat) | Android app for family health monitoring: health records, reminders, articles, charts per family, report export. | — |

Every Flask project above runs locally with `pip install -r requirements.txt` and `python app.py`. No API keys, no paid services.

## Lab work behind these

- **Network security (WKJ):** MAC flooding with `macof`, DHCP starvation with `yersinia`, password sniffing in Wireshark, ARP poisoning with Cain & Abel and `hping3`.
- **Phishing & social engineering:** Social-Engineer Toolkit, phishing detection with the Netcraft extension, AI-assisted phishing simulation in a controlled lab.
- **Machine Learning for IoT:** image classification with MobileNetV2, audio classification, speech commands.
- **Big Data:** IoT air-quality monitoring in Pekanbaru — cleaning, MongoDB, analysis, Tableau dashboard.
- **Networks & CI/CD:** Git and GitHub, Docker, Jenkins pipelines.

## Tools I use

Python, Flask, scikit-learn · Kotlin, Jetpack Compose, Room · Wireshark · Docker, Jenkins · Git · MongoDB · MQTT, ESP32

---

If a tool can't explain why it flagged something, I don't trust it yet — so I build tools that can.
