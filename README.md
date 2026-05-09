<div align="center">

  <img src="https://img.shields.io/badge/status-beta-F5D327?style=for-the-badge&labelColor=1a1a1a" />
  <img src="https://img.shields.io/badge/license-GPL--3.0-1a5c38?style=for-the-badge&labelColor=1a1a1a" />

  <br>

  <h1>🏎️ Undercut</h1>
  <p><strong>The ultimate F1 predictions app — compete with friends across a full season.</strong></p>

  <a href="https://www.undercut.click">
    <img src="https://img.shields.io/badge/🌐_Live_App-undercut.click-1a1a1a?style=for-the-badge&labelColor=1a5c38" />
  </a>

</div>

---

## 📖 Overview

**Undercut** is a full-stack web application built for Formula 1 fans who want to make race predictions more competitive and social.

Before each Grand Prix, submit your predictions — fastest lap, race winner, first retirement, and more. Points are calculated automatically after the race, and you compete with your friends on a seasonal leaderboard.

Inspired by a Discord bot previously used by a community of **30,000+ users**, Undercut brings that experience to a proper web platform.

---

## ✨ Features

- 🏁 **Race Predictions** — Submit your picks before every Grand Prix of the season
- ⚡ **Automatic Scoring** — Points are calculated automatically based on real race results
- 👥 **Friend System** — Add friends and compete in private leaderboards
- 🏆 **Seasonal Rankings** — Track standings across the entire F1 season
- 📅 **F1 Calendar Integration** — Always in sync with the official race schedule
- 🔐 **Authentication** — Secure login and user account management

---

## 🖼️ Screenshots

> ℹ️ *Screenshots coming soon — the app is currently in public beta.*

<!-- Once i do screenshots
<div align="center">
  <img src="./assets/screenshot-home.png" width="80%" alt="Home page" />
  <img src="./assets/screenshot-predictions.png" width="80%" alt="Predictions page" />
  <img src="./assets/screenshot-leaderboard.png" width="80%" alt="Leaderboard" />
</div>
-->

---

## 🛠️ Tech Stack

### Frontend
| Tech | Role |
|------|------|
| React | UI framework |
| TypeScript | Type safety |
| Tailwind CSS | Styling |
| SCSS | Custom styles |

### Backend
| Tech | Role |
|------|------|
| NestJS | REST API framework |
| Prisma | ORM |
| MySQL | Database |
| BetterAuth | Authentication |

### Infrastructure & Tooling
| Tech | Role |
|------|------|
| Turborepo | Monorepo management |
| GitHub Actions | CI/CD |
| Vercel | Frontend deployment |
| Render | Backend deployment |

---

## 🏗️ Architecture

```
undercut/
├── apps/
|   ├── bot/             # Discord bot that manage undercut guild
│   ├── client/          # React frontend
│   └── server/          # NestJS backend
├── packages/
|   ├── types/           # Shared types
│   └── utils/           # Shared utils
└── turbo.json           # Turborepo config
```

---

## 🚧 Status

Undercut is currently in **public beta**. The app is live and usable, but you may encounter bugs or incomplete features. Development is ongoing and new updates ship regularly.

Found a bug or have a suggestion? [Open an issue](https://github.com/Zeikrom251/undercut.click/issues) — feedback is always welcome!

---

## 📬 Contact

Built with ❤️ by [Ryan — Zeikrom](https://github.com/Zeikrom251)

- 🌐 [undercut.click](https://www.undercut.click)
- 💬 Discord: [Join the server](https://discord.com/invite/7dm7MYMSSh)

</div>
