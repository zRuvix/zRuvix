<!-- ═══════════════════════════════════════════════════════════════════
     GitHub profile README for zRuvix
     Live presence: https://api.zruvix.com  ·  Docs: https://docs.zruvix.com/docs
     ═══════════════════════════════════════════════════════════════════ -->

<!-- ── TOP PURPLE BANNER ─────────────────────────────────────────── -->
<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,50:7c3aed,100:a855f7&height=220&section=header&text=zRuvix&fontSize=72&fontColor=ffffff&fontAlignY=35&desc=Beyond%20The%20Imagination.&descSize=18&descAlignY=55&animation=fadeIn"
    alt="zRuvix purple header banner"
    width="100%"
  />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=C084FC&center=true&vCenter=true&width=620&lines=I+build+products+with+AI.;Plan.+Design.+Ship.;Discord+presence+as+an+API.;Curious+builder+%7C+18Y" alt="typing animation" />
</p>

<!-- ── SOCIAL / QUICK LINKS ──────────────────────────────────────── -->
<p align="center">
  <a href="https://zruvix.com"><img src="https://img.shields.io/badge/Website-zruvix.com-7c3aed?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://docs.zruvix.com/docs"><img src="https://img.shields.io/badge/API%20Docs-docs.zruvix.com-a855f7?style=for-the-badge&logo=readthedocs&logoColor=white" alt="API Docs" /></a>
  <a href="https://api.zruvix.com"><img src="https://img.shields.io/badge/REST%20API-api.zruvix.com-9333ea?style=for-the-badge&logo=go&logoColor=white" alt="REST API" /></a>
  <a href="https://x.com/zRuvix_"><img src="https://img.shields.io/badge/X-@zRuvix__-6b21a8?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://t.me/zRuvix"><img src="https://img.shields.io/badge/Telegram-@zRuvix-5b21b6?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://discord.gg/rkJRchDy92"><img src="https://img.shields.io/badge/Discord-Join-4c1d95?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
</p>

---

## Hey, I'm **zRuvix**

> *I'm just curious about new stuff. If I like something, I try to build it myself.*

I'm not a traditional coder by background — I plan the product, design the flow, and use AI to ship things that actually work. Someone once called me an architect on day one. Fair. I care more about how a thing is structured than typing every line myself.

**Building / live**
- [Ruvix.store](https://ruvix.store) — private store
- [nullz.in](https://nullz.in) — temp mail
- [eronix.space](https://eronix.space) — AI image suite (next)
- [zRuvix API](https://docs.zruvix.com/docs) — Discord presence as a REST API + WebSocket

---

## Live Discord status

Powered by my own API — drop this card into any README:

```md
![status](https://api.zruvix.com/v1/users/1452582810421559306/card.svg)
```

<p align="center">
  <a href="https://docs.zruvix.com/docs/rest-api/status-card">
    <img
      src="https://api.zruvix.com/v1/users/1452582810421559306/card.svg"
      alt="zRuvix live Discord status card"
      width="400"
    />
  </a>
</p>

<p align="center">
  <sub>
    Docs:
    <a href="https://docs.zruvix.com/docs">Introduction</a> ·
    <a href="https://docs.zruvix.com/docs/rest-api/presence">Presence</a> ·
    <a href="https://docs.zruvix.com/docs/rest-api/status-card">Status card (SVG)</a> ·
    <a href="https://docs.zruvix.com/docs/websocket">WebSocket</a> ·
    <a href="https://docs.zruvix.com/docs/kv-store">KV Store</a>
  </sub>
</p>

---

## GitHub stats

<p align="center">
  <img
    height="165"
    src="https://github-readme-stats.vercel.app/api?username=zRuvix&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d0a1a&title_color=c084fc&icon_color=a855f7&text_color=e9d5ff&ring_color=7c3aed"
    alt="zRuvix GitHub stats"
  />
  <img
    height="165"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=zRuvix&layout=compact&hide_border=true&bg_color=0d0a1a&title_color=c084fc&text_color=e9d5ff&langs_count=8"
    alt="zRuvix top languages"
  />
</p>

<p align="center">
  <img
    src="https://streak-stats.demolab.com?user=zRuvix&theme=radical&hide_border=true&background=0d0a1a&ring=7c3aed&fire=a855f7&currStreakLabel=c084fc&sideLabels=e9d5ff&dates=c4b5fd&sideNums=c084fc&currStreakNum=c084fc"
    alt="zRuvix contribution streak"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=zRuvix&bg_color=0d0a1a&color=a855f7&line=7c3aed&point=c084fc&area=true&area_color=4c1d95&hide_border=true&custom_title=Contribution%20graph"
    alt="zRuvix contribution graph"
    width="100%"
  />
</p>

---

## zRuvix API — Discord presence as a service

[**Full documentation →**](https://docs.zruvix.com/docs)

A Go service that exposes live Discord presence and activities as a **REST API** and **WebSocket**, with a realtime key/value store. Lanyard-compatible shape so existing clients work with minimal changes.

| Feature | Endpoint / docs |
| --- | --- |
| Get presence | [`GET /v1/users/:id`](https://docs.zruvix.com/docs/rest-api/presence) |
| Live SVG status card | [`GET /v1/users/:id/card.svg`](https://docs.zruvix.com/docs/rest-api/status-card) |
| Now playing (Spotify / YT Music) | [`now_playing`](https://docs.zruvix.com/docs/now-playing) |
| KV store | [KV docs](https://docs.zruvix.com/docs/kv-store) |
| Realtime updates | [WebSocket](https://docs.zruvix.com/docs/websocket) |
| Bot commands | [Bot](https://docs.zruvix.com/docs/bot-commands) |

**Base URL:** `https://api.zruvix.com` · **Docs:** [docs.zruvix.com/docs](https://docs.zruvix.com/docs) · **v1.4.0**

```bash
# Quick example — public presence read
curl https://api.zruvix.com/v1/users/1452582810421559306
```

```json
{
  "success": true,
  "data": {
    "discord_user": { "id": "...", "username": "..." },
    "discord_status": "online",
    "active_on_discord_desktop": true,
    "listening_to_spotify": false,
    "now_playing": null,
    "activities": [],
    "kv": { "LOCATION": "Tokyo, Japan" }
  }
}
```

---

## Stack I reach for

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/AI%20%2F%20LLM-7c3aed?style=for-the-badge&logo=openai&logoColor=white" alt="AI" />
</p>

---

## Repos

| Repo | What it is |
| --- | --- |
| [REST-api-zRuvix](https://github.com/zRuvix/REST-api-zRuvix) | Presence REST API (Go) |
| [Docs-Api-zruvix](https://github.com/zRuvix/Docs-Api-zruvix) | API documentation site |
| [ApiPass-Suite](https://github.com/zRuvix/ApiPass-Suite) | API tooling suite (Python) |

---

## Connect

- Portfolio: [zruvix.com](https://zruvix.com)
- API docs: [docs.zruvix.com/docs](https://docs.zruvix.com/docs)
- X: [@zRuvix_](https://x.com/zRuvix_)
- Telegram: [@zRuvix](https://t.me/zRuvix)
- Discord: [Join the server](https://discord.gg/rkJRchDy92)

<p align="center">
  <em>“If it looks interesting, I want to build my own version of it.”</em>
  <br />
  <strong>— zRuvix</strong>
</p>

<!-- ── BOTTOM PURPLE BANNER ──────────────────────────────────────── -->
<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:a855f7,50:7c3aed,100:4c1d95&height=140&section=footer&text=Thanks%20for%20stopping%20by&fontSize=28&fontColor=ffffff&fontAlignY=70&animation=fadeIn"
    alt="zRuvix purple footer banner"
    width="100%"
  />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=zRuvix&label=Profile%20views&color=7c3aed&style=for-the-badge" alt="profile views" />
</p>
