<p align="center">
  <img src="assets/hero.svg" width="100%" alt="Sad-Bin Alam: ASP.NET, C# and Go developer from Dhaka, Bangladesh. Core stack: C#, .NET, Go, PostgreSQL and MSSQL."/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square" alt="C#"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square" alt=".NET"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square" alt="Go"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MSSQL-CC2927?style=flat-square" alt="MSSQL"/>
  <img src="https://komarev.com/ghpvc/?username=thesturag&amp;label=Profile%20views&amp;color=0e75b6&amp;style=flat-square" alt="Profile views"/>
</p>

<p align="center">
  <a href="mailto:sadbin.alam@gmail.com"><b>Email</b></a> ·
  <a href="https://linkedin.com/in/md-sad-bin-alam-turag-477aa7164">LinkedIn</a> ·
  <a href="https://twitter.com/thesturag">X</a> ·
  <a href="https://www.youtube.com/c/thesturag">YouTube</a>
</p>

I build business software and data tools. ASP.NET is my home turf (C#, .NET, MSSQL). These days a lot of my back-end work is Go on PostgreSQL, with React and TypeScript on the front. Most of what I ship lives in private repositories, so this page is the guided tour.

- 🔭 **Building:** business software (ERP, billing, inventory) and a web data-extraction platform. See [Right now](#right-now).
- 🌱 **Learning:** Entity Framework, and going deeper with Go and Connect RPC.
- 💬 **Ask me about:** C#, .NET, ASP.NET, MSSQL, Go, PostgreSQL, and still php, angular and networking.
- 📫 **Reach me at:** sadbin.alam@gmail.com

<p align="center">
  <b><a href="#right-now">Right now</a></b> ·
  <a href="#stack">Stack</a> ·
  <a href="#public-repos">Public repos</a> ·
  <a href="#github-stats">Stats</a> ·
  <a href="#contact">Contact</a>
</p>

## Right now

Click a row to open it. Names are generic on purpose, because the repositories are private.

<p align="center">
  <img src="assets/now.svg" width="100%" alt="A terminal listing current work: a data-extraction platform, a multi-tenant ERP core, a courier billing platform, pharmacy and inventory apps, and AI mail triage with small tools."/>
</p>

<details open>
<summary><b>Web data-extraction platform</b> · dashboard, scraping API and docs</summary>

<br/>

A scraping and data-extraction product kept in one monorepo: a Next.js dashboard with sign-in, an Elysia API on Bun that drives headless Chromium through Puppeteer, a marketing site, a docs site and Playwright end-to-end tests. It ships in Docker and runs on PostgreSQL and Redis.

`Next.js` `React` `Prisma` `PostgreSQL` `Redis` `Bun` `Elysia` `Puppeteer` `Playwright` `Docker`

</details>

<details>
<summary><b>Business software</b> · ERP, billing, pharmacy, inventory, ISP</summary>

<br/>

| System | What it does | Built with |
| :-- | :-- | :-- |
| **ERP core** | Multi-tenant ERP with a typed RPC API, exact-decimal money handling and a React client | `Go` `Connect RPC` `Protobuf` `PostgreSQL` `React` |
| **Courier billing** | Bookings, carrier rates and costs, invoices, finance reports and staff access, with PDF documents and a multi-language UI | `Go` `chi` `pgx` `PostgreSQL` `React 19` `Vite` `Tailwind` `Playwright` |
| **Pharmacy management** | Pharmacy operations with dashboards, charts and validated forms | `React 19` `Vite` `Tailwind` `Bun` |
| **Shop inventory** | Inventory management for shops, as a web app and a desktop app, with unit and end-to-end tests | `TanStack` `Prisma` `Electron` `Vitest` `Playwright` `Docker` |
| **ISP management** | Management system for internet service providers | `Next.js` `Prisma` `Docker` |

</details>

<details>
<summary><b>Lead generation and AI-assisted tools</b> · find, score, triage</summary>

<br/>

| Tool | What it does | Built with |
| :-- | :-- | :-- |
| **Lead-generation app** | Finds local businesses that need a website or software from open map data, checks each site once, ranks the leads and exports a CSV with the evidence for every row. No account needed; saved leads stay in the browser | `React 19` `TypeScript` `Vite` `Tailwind 4` `Leaflet` `Vercel` |
| **Mail triage** | Pulls mail over IMAP into a local cache and scores each message for spam, priority and recommended action with an AI model. Runs on your own machine | `TanStack Start` `Bun` `TypeScript` |

</details>

<details>
<summary><b>Products, tools and games</b> · the side of the desk</summary>

<br/>

| Project | What it does | Built with |
| :-- | :-- | :-- |
| **Blogging platform** | Fast, private, self-hostable blogs with custom domains, a newsletter and analytics that do not track readers | `TanStack Start` `PostgreSQL` `Drizzle` `Docker Compose` `Caddy` |
| **Image generation API** | Banner and social-card images from templates and a visual editor, with a render cache | `TanStack Start` `Satori` `Skia canvas` `SQLite` |
| **Tab-tidy extension** | A Chromium extension that closes duplicate tabs, groups by site, sorts and merges windows, with no telemetry | `WXT` `TypeScript` `Manifest V3` |
| **Puzzle game** | A browser puzzle with generated, always-solvable levels, rotating boards and moving borders | `React 19` `Vite 8` `Canvas` |
| **Company website** | A marketing site with animated, interactive product demos | `Astro` `Tailwind 4` |

</details>

## Stack

Hover an icon for its name, click it for the docs.

<p align="center"><b>Core</b><br/><sub>what I reach for first</sub></p>

<div align="center">
<table align="center">
<tr><td align="center" width="120"><a href="https://go.dev" title="Go"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/go/go-original-wordmark.svg" width="56" height="56" alt="Go"/><br/><sub>Go</sub></a></td><td align="center" width="120"><a href="https://www.postgresql.org" title="PostgreSQL"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/postgresql/postgresql-original.svg" width="56" height="56" alt="PostgreSQL"/><br/><sub>PostgreSQL</sub></a></td><td align="center" width="120"><a href="https://learn.microsoft.com/dotnet/csharp/" title="C#"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/csharp/csharp-original.svg" width="56" height="56" alt="C#"/><br/><sub>C#</sub></a></td><td align="center" width="120"><a href="https://dotnet.microsoft.com/" title=".NET"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/dot-net/dot-net-original.svg" width="56" height="56" alt=".NET"/><br/><sub>.NET</sub></a></td><td align="center" width="120"><a href="https://www.microsoft.com/sql-server" title="MSSQL"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" width="56" height="56" alt="MSSQL"/><br/><sub>MSSQL</sub></a></td></tr>
</table>
</div>

<p align="center"><b>Tried and trusted</b><br/><sub>years of real projects, and I still ship with them when the job calls for it</sub></p>

<div align="center">
<table align="center">
<tr><td align="center" width="96"><a href="https://www.php.net" title="PHP"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/php/php-original.svg" width="44" height="44" alt="PHP"/><br/><sub>PHP</sub></a></td><td align="center" width="96"><a href="https://laravel.com/" title="Laravel"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/laravel/laravel-original.svg" width="44" height="44" alt="Laravel"/><br/><sub>Laravel</sub></a></td><td align="center" width="96"><a href="https://codeigniter.com" title="CodeIgniter"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/codeigniter/codeigniter-plain.svg" width="44" height="44" alt="CodeIgniter"/><br/><sub>CodeIgniter</sub></a></td><td align="center" width="96"><a href="https://angular.io" title="Angular"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/angularjs/angularjs-original.svg" width="44" height="44" alt="Angular"/><br/><sub>Angular</sub></a></td><td align="center" width="96"><a href="https://nodejs.org" title="Node.js"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/nodejs/nodejs-original.svg" width="44" height="44" alt="Node.js"/><br/><sub>Node.js</sub></a></td><td align="center" width="96"><a href="https://www.mysql.com/" title="MySQL"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/mysql/mysql-original.svg" width="44" height="44" alt="MySQL"/><br/><sub>MySQL</sub></a></td><td align="center" width="96"><a href="https://www.mongodb.com/" title="MongoDB"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/mongodb/mongodb-original.svg" width="44" height="44" alt="MongoDB"/><br/><sub>MongoDB</sub></a></td></tr>
<tr><td align="center" width="96"><a href="https://www.w3.org/html/" title="HTML5"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/html5/html5-original.svg" width="44" height="44" alt="HTML5"/><br/><sub>HTML5</sub></a></td><td align="center" width="96"><a href="https://www.w3schools.com/css/" title="CSS3"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/css3/css3-original.svg" width="44" height="44" alt="CSS3"/><br/><sub>CSS3</sub></a></td><td align="center" width="96"><a href="https://getbootstrap.com" title="Bootstrap"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/bootstrap/bootstrap-plain.svg" width="44" height="44" alt="Bootstrap"/><br/><sub>Bootstrap</sub></a></td><td align="center" width="96"><a href="https://jasmine.github.io/" title="Jasmine"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/jasmine/jasmine-original.svg" width="44" height="44" alt="Jasmine"/><br/><sub>Jasmine</sub></a></td><td align="center" width="96"><a href="https://www.cprogramming.com/" title="C"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/c/c-original.svg" width="44" height="44" alt="C"/><br/><sub>C</sub></a></td><td align="center" width="96"><a href="https://www.w3schools.com/cpp/" title="C++"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/cplusplus/cplusplus-original.svg" width="44" height="44" alt="C++"/><br/><sub>C++</sub></a></td></tr>
</table>
</div>

<p align="center"><b>Shipping with lately</b><br/><sub>front end, tooling and infrastructure</sub></p>

<div align="center">
<table align="center">
<tr><td align="center" width="96"><a href="https://www.typescriptlang.org" title="TypeScript"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/typescript/typescript-original.svg" width="44" height="44" alt="TypeScript"/><br/><sub>TypeScript</sub></a></td><td align="center" width="96"><a href="https://react.dev" title="React"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/react/react-original.svg" width="44" height="44" alt="React"/><br/><sub>React</sub></a></td><td align="center" width="96"><a href="https://nextjs.org" title="Next.js"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/nextdotjs/ffffff"><img src="https://cdn.simpleicons.org/nextdotjs/000000" width="44" height="44" alt="Next.js"/></picture><br/><sub>Next.js</sub></a></td><td align="center" width="96"><a href="https://vite.dev" title="Vite"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/vitejs/vitejs-original.svg" width="44" height="44" alt="Vite"/><br/><sub>Vite</sub></a></td><td align="center" width="96"><a href="https://tailwindcss.com" title="Tailwind"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/tailwindcss/tailwindcss-original.svg" width="44" height="44" alt="Tailwind"/><br/><sub>Tailwind</sub></a></td><td align="center" width="96"><a href="https://bun.sh" title="Bun"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/bun/bun-original.svg" width="44" height="44" alt="Bun"/><br/><sub>Bun</sub></a></td><td align="center" width="96"><a href="https://redis.io" title="Redis"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/redis/redis-original.svg" width="44" height="44" alt="Redis"/><br/><sub>Redis</sub></a></td></tr>
<tr><td align="center" width="96"><a href="https://www.prisma.io" title="Prisma"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/prisma/ffffff"><img src="https://cdn.simpleicons.org/prisma/0C344B" width="44" height="44" alt="Prisma"/></picture><br/><sub>Prisma</sub></a></td><td align="center" width="96"><a href="https://www.docker.com" title="Docker"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/docker/docker-original.svg" width="44" height="44" alt="Docker"/><br/><sub>Docker</sub></a></td><td align="center" width="96"><a href="https://playwright.dev" title="Playwright"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/playwright/playwright-original.svg" width="44" height="44" alt="Playwright"/><br/><sub>Playwright</sub></a></td><td align="center" width="96"><a href="https://www.electronjs.org" title="Electron"><img src="https://cdn.simpleicons.org/electron/47848F" width="44" height="44" alt="Electron"/><br/><sub>Electron</sub></a></td><td align="center" width="96"><a href="https://astro.build" title="Astro"><img src="https://cdn.simpleicons.org/astro/FF5D01" width="44" height="44" alt="Astro"/><br/><sub>Astro</sub></a></td><td align="center" width="96"><a href="https://vercel.com" title="Vercel"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/vercel/ffffff"><img src="https://cdn.simpleicons.org/vercel/000000" width="44" height="44" alt="Vercel"/></picture><br/><sub>Vercel</sub></a></td><td align="center" width="96"><a href="https://git-scm.com" title="Git"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/git/git-original.svg" width="44" height="44" alt="Git"/><br/><sub>Git</sub></a></td></tr>
</table>
</div>

<p align="center"><sub>Also: Entity Framework, Connect RPC, Protobuf, Drizzle, Caddy, Vitest.</sub></p>

## Public repos

Nearly everything above is private. These two are open, if you would like to read real code.

| Repo | What it is | Built with |
| :-- | :-- | :-- |
| [reddit-helper](https://github.com/dataautomators/reddit-helper) | A Chrome extension that adds an AI summary to Reddit posts, with related-post search and support for local or OpenAI-compatible models | `Plasmo` `React` `TypeScript` |
| [bulk-duckduckgo-search-tool](https://github.com/dataautomators/bulk-duckduckgo-search-tool) | A simple UI for running many DuckDuckGo searches at once, with filtering and a queue | `Next.js` `TypeScript` `Redis` |

## GitHub stats

<p align="center">
  <a href="https://github.com/thesturag">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=thesturag&amp;show_icons=true&amp;hide_border=true&amp;bg_color=0d1117&amp;title_color=58a6ff&amp;icon_color=58a6ff&amp;text_color=c9d1d9">
      <img src="https://github-readme-stats.vercel.app/api?username=thesturag&amp;show_icons=true&amp;hide_border=true&amp;bg_color=ffffff&amp;title_color=0969da&amp;icon_color=0969da&amp;text_color=24292f" alt="GitHub stats for thesturag"/>
    </picture>
  </a>
  <br/>
  <sub>Public activity only. Most of my work is in private repositories, so this card undercounts.</sub>
</p>

## Contact

Ask me about C#, .NET, ASP.NET, MSSQL, Go, PostgreSQL, or php, angular and networking. I read my email.

<p align="center">
  <a href="mailto:sadbin.alam@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge" alt="Email"/></a>
  <a href="https://linkedin.com/in/md-sad-bin-alam-turag-477aa7164"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"/></a>
  <a href="https://twitter.com/thesturag"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge" alt="X"/></a>
  <a href="https://fb.com/thesturag"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge" alt="Facebook"/></a>
  <a href="https://instagram.com/thesturag"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge" alt="Instagram"/></a>
  <a href="https://www.youtube.com/c/thesturag"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge" alt="YouTube"/></a>
</p>

<p align="center"><sub>Thanks for stopping by.</sub></p>
