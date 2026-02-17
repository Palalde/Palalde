# Paul Alessandrini

**Développeur web en reconversion** · autodidacte · France

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paul-a-268a55339/)
[![CV Interactif](https://img.shields.io/badge/🌐_CV_Interactif-Live-blue?style=flat)](https://cv-interactif-paul.vercel.app/)

---

Ancien trader indépendant reconverti dans le développement web.  
J'apprends en construisant des projets concrets — pas de bootcamp, pas de tuto passif.

---

## Stack

**Maîtrisé**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat&logo=npm&logoColor=white)
![esbuild](https://img.shields.io/badge/esbuild-FFCF00?style=flat&logo=esbuild&logoColor=black)

**En apprentissage**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Prévu**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat&logo=hono&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

---

## Projets

### [CV Interactif](https://github.com/Palalde/CV-interactif) · [Demo live](https://cv-interactif-paul.vercel.app/)

> Site statique vanilla JS — mon CV sous forme d'app interactive chronologique.

Un projet frontend complexe construit sans framework, qui démontre une maîtrise concrète du JavaScript natif et des Web APIs modernes :

- **Navigation** — Slider chronologique avec snap, swipe mobile, historique de navigation (back/forward)
- **Trading** — Graphique chandelier temps réel (Lightweight Charts v5), crosshair, watermark, thème synchronisé
- **Leclerc** — Drag & drop HTML5 + Pointer Events (desktop & mobile), balance interactive avec ticket de pesée
- **Terminal** — Console xterm.js embarquée avec commandes custom, bundlée via esbuild
- **Recherche** — Moteur de recherche avec autocomplete, filtres, favoris (persistés en localStorage, sync cross-tab)
- **Thème** — Dark/light mode + générateur de palette couleur via API externe, appliqué en temps réel
- **Analytics** — Dashboard stats avec Canvas (pie chart), Web Worker pour le calcul, export CSV
- **Accessibilité** — Focus trap, ARIA, navigation clavier complète, `aria-live` regions
- **Responsive** — Mobile-first, media query listeners JS, viewport stable (`--app-vh`), gestes tactiles

<details>
<summary><strong>APIs & techniques utilisées</strong></summary>

`Canvas 2D` · `IntersectionObserver` · `ResizeObserver` · `MutationObserver` · `Web Workers` · `Clipboard API` · `Fetch API` · `Drag & Drop API` · `Pointer Events` · `Touch Events` · `File API` · `Page Visibility` · `matchMedia` · `requestAnimationFrame` · `CustomEvent` · `dynamic import()` · `Promise.all` · `async/await` · `ES Modules` · `IIFE` · `Classes` · `Event delegation` · `Debounce` · `Velocity-based gestures` · `CSS Custom Properties (JS)` · `localStorage` · `sessionStorage` · `cross-tab sync` · `Unicode regex` · `focus trap` · `ARIA`

</details>

---

### [ChefPlanning](https://github.com/Palalde/react) · 🚧 En développement

> App React de gestion de planning d'équipe pour la restauration.

Projet d'apprentissage React structuré en phases progressives — chaque feature est un exercice ciblé :

- **Phases 0-6** ✅ — JSX, composants, props, useState, listes, useEffect, custom hooks
- **Phase 7** ✅ — Lifting state up, assignments, calcul d'heures
- **Phase 8** ✅ — Custom hooks avancés (`useEmployees`, `useShifts`, `useAssignments`, `useHoursCalculator`)
- **Phase 9** 🔄 — Composition avancée, refonte UI (tableau Employé×Jour AM/PM), CRUD shifts, navigation semaines
- **Phase 10** 📘 — Migration TypeScript
- **Phases 11-12** 📘 — Backend (Hono + Drizzle + PostgreSQL)

`React` · `Vite` · `Tailwind CSS` · `Custom Hooks` · `date-fns`

---

## Approche

```
pas de bootcamp → projets concrets
pas de tuto copié → code écrit à la main
pas de framework magique → comprendre ce qui se passe sous le capot
```

Je construis d'abord en vanilla JS pour comprendre les fondamentaux, puis je monte en abstraction avec React et TypeScript. Chaque projet est un terrain d'apprentissage réel, pas un exercice jetable.

---

<sub>📍 France · Ouvert aux opportunités · [CV PDF disponible sur demande](https://cv-interactif-paul.vercel.app/)</sub>
