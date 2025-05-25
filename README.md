# Accessly 🔐

**Accessly** is a lightweight, developer-friendly authentication and authorization framework built in **Go**, using **JWT** for secure, stateless session management. It’s designed to be fast, minimal, and extensible — ideal for modern web and mobile applications.

---

## 🚀 Features

- 🛡️ JWT-based Authentication (stateless)
- 🔁 Refresh Tokens with HttpOnly Cookies
- 👥 User Registration and Login
- ✅ Email + Password Auth (OAuth coming soon)
- 🔓 Role-Based Access Control (RBAC)
- 🌍 RESTful API
- 📦 SDK-ready architecture
- 🧪 Unit-tested core logic

---

## 🧱 Tech Stack

| Layer         | Tech                          |
|---------------|-------------------------------|
| Backend       | [Go](https://golang.org)      |
| Framework     | [Fiber](https://gofiber.io) or [Echo](https://echo.labstack.com) |
| Auth          | JWT (HS256 or RS256)          |
| Database      | PostgreSQL                    |
| ORM           | [GORM](https://gorm.io)       |
| Caching       | Redis (optional)              |
| Container     | Docker                        |

---

## 📂 Project Structure

```bash
accessly/
├── cmd/                # Entry point (main.go)
├── internal/
│   ├── auth/           # JWT logic, token gen/verify
│   ├── handlers/       # HTTP handlers
│   ├── middleware/     # Auth & role checks
│   ├── models/         # DB models
│   └── utils/          # Helper functions
├── config/             # Environment configs
├── migrations/         # DB schema
└── README.md

