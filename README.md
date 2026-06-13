<div align="center">

# 📚 CyberLib — Tanish Sareen's Cybersecurity Library

**Free, in-depth technical guides on penetration testing, digital forensics,  
network analysis, and offensive security tools.**

[![Books](https://img.shields.io/badge/Books-7_Published-00ff9d?style=for-the-badge&logo=bookstack&logoColor=black)](https://tanish-sareen.github.io/cyberlib)
[![License: MIT](https://img.shields.io/badge/License-MIT-7b61ff?style=for-the-badge)](LICENSE)
[![Free](https://img.shields.io/badge/Price-100%25_Free-ff4d6d?style=for-the-badge)]()
[![Pages](https://img.shields.io/badge/GitHub_Pages-Live-60a5fa?style=for-the-badge&logo=github)](https://tanish-sareen.github.io/cyberlib)

<br>

> Written by **Tanish Sareen** · BCA Cyber Security & Forensics · CT University  
> *For educational & authorised penetration testing use only.*

**[🌐 Browse the Library - https://tanish-sareen.github.io/Cyber-lib/#books]**

</div>

---

## 📖 Published Guides

| # | Title | Category | Chapters | Download |
|---|-------|----------|----------|----------|
| 01 | **Medusa — Brute-Force & Password Auditing** | Password · Offensive | 23 + 3 Appendices | [PDF](books/Medusa_Complete_Guide_Tanish_Sareen.pdf) |
| 02 | **Wireshark — Complete Packet Analysis** | Network · Forensics | Full Guide | [PDF](books/Wireshark_Complete_Guide_Tanish_Sareen.pdf) |
| 03 | **NMAP — Network Scanning & Recon** | Recon · Network | Full Guide | [PDF](books/NMAP_Complete_Guide_Tanish_Sareen.pdf) |
| 04 | **John The Ripper — Password Cracking** | Password · Offensive | Full Guide | [PDF](books/John_The_Ripper_eBook_TanishSareen.pdf) |
| 05 | **Autopsy — Digital Forensics Guide** | Forensics | Full Guide | [PDF](books/Autopsy_Digital_Forensics_Guide_TanishSareen.pdf) |
| 06 | **SET — Social Engineering Toolkit Field Guide** | Social Engineering | Full Guide | [PDF](books/SET_Complete_Field_Guide_Tanish_Sareen.pdf) |
| 07 | **Wash — Cybersecurity Fundamentals** | Defensive | Full Guide | [PDF](books/Wash_Cybersecurity_Ebook_Tanish_Sareen.pdf) |

---

## ⚠️ Legal Disclaimer

All content is written **strictly for educational purposes** and authorised penetration-testing engagements. Using any tool or technique described against systems without **explicit written permission** is illegal under India's IT Act 2000, the US CFAA, the UK Computer Misuse Act, and equivalent laws worldwide.

All practical exercises must be performed in **isolated lab environments** only.

---

## 🗂️ Repository Structure

```
cyberlib/
│
├── index.html          ← Library website (GitHub Pages)
├── README.md           ← This file
├── LICENSE             ← MIT License
│
└── books/              ← All PDF ebooks go here
    ├── Medusa_Complete_Guide_Tanish_Sareen.pdf
    ├── Wireshark_Complete_Guide_Tanish_Sareen.pdf
    ├── NMAP_Complete_Guide_Tanish_Sareen.pdf
    ├── John_The_Ripper_eBook_TanishSareen.pdf
    ├── Autopsy_Digital_Forensics_Guide_TanishSareen.pdf
    ├── SET_Complete_Field_Guide_Tanish_Sareen.pdf
    └── Wash_Cybersecurity_Ebook_Tanish_Sareen.pdf
```

---

## ➕ How to Publish a New Book (Daily Workflow)

```bash
# Step 1 — Drop your new PDF in the books/ folder
cp ~/my-projects/MY\ EBOOKS/NewBook_TanishSareen.pdf books/

# Step 2 — Open index.html, copy an existing book card block,
#           update: href, title, description, icon, tags, color

# Step 3 — Update the book count in index.html
#           <span id="book-count">8</span>   ← increment by 1

# Step 4 — Commit and push — live in ~30 seconds
git add .
git commit -m "📚 Add [Book Name] guide"
git push
```

The site auto-updates on GitHub Pages. No build step, no CI needed.

---

## 🎯 Who Is This For?

- Students studying **CEH, OSCP, CompTIA PenTest+, CHFI**
- **BCA / B.Tech / MCA** cybersecurity coursework
- **CTF players** looking for tool references
- Security professionals wanting quick command references
- Anyone building a home **penetration testing lab**

---

## 🛠️ Tech Stack

The library site is a **single zero-dependency HTML file** — no frameworks, no build tools, no npm. Just open `index.html` or visit the GitHub Pages URL.

---

## 📄 License

MIT License — © 2026 Tanish Sareen. Free to read, share, and learn from.  
See [LICENSE](LICENSE) for full terms.

---

<div align="center">

Made with 🖤 by **Tanish Sareen**  
*If this helped you, give it a ⭐ — it means a lot!*

</div>
