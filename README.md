
# 🏛️ Public Academic Projects & Software Engineering Showcase

Welcome to my central academic software repository. This space serves as an engineering log and production-grade portfolio, showcasing scalable software architectures, deep semantic layout designs, and responsive frontend systems built entirely with modern web standards.

Each directory inside this repository represents a distinct project engineered to solve specific layout, architectural, or integration problems.

---
## Projects included:
**[Academic Event Matrix](./school-events-matrix)** - Advanced Vanilla JS SPA utilizing public Holiday APIs, responsive CSS container queries, and a custom History API router.
## 🛠️ Project Directory Index

### 1. 📅 Academic Event Matrix (Vanilla JS SPA)
* **Directory:** [`/school-event-matrix`](./academic-events-matrix)
* **Core Stack:** Vanilla JavaScript (ES6+ Modules), HTML5 Semantics, Native CSS (Grid/Subgrid)
* **Architectural Highlights:**
  - Built completely framework-free to demonstrate raw DOM manipulation and memory management safety.
  - Features a custom client-side router leveraging the native browser **History API**.
  - Implements a network-resilient caching wrapper (`localStorage` abstraction) around public Holiday APIs to guarantee smooth performance on unstable networks.
  - Utilizes strict **Event Delegation** on a complex, mathematical calendar grid to optimize computational efficiency.

---

## 🎨 Core Engineering Philosophy & Habit Checklist

Across all projects in this repository, I follow strict production-level coding habits that align with modern web engineering standards:

* **Semantic Layout Architectures:** Total avoidance of `<div>` soup. Interfaces are structurally organized using `<main>`, `<article>`, `<section>`, and `<aside>` to ensure accessible markup (WCAG compliance).
* **Modern Scalable CSS:** Built entirely without styling framework dependencies. Layouts rely on CSS Custom Properties for theme orchestration, CSS Grid/Flexbox for multi-axis alignments, and modern **Container Queries (`@container`)** for component-isolated responsiveness.
* **Framework-Free Core Competency:** Deep reliance on native web standards (ES Modules, Native Web APIs) to ensure blistering performance and minimal bundle overhead.
* **Atomic Version Control:** Maintain clean, readable, and semantic Git history tracking clear logical progressions (e.g., `feat:`, `fix:`, `refactor:`).

---

## ⚙️ Running Projects Locally

Since these projects are built natively on web standards, they do not require heavy dependency compilation or package installations:

1. Clone this repository to your workstation:
   ```bash
   git clone https://github.com
   ```
2. Navigate into any specific project directory.
3. Serve the directory using a lightweight development server (such as the *Live Server* extension in VS Code) to allow ES Modules to resolve correctly.

