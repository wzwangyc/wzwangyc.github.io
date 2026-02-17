# 🌐 Yucheng Wang's Personal Portfolio

[![Build Status](https://github.com/wzwangyc/wzwangyc.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/wzwangyc/wzwangyc.github.io/actions)
[![Powered by Jekyll](https://img.shields.io/badge/Powered%20by-Jekyll-red)](https://jekyllrb.com/)
[![Theme](https://img.shields.io/badge/Theme-Minimal%20Mistakes-blue)](https://mmistakes.github.io/minimal-mistakes/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

> Source code for my personal website: **[wzwangyc.github.io](https://wzwangyc.github.io)**

This repository hosts the static source code for my personal portfolio, built with **Jekyll** and hosted on **GitHub Pages**. It serves as a comprehensive showcase of my academic research, quantitative projects, and creative works.

---

## 👨‍💻 About The Author

**Yucheng Wang (王煜诚)**
* **M.Sc. Candidate** in Digital Financial Technology at **National University of Singapore (NUS)**.
* **Quant Researcher** & **AI Algorithm Engineer** (Ex-Baidu Qianfan).
* **Music Producer** ("Awakening Conscience", 48M+ Streams).

My work focuses on the intersection of **Quantitative Finance**, **Deep Learning (Time-Series)**, and **Blockchain**.

---

## ✨ Features & Structure

This site is customized based on the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme to fit a "Quant Scientist" persona.

### 1. **Curriculum Vitae as Code (`/cv/`)**
* A responsive, digital version of my resume.
* Includes a direct download link for the PDF version.
* [View CV Page](https://wzwangyc.github.io/cv/)

### 2. **Project Portfolio (`/projects/`)**
* **AI & Algo Trading:** Showcasing *Meta-HCapsNet* (Baidu) and *Risk Parity Strategies* (SSE Cup).
* **Data Engineering:** Highlighting the Fiscal Data ETL Pipeline.
* **Gamified FinTech:** The "Cai Meng Consensus Circle" product case study.
* [View Projects](https://wzwangyc.github.io/projects/)

### 3. **Academic Publications (`/publications/`)**
* Lists working papers (e.g., *Computational Economics* submission) and research reports.
* Formatted using standard academic citation styles.

---

## 🛠 Tech Stack

The site is built with a focus on **performance**, **maintainability**, and **developer-friendliness**.

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Generator** | `Jekyll` | Static site generator written in Ruby. |
| **Templating** | `Liquid` | For dynamic content rendering. |
| **Theme** | `Minimal Mistakes` | Highly customizable, responsive, dark-mode ready. |
| **Styling** | `SCSS` | Custom tweaks for the "Quant Dark" aesthetic. |
| **Deployment** | `GitHub Actions` | CI/CD pipeline for automated building and deployment. |
| **Math** | `MathJax` | For rendering LaTeX equations in research posts. |

---

## 📂 Directory Map

For developers or recruiters reviewing the source code:

```text
.
├── _config.yml          # Main configuration (Site settings, SEO, Navigation)
├── _data/
│   └── navigation.yml   # Top navigation bar structure
├── _pages/              # Static pages (About, Projects, CV)
├── _posts/              # Blog posts (Year-Month-Day-Title.md)
├── assets/
│   └── images/          # Profile pictures and project screenshots
├── Gemfile              # Ruby dependencies
└── index.md             # Landing page (Homepage)
