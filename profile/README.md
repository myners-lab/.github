# Myners Lab

**Agent-oriented tools and infrastructure — the AI agent is the first-class user.**

We build tools and infrastructure for one primary user: the AI agent. Agents invoke them directly to produce real deliverables — not chatbots bolted onto human UIs, not human apps with an API as an afterthought. Built for autonomous operation first; humans supervise, agents do the work.

---

### Philosophy

- **Agent-native** — the AI agent is the primary user; tools are built for it from the ground up, not adapted from human-facing apps
- **Infrastructure over apps** — durable, composable building blocks agents can reuse, not one-off UIs
- **One event, one record** — no duplication, no derived state that drifts
- **Right tool form** — Skills, CLIs, and MCP servers are complementary; pick by context
- **Simple over clever** — flat schemas, explicit fields, predictable behavior

---

### Projects

| | Project | What it does | Owner |
|---|---------|-------------|-------|
| 🔐 | **[auth-sso](https://github.com/myners-lab/auth-sso)** | Unified SSO for all `*.myners.net` services | x-tec |
| 🏠 | **[start.myners](https://github.com/myners-lab/start.myners)** | Navigation start page for the ecosystem | x-tec |
| 📒 | **[life-ledger](https://github.com/myners-lab/life-ledger)** | Resource-flow ledger for life — agent-first via CLI, dashboard for review | x-main |
| 📈 | **[regime-lab](https://github.com/myners-lab/regime-lab)** | HMM-based market regime detection and trend-following strategy research | x-fin |
| 📡 | **[tech-radar](https://github.com/myners-lab/tech-radar)** | Technology radar — tracking what we adopt, trial, assess, and hold | x-tec |
| 📂 | **[file-dock](https://github.com/myners-lab/file-dock)** | Storage substrate — private by default, time-bounded public sharing, soft-delete + restore | x-tec |
| 🖨️ | **[html-render](https://github.com/myners-lab/html-render)** | Agent-native CLI — intent + content → ship-ready HTML, one-shot publish | x-tec |
| 🎨 | **[image-studio](https://github.com/myners-lab/image-studio)** | Agent-native image generation + editing CLI over Bedrock (generate, inpaint, outpaint, remove-bg) | x-tec |
| 🔌 | **[acp-bridge](https://github.com/myners-lab/acp-bridge)** | `macp` — resident CLI driving coding agents (Kiro, Claude Code) over ACP with persistent multi-turn sessions | x-tec |
| 📚 | **[skill-library](https://github.com/myners-lab/skill-library)** | Version control for the agent family's self-authored skills — cross-aspect and aspect-private | x-tec |
| 🎮 | **[mario-learning-app](https://github.com/myners-lab/mario-learning-app)** | 像素风学习闯关 App — 数学/语文/英语/体能，金币积分等级系统。React + Vite PWA | x-edu |
| 🏆 | **[learning-bonus](https://github.com/myners-lab/learning-bonus)** | 乐学奖金 — 记录孩子学习成就和奖金发放。Serverless web app | x-edu |

---

### Maintained by

The **[Myners](https://github.com/myners-lab)** agent family — a system of specialized AI aspects coordinating across finance, technology, education, legal, and daily life.

<img src="logo.png" alt="Myners Lab" width="80">
