# 🔥 Firewall ACL Lab — MLA Tech

[![Live Demo](https://img.shields.io/badge/Live%20Demo-mohammadlotfi.com-f0c93a?style=flat-square&logo=google-chrome&logoColor=black)](https://mohammadlotfia.github.io/firewall-lab/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](./LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-181717?style=flat-square&logo=github)](https://pages.github.com)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-blue?style=flat-square)

An **interactive, browser-based firewall ACL simulator** built for students preparing for cybersecurity and networking certifications. Configure Access Control List rules in a realistic lab environment — no installation, no backend, no account required.

> **Primary target:** CompTIA Security+  
> **Also covers:** CCNA · Network+ · CySA+

---

## 🎯 What Is This?

This lab teaches you how firewalls evaluate traffic by making you *write the rules yourself*. Each scenario gives you a real-world ticket (connectivity issue, malware outbreak, server hardening request) and asks you to build the correct ACL policy from scratch.

You must know — or look up — the correct port number and protocol for each service. The lab deliberately withholds that information from the main view so that recalling `SSH = TCP/22` or `DNS = UDP/53` becomes second nature, exactly the way exam questions are written.

---

## ✨ Features

- **5 difficulty levels** — from single host-to-host rules up to full DMZ segmentation policy
- **Randomised scenarios** — IPs, services, and targets change every time you generate a new scenario
- **Gated hints** — port and protocol info is hidden behind a "Show Intel" button, preserving the learning challenge
- **Instant verification** — the checker highlights incorrect rows in red and lists missing rules by name
- **Solution reveal** — shows the correct ACL with a full protocol explanation (TCP vs UDP rationale)
- **Rule priority controls** — move rules up/down to understand first-match firewall logic
- **Dark / Light theme** — toggle with a single click, preference persists for the session
- **Fully responsive** — works on desktop, tablet, and mobile
- **Zero dependencies** — single HTML file, no npm, no build step, no CDN required for core logic

---

## 🧪 Difficulty Levels

| Level | Role | Scenario Type |
|-------|------|--------------|
| 1 — Trainee | Junior Analyst | Allow one specific service from a single host |
| 2 — Analyst | SOC Analyst | Block all traffic from a threat subnet (CIDR) |
| 3 — Engineer | Sysadmin | Harden a production server (multi-rule policy) |
| 4 — Specialist | Network Engineer | Allow two randomised services from any source |
| 5 — Architect | Security Architect | Full DMZ segmentation with directional rules |

---

## 📚 Services Covered

The lab draws from 16 real-world services commonly tested on Security+, CCNA, and Network+:

`FTP` `SSH` `Telnet` `SMTP` `DNS` `TFTP` `HTTP` `POP3` `NTP` `IMAP` `SNMP` `HTTPS` `SMB` `MSSQL` `MySQL` `RDP`

Each hint explains *why* the service uses TCP or UDP — not just the port number.

---

## 🚀 Getting Started

### Option 1 — GitHub Pages (recommended)
Fork this repo, enable GitHub Pages in **Settings → Pages → Source: main branch**, and your lab is live at:
```
https://<your-username>.github.io/<repo-name>/
```

### Option 2 — Local
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
open index.html   # macOS
# or just double-click index.html in your file explorer
```

No build step. No server required. Open the file directly in any modern browser.

---

## 🗂️ Project Structure

```
/
├── index.html      # The entire application — HTML, CSS, and JS in one file
├── README.md       # This file
└── LICENSE         # MIT License
```

---

## 🎓 Who Is This For?

- Students studying for **CompTIA Security+** (exam objective: 3.0 — Security Architecture / Network Security)
- **CCNA** candidates learning ACL configuration concepts
- **Network+** candidates building port/protocol fluency
- Instructors looking for a zero-setup lab exercise to assign
- Anyone who wants to sharpen firewall fundamentals fast

---

## 🛠️ Built With

- **Vanilla HTML/CSS/JavaScript** — ES5-compatible, no frameworks
- **Inter** + **JetBrains Mono** via Google Fonts
- **CSS custom properties** for full dark/light theming
- **JSON-LD** structured data for SEO (`LearningResource` schema)
- Inline **SVG icons** — no icon font dependency

---

## 🤝 Contributing

Contributions are welcome! Ideas for improvement:

- Add more difficulty levels (e.g. stateful inspection, NAT rules)
- Add a session score tracker
- Add a port/protocol quick-reference table
- Translate scenarios into other languages

To contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-idea`)
3. Commit your changes (`git commit -m 'Add: your feature description'`)
4. Push and open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.  
Free to use, share, and modify. Attribution appreciated but not required.

---

## 👤 Author

**Mohammad Lotfi**  
🌐 [mohammadlotfi.com](https://mohammadlotfi.com) — more labs, courses, and resources  
🏢 **MLA Tech**

---

*If this helped you pass your exam, consider sharing it with your study group. ⭐ Star the repo to help others find it.*
