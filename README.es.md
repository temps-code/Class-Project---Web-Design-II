<div align="center">

<img src="https://github.com/temps-code/Class-Project---Web-Design-II/blob/main/logo.jpg?raw=true" alt="D² Innovation Logo" width="160"/>

<h1>Todo List — Gestor de Proyectos de Construcción</h1>

<p><strong>Una aplicación web para planificar, hacer seguimiento y gestionar proyectos de construcción desde un solo panel.</strong></p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=323330" alt="JavaScript">
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap 5">
</p>

</div>

---

📄 Leé esto en: [English](README.md) | **Español**

---

**Proyecto Académico**
Universidad Privada Domingo Savio — Ing. de Sistemas
Materia: Diseño Web II — 2024

---

## Tabla de Contenidos

- [Descripción](#descripción)
- [Stack](#stack)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación](#instalación)
- [Páginas](#páginas)
- [Equipo](#equipo)

---

## Descripción

Todo List es una aplicación web estática construida para equipos de construcción que necesitan gestionar múltiples proyectos de forma simultánea.

**El problema**: los equipos de construcción hacen seguimiento de tareas, costos y avances en planillas y notas dispersas — desordenado, ineficiente y propenso a errores.

**La solución**: una sola interfaz web que centraliza la gestión de proyectos con cuatro módulos dedicados.

Funcionalidades principales:

- Crear y gestionar proyectos de construcción con descripción y fechas límite
- Visualizar y mover tareas en un tablero Kanban (Por hacer / En progreso / Completado)
- Hacer seguimiento de costos reales versus el presupuesto planificado
- Formulario de contacto para comunicación del equipo

---

## Stack

| Categoría | Tecnología | Versión |
|---|---|---|
| Marcado | HTML5 | 5 |
| Estilos | CSS3 | 3 |
| Framework de Estilos | Bootstrap | 5.3.3 |
| Scripts | JavaScript (Vanilla) | ES6+ |

---

## Estructura del Proyecto

```
classproject/
├── index.html          # Página de inicio
├── proyectos.html      # Lista y creación de proyectos
├── kanban.html         # Tablero de tareas
├── costos.html         # Seguimiento de costos
├── contacto.html       # Formulario de contacto
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

## Instalación

No requiere compilación. Es un proyecto completamente estático.

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/temps-code/Class-Project---Web-Design-II.git
   ```

2. Navegá a la carpeta del proyecto:
   ```bash
   cd Class-Project---Web-Design-II/classproject
   ```

3. Abrí `index.html` en tu navegador — o servilo localmente:
   ```bash
   # Con la extensión Live Server de VS Code, o:
   npx serve .
   ```

> No hay dependencias que instalar ni variables de entorno requeridas.

---

## Páginas

| Página | Archivo | Descripción |
|---|---|---|
| Inicio | `index.html` | Landing page con resumen del proyecto y navegación |
| Proyectos | `proyectos.html` | Crear y explorar proyectos de construcción |
| Tareas | `kanban.html` | Tablero Kanban para gestión de tareas |
| Seguimiento de Costos | `costos.html` | Monitorear gastos versus presupuesto planificado |
| Contacto | `contacto.html` | Formulario de contacto del equipo |

---

## Equipo

| Integrante | Rol |
|---|---|
| Diego Vargas | Desarrollador Frontend |
| Damaris Mamani | Desarrolladora Frontend |

---

<div align="center">
<img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License: MIT">
</div>
