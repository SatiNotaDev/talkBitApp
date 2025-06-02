# 🧠 Talkbit.app

**Talkbit** is a modern full-stack platform for embedding AI assistants (powered by OpenAI) into any website. It supports full customization, analytics, and bot management.

---

## 🚀 Features

- Embeddable chatbot widget (GPT-powered)
- Admin panel with bot creation and customization
- Welcome message, color, and language settings
- Chat history storage per site
- JWT authentication + role-based access
- OpenAI API integration (GPT-3.5 / 4)
- Real-time communication (WebSocket ready)
- Docker-based dev environment

---

## 🧰 Tech Stack

| Layer      | Technology                  |
|------------|-----------------------------|
| Frontend   | Next.js, TailwindCSS, shadcn/ui |
| Backend    | NestJS, Prisma, PostgreSQL  |
| Auth       | JWT + Refresh Tokens        |
| Realtime   | WebSocket (Socket.IO)       |
| AI Engine  | OpenAI API (GPT)            |
| DevOps     | Docker, Docker Compose      |
| Cache/Queue| Redis                       |

---

## 📦 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/talkbit.git
cd talkbit
