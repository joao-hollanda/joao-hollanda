<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=250&text=João%20Hollanda&fontSize=70&color=0:0f0c29,50:302b63,100:24243e&fontColor=ffffff&stroke=6c63ff&strokeWidth=2&animation=fadeIn&desc=building%20things%20that%20matter&descSize=18&descAlignY=72&descAlign=50" width="100%"/>
</div>

<br/>

<div align="center">```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   $ whoami                                                       ║
║   > João Hollanda — Full Stack Dev, 18, Alfenas MG 🇧🇷           ║
║                                                                  ║
║   $ cat about.txt                                                ║
║   > CS @ Unifal (2026)                                           ║
║   > 580h Full Stack Bootcamp — Itera360                          ║
║   > Dev Monitor & PR Reviewer                                    ║
║   > Building: Learnly                                            ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

<br/>

## `~/projects/learnly` &nbsp;★ flagship

> **Learnly** é uma plataforma de preparação para o ENEM com simulados e feedback por questão gerado por IA.  
> Saiu de projeto pessoal para **oferta real de deploy em escola** após apresentação pública.

```bash
$ cat learnly/stack.json
{
  "backend":  ["C#", ".NET 8", "Clean Architecture", "EF Core", "PostgreSQL/Neon"],
  "frontend": ["React", "TypeScript", "TanStack Query", "CSS Modules"],
  "auth":     "JWT + HttpOnly Cookies",
  "ai":       "Groq API — llama-3.1-8b-instant",
  "db":       "PostgreSQL via Neon (serverless)"
}

$ cat learnly/highlights.md
  [✓] IDOR prevention — userId lido dos claims JWT, nunca da rota
  [✓] AI feedback batch — uma chamada Groq por simulado, por questão
  [✓] TanStack Query cache — staleTime: Infinity + invalidateQueries cross-page
  [✓] Pitch page — market sizing, pricing tiers, modelo de negócio
  [✓] Load testing — estratégia k6/Artillery em andamento
  [✓] Oferta de deploy em escola após apresentação 🎓

$ git log --oneline learnly/
  a3f91c  feat: AI feedback por questão via Groq (batch)
  b82de1  fix: IDOR em todos os controllers via JWT claims
  c14fa2  perf: cache TanStack Query + invalidação coordenada
  d09b3e  feat: engine de simulado + cálculo de nota final
  e71ca9  build: pitch page com market sizing e pricing
  f30d11  sec: JWT HttpOnly + refresh token queue (Axios)
```

<br/>

[![Learnly API](https://img.shields.io/badge/Learnly.API-repo-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://github.com/joao-hollanda/Learnly.API)
[![Learnly APP](https://img.shields.io/badge/Learnly.APP-repo-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://github.com/joao-hollanda/Learnly.APP)

<br/>

---

<br/>

## `~/stack`

```
Language    C# ████████████████████░░░  primary
            JavaScript/TS ███████████░░░░░░░░░  frontend
            SQL ████████░░░░░░░░░░░░░  queries & migrations

Backend     .NET 8 · Clean Architecture · EF Core · REST API
Frontend    React · TanStack Query · CSS Modules
Database    PostgreSQL · Neon · SQL Server
Auth        JWT · HttpOnly Cookies · Refresh Token rotation
AI          Groq API · prompt engineering · batch inference
Tooling     Git · Linux · Scrum · code review
```

<br/>

---

<br/>

## `~/stats`

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=joao-hollanda&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&ring_color=58a6ff&include_all_commits=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=joao-hollanda&layout=compact&langs_count=5&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=joao-hollanda&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" />
</div>

<br/>

---

<br/>

## `~/contact`

```bash
$ cat links.sh

  open https://www.hollanda.dev
  open https://linkedin.com/in/joao-victor-hollanda
  open https://github.com/joao-hollanda
```

<br/>

<div align="center">

![](https://komarev.com/ghpvc/?username=joao-hollanda&style=flat-square&color=58a6ff&label=profile+views)

</div>
  
  [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=3000&pause=800&color=6C63FF&center=true&vCenter=true&multiline=false&width=550&lines=Full+Stack+Dev+%7C+C%23+%2B+.NET+%2B+React;Building+Learnly+%E2%80%94+ENEM+prep+powered+by+AI;Clean+Architecture+%7C+EF+Core+%7C+PostgreSQL;18yo+%7C+CS+%40+Unifal+%7C+Alfenas%2C+MG+%F0%9F%87%A7%F0%9F%87%B7)](https://git.io/typing-svg)

</div>

<br/>

---

<br/>

<table width="100%">
<tr>
<td width="55%" valign="top">

### `whoami`

```yaml
name:      João Victor Hollanda
age:       18
city:      Alfenas, Minas Gerais
study:     CS @ Unifal — 1st semester
training:  580h Full Stack Bootcamp (Itera360)
           └─ Scrum, sprints, code review, PRs

role:      Dev Monitor & PR Reviewer
stack:     C# / .NET / React / PostgreSQL

flagship:  Learnly 🚀
           └─ ENEM prep platform with AI feedback
           └─ Got a school deployment offer after demo

focus:     Real products > portfolio pieces
           Honest feedback > empty praise
           Why > How
```

</td>
<td width="45%" valign="top">

### `git log --me`

```bash
[Learnly]  feat: AI per-question feedback (Groq)
[Learnly]  fix: IDOR via JWT claims on all routes
[Learnly]  perf: TanStack Query staleTime + cache
[Learnly]  feat: simulado engine + scoring logic
[Learnly]  build: pitch page w/ market sizing
[Learnly]  infra: load test strategy (k6)
[Monitor]  review: PR batch @ Itera360 platform
[Monitor]  refactor: controller → use case split
```

</td>
</tr>
</table>

<br/>

---

<br/>

## 🛠 Stack

<div align="center">

#### Backend
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-1a1a2e?style=flat-square&logoColor=white)
![REST](https://img.shields.io/badge/REST_API-6c63ff?style=flat-square)
![JWT](https://img.shields.io/badge/JWT_HttpOnly-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

#### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![CSS Modules](https://img.shields.io/badge/CSS_Modules-000?style=flat-square&logo=cssmodules&logoColor=white)

#### Data & Infra
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Neon](https://img.shields.io/badge/Neon_DB-00E699?style=flat-square&logo=neon&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

#### AI & Tooling
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Scrum](https://img.shields.io/badge/Scrum-009FDA?style=flat-square&logo=scrumalliance&logoColor=white)

</div>

<br/>

---

<br/>

## 🚀 Learnly — Flagship Project

> Plataforma de preparação para o ENEM com simulados adaptativos e feedback individualizado gerado por IA.  
> Construída do zero, com arquitetura de produção, segurança real e visão de produto.

<br/>

<div align="center">

| | |
|:---|:---|
| 🏛 **Arquitetura** | Clean Architecture · Use Cases · Repository Pattern · separação de camadas bem definida |
| 🔐 **Segurança** | JWT com HttpOnly cookies · IDOR prevention via claims · sem exposição de `ex.Message` |
| 🤖 **IA** | Groq API (`llama-3.1-8b-instant`) · batch único por simulado · feedback por questão |
| ⚡ **Performance** | TanStack Query `staleTime: Infinity` · `invalidateQueries` cross-page · N+1 prevention no EF Core |
| 📊 **Produto** | Pitch page com market sizing · modelo de negócio · oferta real de deploy em escola |
| 🧪 **Escalabilidade** | Estratégia de load test com k6 / Artillery em andamento |

</div>

<br/>

<div align="center">

[![Learnly API](https://img.shields.io/badge/Learnly.API-C%23%20%7C%20.NET%20%7C%20Clean%20Arch-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://github.com/joao-hollanda/Learnly.API)
&nbsp;
[![Learnly APP](https://img.shields.io/badge/Learnly.APP-React%20%7C%20TanStack%20Query-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://github.com/joao-hollanda/Learnly.APP)

</div>

<br/>

---

<br/>

## 📊 Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=joao-hollanda&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=6c63ff&icon_color=6c63ff&text_color=c9d1d9&ring_color=6c63ff" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=joao-hollanda&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6c63ff&text_color=c9d1d9" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=joao-hollanda&theme=tokyonight&hide_border=true&background=0D1117&ring=6c63ff&fire=6c63ff&currStreakLabel=6c63ff" />
</div>

<br/>

---

<br/>

## 📈 Jornada

```
2023  └─ Iniciou estudos em C# e .NET
2024  ├─ Bootcamp Full Stack @ Itera360 (580h)
      │   ├─ Scrum, sprints, code review em time
      │   └─ Ambiente de simulação profissional real
      ├─ Construiu Learnly do zero
      │   ├─ Auth JWT, Clean Architecture, EF Core, React
      │   └─ Integração com Groq API (AI feedback)
      └─ Dev Monitor @ Itera360 — PR reviews + mentoria
2025  ├─ Ingressou em Ciência da Computação — Unifal
      ├─ Apresentação do Learnly → oferta de deploy em escola 🎓
      ├─ Pitch page com market sizing + modelo de negócio
      └─ Estratégia de escalabilidade em andamento
2026  └─ Continuando a construir → próxima milestone ...
```

<br/>

---

<br/>

<div align="center">

### Onde me encontrar

[![Portfolio](https://img.shields.io/badge/hollanda.dev-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.hollanda.dev)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/joao-victor-hollanda)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/joao-hollanda)

<br/>

![Visitors](https://komarev.com/ghpvc/?username=joao-hollanda&style=flat-square&color=6c63ff&label=visitors)

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer&reversal=false" width="100%" />
</div>
