<div align="center">

# Ilmaan Khan

**Full-stack developer who builds complete apps, from database schema to UI.**

B.Tech Information Science at CMRIT, Bengaluru · Class of 2028

![Open to](https://img.shields.io/badge/Open_to-SWE_Internships-2ea44f?style=flat)
![Location](https://img.shields.io/badge/Bengaluru-India-555555?style=flat)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ilmaan-khan/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:ilm2ankhan@gmail.com)

</div>

---

## About

I learn by building whole applications: designing the data model, writing the API, then making it usable in the browser. My recent work is a Spring Boot + React system that predicts railway station congestion, and a Next.js platform for a Bengaluru printing business with a 2D design editor and 3D packaging preview.

I like databases, clean APIs, and problems where the interface has to do something non-trivial.

## Tech stack

| | |
|---|---|
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white) |
| **Backend and data** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white) ![npm](https://img.shields.io/badge/npm-CB3837?style=flat&logo=npm&logoColor=white) |

---

## Featured projects

[![Railway Congestion](https://github-readme-stats.vercel.app/api/pin/?username=ilm2ankhan-maker&repo=Railway_congestion&theme=tokyonight&border_radius=10)](https://github.com/ilm2ankhan-maker/Railway_congestion)
[![PrintCraft](https://github-readme-stats.vercel.app/api/pin/?username=ilm2ankhan-maker&repo=printcraft-vajra-prints&theme=tokyonight&border_radius=10)](https://github.com/ilm2ankhan-maker/printcraft-vajra-prints)

### Railway Congestion Prediction System

Search a PNR and see whether the station will be Low, Medium, or High congestion.

- Congestion prediction from reservation data
- REST API between a React (Vite) frontend and Spring Boot backend
- MySQL for data management

`Java` `Spring Boot` `React` `Vite` `MySQL`

### PrintCraft: Digital Prepress and E-Commerce

Built for Vajra Prints, a commercial printing business in Bengaluru, as a team project at CMRIT.

- 2D design studio with bleed lines, templates, and SVG/PNG layers
- 3D packaging customizer with real-time preview
- Laser-cutting price calculator driven by SVG outlines
- Staff dashboard with an order management pipeline

`Next.js` `TypeScript` `Tailwind CSS` `Zustand` `Prisma` `Supabase`

<!--
Add demos when you have them (keep each under ~5 MB):
![Railway demo](./assets/railway-demo.gif)
![PrintCraft demo](./assets/printcraft-demo.gif)
-->

<details>
<summary><b>How they're built</b></summary>

```mermaid
flowchart LR
    subgraph Railway
        RC[React + Vite] -->|REST| SB[Spring Boot API]
        SB --> ML[(MySQL)]
    end

    subgraph PrintCraft
        NX[Next.js + Zustand] --> ST[2D Studio]
        NX --> TD[3D Preview]
        NX -->|Prisma| SP[(Supabase)]
    end
```

</details>

<details>
<summary><b>Run them locally</b></summary>

Commands are the standard ones for each stack. Check each repo's README if something differs.

**Railway Congestion** (Java 17+, Maven, Node 18+, MySQL 8+)

```bash
git clone https://github.com/ilm2ankhan-maker/Railway_congestion.git
cd Railway_congestion

# backend
cd backend && mvn spring-boot:run

# frontend (new terminal)
cd frontend && npm install && npm run dev
```

**PrintCraft** (Node 18+, a Supabase project)

```bash
git clone https://github.com/ilm2ankhan-maker/printcraft-vajra-prints.git
cd printcraft-vajra-prints
npm install
npx prisma migrate dev
npm run dev
```

</details>

---

## GitHub stats

[![Stats](https://github-readme-stats.vercel.app/api?username=ilm2ankhan-maker&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10)](https://github.com/ilm2ankhan-maker)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ilm2ankhan-maker&layout=compact&theme=tokyonight&hide_border=true&border_radius=10)](https://github.com/ilm2ankhan-maker)

---

## Currently working on

- [ ] Tests for the Railway prediction logic
- [ ] CI (build and lint) with GitHub Actions
- [ ] Live deployments for both projects

---

## Get in touch

I'm looking for a Software Engineering internship. If you're hiring, or just want to talk about a project, reach out.

[LinkedIn](https://www.linkedin.com/in/ilmaan-khan/) · [ilm2ankhan@gmail.com](mailto:ilm2ankhan@gmail.com)
