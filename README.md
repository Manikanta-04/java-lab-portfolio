<div align="center">

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>

<br/>

# 📘 Advanced Java Lab Portfolio

### A structured digital lab record system for 12 weeks of Advanced Java experiments

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-Visit%20Site-2ea44f?style=for-the-badge)](https://manikanta-04.github.io/java-lab-portfolio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 📌 Overview

The **Advanced Java Lab Portfolio** is a professional digital lab record system designed to organize and present **12 weeks of Advanced Java laboratory experiments** in a clean, structured, and accessible format.

Built as a portfolio-style static web application, it enables students and evaluators to navigate weekly lab programs with ease — featuring inline PDF previews, download options, and a minimal academic UI.

> **Deployed on GitHub Pages** — zero backend, zero dependencies, fully static.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📂 Week-wise Navigation | Sidebar spanning Week 1 to Week 12 |
| 📄 PDF Viewer | Embedded inline PDF preview per week |
| ⬇️ Download | One-click download for each week's lab record |
| 🎨 Clean UI | Minimal dark-theme academic design |
| 📱 Responsive | Adapts to desktop and tablet screens |
| 🧑‍🎓 Student Info | Roll number and student details displayed |

---

## 🗂️ Project Structure

```
java-lab-portfolio/
│
├── index.html              # Landing page / Week 1 default view
├── week1.html – week12.html # Individual week pages
│
├── assets/
│   ├── pdf/                # Lab record PDFs (week1.pdf – week12.pdf)
│   └── images/             # UI assets
│
├── css/
│   └── style.css           # Global stylesheet
│
├── js/
│   └── script.js           # Navigation & PDF rendering logic
│
└── README.md
```

---

## 📚 Lab Experiments

| Week | Topic |
|------|-------|
| Week 1  | JDBC & MySQL Connection |
| Week 2  | CRUD Operations using JDBC |
| Week 3  | Servlets |
| Week 4  | JavaServer Pages (JSP) |
| Week 5  | Session Management |
| Week 6  | Cookies |
| Week 7  | MVC Architecture |
| Week 8  | Hibernate Basics |
| Week 9  | Spring Framework |
| Week 10 | Spring Boot |
| Week 11 | REST API Development |
| Week 12 | Mini Project Integration |

---

## 🛠️ Tech Stack

- **Frontend** — HTML5, CSS3, JavaScript (Vanilla)
- **PDF Rendering** — Native browser embed / PDF.js
- **Deployment** — GitHub Pages

---

## 🚀 Run Locally

```bash
# Clone the repository
git clone https://github.com/Manikanta-04/java-lab-portfolio.git

# Navigate into the project
cd java-lab-portfolio

# Open in browser (no build step required)
open index.html
```

> ⚠️ For PDF embeds to work correctly locally, serve via a local HTTP server:
> ```bash
> python -m http.server 8000
> # then open http://localhost:8000
> ```

---

## 🌍 Deployment

Hosted via **GitHub Pages**.

```
Settings → Pages → Branch: main → Root (/) → Save
```

Live: [https://manikanta-04.github.io/java-lab-portfolio/](https://manikanta-04.github.io/java-lab-portfolio/)

---

## 🔭 Roadmap

- [ ] 🔍 Global search across all weeks
- [ ] 🌙 Dark / Light mode toggle
- [ ] 📊 Progress tracker for completed experiments
- [ ] 📦 Bulk ZIP download of all lab records
- [ ] 🔐 Optional login gate for restricted access

---

## 🎓 Academic Details

| Field | Details |
|---|---|
| **Student** | N. Manikanta |
| **Roll No.** | 238W1A12A7 |
| **Program** | B.Tech – Information Technology |
| **Subject** | Advanced Java Programming Laboratory |
| **Academic Year** | 2025 – 2026 |

---

## 📄 License

Released under the [MIT License](LICENSE). Free to fork and adapt for academic use with attribution.

---

<div align="center">

Made with ❤️ by [N. Manikanta](https://github.com/Manikanta-04)

⭐ **Star this repo if you found it helpful!**

</div>
