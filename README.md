# Personal Portfolio & Algorithm Visualizations

This repository contains my personal website and portfolio, built as a long-term project to document my work as a software engineering student and to explore algorithmic concepts through interactive visualizations.

The site includes:
- A portfolio of projects
- An interactive algorithm visualizer
- A technical blog documenting design decisions and learnings

The project is designed to evolve over time as I continue my studies and professional experience.

---

## ✨ Features

- **Interactive Algorithm Visualizer**
  - Visual exploration of pathfinding and graph algorithms
  - Step-by-step execution and comparison
  - User-configurable environments and parameters

- **Projects Section**
  - Detailed pages for personal and academic projects
  - Focus on engineering decisions, not just results

- **Dev Blog**
  - Technical articles on algorithms, software design, and problem-solving
  - Reflections on implementation trade-offs and learning outcomes

---

## 🧠 Motivation

Many algorithm visualizations focus on showing *what* an algorithm does.
This project aims to explore *how* and *why* different algorithms behave the way they do, using interactive tools and clear explanations.

The goal is to bridge theory and practice through software engineering.

---

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router)
- **Language:** TypeScript / JavaScript
- **Frontend:** React, Tailwind CSS
- **Algorithms:** Custom implementations (UI-agnostic)
- **Deployment:** Vercel (planned)

---

## 📁 Project Structure

````

src/
├─ app/            # Next.js routes (pages)
├─ components/     # Reusable UI components
├─ algorithms/     # Algorithm implementations (framework-agnostic)
├─ lib/            # Utilities and helpers

````

Algorithms are intentionally decoupled from the UI to allow reuse, testing, and future extensions.

---

## 🚀 Running Locally

```bash
npm install
npm run dev
```

Then open `http://localhost:3000` in your browser.

---

## 📌 Roadmap

* [ ] Pathfinding algorithms (BFS, Dijkstra, A*)
* [ ] Algorithm comparison mode
* [ ] Performance and complexity visualization
* [ ] Additional algorithm modules (graphs, data structures)
* [ ] Blog system with Markdown
* [ ] Deployment

---

## 📄 License

This project is for educational and personal use.
Feel free to explore the code and ideas.

