```console
                                 __
   _________ ___  ______  ____ _/ /__
  / ___/ __ `/ / / / __ \/ __ `/ //_/
 / /  / /_/ / /_/ / / / / /_/ / ,<
/_/   \__,_/\__,_/_/ /_/\__,_/_/|_|

raunak@i-Rony-op:~$ whoami && cat /etc/motd
raunak
full stack dev. pixels to databases. 60fps or it didn't ship.
raunak@i-Rony-op:~$ _
```
```console
raunak@github:~$ ss -tulpn | grep raunak
```

| `PID` | `SERVICE` | `ENDPOINT` | `STATE` |
|:-:|:--|:--|:-:|
| `001` | `linkedin` | [`/in/raunak-sharma-5393a9248  ↗`](https://www.linkedin.com/in/raunak-sharma-5393a9248/) | `LISTEN` |
| `002` | `x` | [`@RONY38434557  ↗`](https://x.com/RONY38434557) | `LISTEN` |
| `003` | `instagram` | [`@raunakksharmaa  ↗`](https://www.instagram.com/raunakksharmaa/) | `LISTEN` |
| `004` | `smtp` | [`raunaksharma6205@gmail.com  ↗`](mailto:raunaksharma6205@gmail.com) | `LISTEN` |
| `005` | `git` | [`github.com/i-Rony-op  ↗`](https://github.com/i-Rony-op) | `LISTEN` |

<img src="https://komarev.com/ghpvc/?username=i-Rony-op&style=flat-square&color=0d1117&labelColor=161b22&label=visitors+%5Bcat+%2Fvar%2Flog%2Fhits%5D" />

<br/>

```console
raunak@github:~$ neofetch
  ┌──────────────────┐   raunak@i-Rony-op
  │ ●  ●  ●          │   ─────────────────────────────────────────
  ├──────────────────┤   OS        : Full Stack Developer
  │ $ whoami         │   Host      : Maritime Support Solutions
  │ > raunak         │   Location  : Pune, India
  │                  │   Kernel    : JavaScript / TypeScript / Python
  │ $ git commit     │   Shell     : zsh + vim motions
  │ > ship it        │   Frontend  : React · Three.js · GSAP · Tailwind
  │                  │   Backend   : Django · Node.js · Express · REST
  │ $ npm run dev    │   Data      : PostgreSQL · MySQL · MongoDB
  │ > 60fps ▌        │   Cloud     : Azure · Vercel · Docker · CI/CD
  │                  │   Uptime    : shipped a platform for 430+ users
  └──────────────────┘   Packages  : too many (npm i, regret later)
      ╚═══════════╝    
                         ███ ███ ███ ███ ███ ███ ███ ███
```

### `~/raunak $ cat developer.ts`

```ts
interface Engineer { name: string; role: string; ships: string[]; }

export const raunak: Engineer & Record<string, unknown> = {
  name:  "raunak",
  role:  "Full Stack Developer",
  ships: [
    "immersive 3D & motion-driven frontends",       // Three.js · R3F · GSAP
    "production web apps with real users",          // 430+ and counting
    "clean REST APIs and well-modelled databases",  // Django · Node.js · SQL
  ],
  philosophy: [
    "Performance is a feature — 60fps or it didn't ship.",
    "Design and engineering are the same job.",
    "Read the error message. Then read it again.",
  ],
  currentlyLearning: ["Next.js App Router", "WebGL shaders (GLSL)", "system design"],
  pairsWith: ["Claude", "ChatGPT"],   // rubber ducks with opinions
  coffee: Infinity,
};
```

### `~/raunak $ tree ./stack -L 1`

<table>
<tr>
<td width="140"><b> Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,html,css,tailwind,sass,redux,vite&perline=10" /></td>
</tr>
<tr>
<td><b> 3D & Motion</b></td>
<td>
<img src="https://skillicons.dev/icons?i=threejs&perline=10" />
<img src="https://img.shields.io/badge/GSAP-0AE448?style=for-the-badge&logo=greensock&logoColor=black" />
<img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" />
<img src="https://img.shields.io/badge/R3F-000000?style=for-the-badge&logo=threedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Lenis-1a1a1a?style=for-the-badge" />
</td>
</tr>
<tr>
<td><b> Backend</b></td>
<td><img src="https://skillicons.dev/icons?i=nodejs,express,python,django,fastapi&perline=10" /></td>
</tr>
<tr>
<td><b> Data</b></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis&perline=10" /></td>
</tr>
<tr>
<td><b> DevOps</b></td>
<td><img src="https://skillicons.dev/icons?i=azure,vercel,docker,githubactions,linux,nginx&perline=10" /></td>
</tr>
<tr>
<td><b> Tools</b></td>
<td><img src="https://skillicons.dev/icons?i=git,github,vscode,vim,postman,figma&perline=10" /></td>
</tr>
</table>

### `~/raunak $ cat how-i-build.md`

```mermaid
flowchart LR
    U([👤 User]) --> FE["⚛️ React / Three.js<br/>GSAP · Tailwind"]
    FE -- REST / JSON --> API["🐍 Django · 🟢 Node.js<br/>auth · business logic"]
    API --> DB[("🗄️ PostgreSQL / MySQL")]
    API --> C[("⚡ Redis cache")]
    FE -. deploy .-> V["▲ Vercel"]
    API -. deploy .-> AZ["☁️ Azure · 🐳 Docker"]
```

### `~/raunak $ ls -la ./projects`

| | Project | What it does | Stack | Live |
|:-:|---|---|---|:-:|
|  | **Symbi Time Table** | Timetable management platform for an institute: Django backend, animated HTML/CSS/JS frontend, deployed on Azure | Django · JS · GSAP · Azure | — |
|  | **Re-Designn** | Interactive React UI with timeline animation and buttery smooth scroll | React · Framer Motion · GSAP · Lenis | [▶](https://re-design-rony.vercel.app/) |
|  | **Cyberpunk** | 3D landing page with GLTF models, HDR lighting and post-processing | Three.js · GSAP | [▶](https://cyberpunk-three-js.vercel.app/) |
|  | **The Planets** | Orbiting textured planets with HDR lighting and orbit controls | Three.js · GSAP | [▶](https://the-planets-rony.vercel.app/) |
|  | **Obys Agency** | Agency site with Locomotive Scroll and fluid GSAP timelines | HTML · CSS · JS | [▶](https://i-rony-op.github.io/Obys_Agency_Clone/) |
|  | **Rayy Bannnn** | Ray-Ban landing page redesign with smooth navigation | GSAP · JS | [▶](https://i-rony-op.github.io/SheryJS_Modern_Site/) |

### `~/raunak $ git log --stat --all | analyze`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=i-Rony-op&show_icons=true&hide_border=true&bg_color=0d1117&title_color=e8b04b&icon_color=e8b04b&text_color=c9d1d9&include_all_commits=true&count_private=true&rank_icon=github" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=i-Rony-op&layout=compact&hide_border=true&bg_color=0d1117&title_color=e8b04b&text_color=c9d1d9&langs_count=8" />

<img src="https://streak-stats.demolab.com?user=i-Rony-op&hide_border=true&background=0d1117&ring=e8b04b&fire=e8b04b&currStreakLabel=e8b04b&sideLabels=c9d1d9&dates=8b949e&currStreakNum=f8f6f1&sideNums=f8f6f1" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=i-Rony-op&bg_color=0d1117&color=c9d1d9&line=e8b04b&point=f8f6f1&area=true&area_color=e8b04b&hide_border=true&custom_title=commits%20over%20time" />

</div>

### `~/raunak $ ./snake --eat contributions`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/i-Rony-op/i-Rony-op/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/i-Rony-op/i-Rony-op/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/i-Rony-op/i-Rony-op/output/github-snake.svg" />
</picture>

<div align="center">

```console
raunak@github:~$ ./hire-me.sh
[ok] full stack roles · creative dev · freelance collabs
[ok] response time: < 24h  →  raunaksharma6205@gmail.com
```

</div>
