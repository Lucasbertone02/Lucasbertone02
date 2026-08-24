<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A1128,50:0353A4,100:0077FF&height=200&section=header&text=Lucas%20Bertone&fontSize=54&fontColor=FFFFFF&fontAlignY=35&desc=Frontend%20%2F%20Full-Stack%20Developer&descSize=18&descAlignY=55&animation=fadeIn" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=0077FF&center=true&vCenter=true&width=650&lines=Cofundador+de+FlexCode+Software;Construyo+SaaS+multi-tenant+en+producci%C3%B3n;Next.js+%C2%B7+TypeScript+%C2%B7+Django+REST;De+Bah%C3%ADa+Blanca%2C+Argentina+%F0%9F%87%A6%F0%9F%87%B7" alt="Typing SVG" />

<br/>

<a href="https://flexcodesoftware.com">
  <img src="https://img.shields.io/badge/Portfolio-0077FF?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0A1128" />
</a>
<a href="https://linkedin.com/in/lucas-bertone2">
  <img src="https://img.shields.io/badge/LinkedIn-0077FF?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A1128" />
</a>
<a href="mailto:bertonelucas885@gmail.com">
  <img src="https://img.shields.io/badge/Email-0077FF?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A1128" />
</a>
<img src="https://komarev.com/ghpvc/?username=Lucasbertone02&style=for-the-badge&color=0077FF&labelColor=0A1128&label=VISITAS" />

</div>

<br/>


## Sobre mí

Construyo aplicaciones web con **Next.js**, **React** y **TypeScript**, y las APIs que están atrás con **Django REST Framework** y **PostgreSQL**. Cofundador de [FlexCode Software](https://flexcodesoftware.com), donde diseño plataformas SaaS multi-tenant que hoy corren en producción con clientes reales en Argentina, Uruguay y España.

```ts
const lucas = {
  rol:      "Frontend / Full-Stack Developer",
  empresa:  "FlexCode Software (cofundador)",
  stack:    ["Next.js", "React", "TypeScript", "Django REST", "PostgreSQL"],
  foco:     ["Arquitectura multi-tenant", "Performance", "Testing", "Seguridad"],
  ia:       ["Claude Code", "Cursor"],
  ubicacion: "Bahía Blanca, Argentina",
};
```

<br/>

## Proyectos en producción

<table>
<tr>
<td width="50%" valign="top">

### Vectus
**SaaS multi-tenant de gestión**

Una sola base de código sirviendo a varias empresas con planes y feature flags por instancia. Remitos digitales con firma en pantalla, contratos, ruteo de operaciones y caja con P&L.

Bajé el listado de remitos de **~560 kB / ~1,8 s** a **~60 kB** y fracciones de segundo eliminando N+1 y moviendo filtrado y paginación al server.

`Next.js 16` `TypeScript` `Django 5` `PostgreSQL`

</td>
<td width="50%" valign="top">

### [Zonea](https://zonea.app)
**SaaS de gestión de torneos de pádel**

Clubes crean torneos, el motor genera los fixtures con horarios y canchas, y los resultados salen exportados como imagen con el brand kit del club.

Arquitectura hexagonal con el dominio testeado primero: **+1.800 tests**. Multi-tenancy con Row-Level Security de PostgreSQL.

`Next.js 16` `React 19` `Prisma` `Vitest`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Templo Barbería](https://templobarberia.com.ar)
**Sistema de gestión y reservas**

Reservas online, panel admin con vista kanban de turnos, programa de fidelidad y reportes financieros.

Control de doble reserva a nivel de base de datos con constraint condicional y transacción que devuelve **409** en conflictos concurrentes.

`Next.js 15` `Zustand` `Django 6` `JWT`

</td>
<td width="50%" valign="top">

### [FlexCode Software](https://flexcodesoftware.com)
**Sitio institucional**

Arquitectura modular de componentes reutilizables con optimización de assets y SEO técnico.

Junto a proyectos a medida para clientes de Argentina, Uruguay y España, desde el relevamiento hasta el deploy.

`Astro` `TypeScript` `Tailwind`

</td>
</tr>
</table>

<br/>

## Stack

<div align="center">

**Frontend**

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,astro,tailwind,html,css&theme=dark" />

**Backend & Datos**

<img src="https://skillicons.dev/icons?i=python,django,nodejs,postgres,prisma,supabase&theme=dark" />

**Testing, Infra & Herramientas**

<img src="https://skillicons.dev/icons?i=vitest,git,github,docker,vercel,figma&theme=dark" />

</div>

<br/>

<details>
<summary><b>Ver el stack en detalle</b></summary>

<br/>

| Área | Tecnologías |
|---|---|
| **Frontend** | TypeScript · React 19 · Next.js (App Router, Server Components/Actions) · Astro · Tailwind CSS · Zustand · Framer Motion · Zod |
| **Backend** | Python · Django 5/6 · Django REST Framework · PostgreSQL · Prisma · JWT / OAuth 2.0 · RBAC · Row-Level Security |
| **Testing** | Vitest · Pytest · TDD · tests de integración · type-checking en CI |
| **Infra** | Git · CI/CD · Vercel · Railway · Supabase · Docker |
| **IA** | Claude Code · Cursor — scaffolding, generación de tests y refactors guiados, con revisión y testing manual antes del merge |

</details>

<br/>

## Cómo trabajo

> **Arquitectura primero.** Multi-tenancy, límites de dominio y modelo de datos antes del primer archivo.
>
> **Tests, no como trámite.** En Zonea el dominio se testeó antes de que existiera la UI.
>
> **Performance medida, no supuesta.** Si digo que algo bajó de 1,8 s, tengo el número de antes.
>
> **Seguridad durante, no después.** Auditorías por ronda: mass-assignment, IDOR, sesión y tokens, control de acceso por rol.

<br/>

## Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Lucasbertone02&show_icons=true&hide_border=true&bg_color=0A1128&title_color=0077FF&text_color=FFFFFF&icon_color=0077FF&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lucasbertone02&layout=compact&hide_border=true&bg_color=0A1128&title_color=0077FF&text_color=FFFFFF&langs_count=8" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Lucasbertone02&hide_border=true&background=0A1128&stroke=0077FF&ring=0077FF&fire=0077FF&currStreakLabel=0077FF&sideLabels=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=AAAAAA" width="500" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Lucasbertone02&bg_color=0A1128&color=FFFFFF&line=0077FF&point=FFFFFF&area=true&hide_border=true" width="100%" />

</div>

<br/>

## La viborita

<div align="center">

<img src="https://raw.githubusercontent.com/Lucasbertone02/Lucasbertone02/output/snake.svg" alt="Snake animation" width="100%" />

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0077FF,50:0353A4,100:0A1128&height=120&section=footer" width="100%" />

</div>
