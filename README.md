```
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
