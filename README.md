<div align="center">

<img src="https://github.com/temps-code/Class-Project---Web-Design-II/blob/main/logo.jpg?raw=true" alt="D² Innovation Logo" width="160"/>

<h1>Todo List — Construction Project Manager</h1>

<p><strong>A web application to plan, track, and manage construction projects from a single dashboard.</strong></p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=323330" alt="JavaScript">
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap 5">
</p>

</div>

---

📄 Read this in: **English** | [Español](README.es.md)

---

**Academic Project**
Universidad Privada Domingo Savio — Ing. de Sistemas
Course: Web Design II — 2024

---

## Table of Contents

- [What It Does](#what-it-does)
- [Stack](#stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Pages](#pages)
- [Team](#team)

---

## What It Does

Todo List is a static web application built for construction teams that need to manage multiple projects simultaneously.

**The problem**: construction teams track tasks, costs, and project progress across spreadsheets and sticky notes — scattered, inefficient, and error-prone.

**The solution**: a single web interface that centralizes project management with four dedicated modules.

Key features:

- Create and manage construction projects with descriptions and deadlines
- Visualize and move tasks across a Kanban board (To Do / In Progress / Done)
- Track project costs against planned budgets
- Contact form for team communication

---

## Stack

| Category | Technology | Version |
|---|---|---|
| Markup | HTML5 | 5 |
| Styling | CSS3 | 3 |
| Styling Framework | Bootstrap | 5.3.3 |
| Scripting | JavaScript (Vanilla) | ES6+ |

---

## Project Structure

```
classproject/
├── index.html          # Home / landing page
├── proyectos.html      # Projects list and creation
├── kanban.html         # Task board
├── costos.html         # Cost tracking
├── contacto.html       # Contact form
├── css/
│   ├── global.css
│   ├── proyectos.css
│   ├── kaban.css
│   └── contacto.css
└── js/
    ├── index.js
    ├── proyectos.js
    ├── kanban.js
    ├── costos.js
    └── contacto.js
```

---

## Installation

No build step required. This is a fully static project.

1. Clone the repository:
   ```bash
   git clone https://github.com/temps-code/Class-Project---Web-Design-II.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Class-Project---Web-Design-II/classproject
   ```

3. Open `index.html` in your browser — or serve it locally:
   ```bash
   # Using VS Code Live Server extension, or:
   npx serve .
   ```

> No dependencies to install. No environment variables required.

---

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Landing page with project overview and navigation |
| Projects | `proyectos.html` | Create and browse construction projects |
| Tasks | `kanban.html` | Kanban board for task management |
| Cost Tracking | `costos.html` | Monitor expenses vs. planned budget |
| Contact | `contacto.html` | Team contact form |

---

## Team

| Member | Role |
|---|---|
| Diego Vargas | Frontend Developer |
| Damaris Mamani | Frontend Developer |

---

<div align="center">
<img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License: MIT">
</div>
