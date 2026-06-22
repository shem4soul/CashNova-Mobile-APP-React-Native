# 💸 CashNova

![Bun](https://img.shields.io/badge/Bun-1.2%2B-black?logo=bun)
![Expo](https://img.shields.io/badge/Expo-SDK%2055-000020?logo=expo)
![React Native](https://img.shields.io/badge/React%20Native-0.83-61dafb?logo=react)
![Hono](https://img.shields.io/badge/Hono-API-f97316)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?logo=postgresql)
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178c6?logo=typescript)

A modern cross-platform **Personal Finance & Invoice Management** application built with **React Native**, **Expo**, **Bun**, **Hono**, **PostgreSQL**, **Drizzle ORM**, and **Better Auth**.

CashNova enables users to securely manage wallets, record income and expenses, monitor financial activities, generate invoices, export PDF invoices, and gain financial insights through a clean mobile-first experience.

---

## ✨ Features

### Authentication

- Email & Password Authentication
- Secure Session Management
- Protected Routes
- Better Auth Integration

### User Management

- User Registration
- User Profile
- Onboarding Flow
- Profile Photo Upload

### Wallet Management

- Create Wallets
- Multiple Wallet Support
- Default Wallet Selection
- Wallet Balances

### Categories

- Income Categories
- Expense Categories
- Custom Categories

### Transactions

- Record Income
- Record Expenses
- Transaction History
- Transaction Filtering
- Financial Summaries

### Reports

- Dashboard Overview
- Monthly Reports
- Income Analysis
- Expense Analysis

### Invoice System

- Create Invoices
- Invoice Status Management
- PDF Generation
- Invoice Sharing
- Client Information

### Notifications

- Real-time Notifications
- Read/Unread Status

---

# 🏗 Architecture

```
                React Native App
                      │
              Expo Router Navigation
                      │
         TanStack Query + Better Auth
                      │
               Hono REST API
                      │
          Business Services Layer
                      │
            Drizzle ORM
                      │
              PostgreSQL Database
```

---

# 📁 Project Structure

```
CashNova-Mobile-APP-React-Native
│
├── apps
│   ├── native
│   │   ├── app
│   │   ├── components
│   │   ├── contexts
│   │   ├── hooks
│   │   ├── lib
│   │   └── types
│   │
│   └── server
│       └── src
│           ├── middleware
│           ├── routes
│           └── services
│
├── packages
│   ├── auth
│   ├── config
│   ├── db
│   ├── env
│   └── schema
│
├── turbo.json
└── package.json
```

---

# 🚀 Tech Stack

## Mobile

- React Native
- Expo
- Expo Router
- TypeScript
- HeroUI Native
- TanStack Query
- React Hook Form

## Backend

- Bun
- Hono
- Better Auth

## Database

- PostgreSQL
- Drizzle ORM
- Drizzle Kit

## Shared Packages

- Zod
- TurboRepo
- TypeScript

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/shem4soul/CashNova-Mobile-APP-React-Native.git

cd CashNova-Mobile-APP-React-Native
```

Install dependencies

```bash
bun install
```

---

# 🔑 Environment Variables

### Server

`apps/server/.env`

```env
DATABASE_URL=postgresql://postgres:password@localhost:5432/cashnova

BETTER_AUTH_SECRET=your_secret

BETTER_AUTH_URL=http://localhost:3000

CORS_ORIGIN=http://localhost:8081

NODE_ENV=development
```

### Native

`apps/native/.env`

```env
EXPO_PUBLIC_SERVER_URL=http://localhost:3000
```

---

# 🗄 Database

Push schema

```bash
bun run db:push
```

Generate migrations

```bash
bun run db:generate
```

Run migrations

```bash
bun run db:migrate
```

Open Drizzle Studio

```bash
bun run db:studio
```

---

# ▶️ Running the Project

Run everything

```bash
bun run dev
```

Run server only

```bash
bun run dev:server
```

Run mobile app only

```bash
bun run dev:native
```

---

# 📱 Application Workflow

1. Create an account
2. Complete onboarding
3. Create wallets
4. Create income & expense categories
5. Record transactions
6. View dashboard analytics
7. Generate invoices
8. Export invoices as PDF
9. Manage notifications

---

# 🔌 API Modules

- Authentication
- Wallets
- Categories
- Budgets
- Transactions
- Invoices
- Notifications

---

# 📸 Screenshots

Coming Soon

```
assets/screenshots/
```

---

# 🛣 Roadmap

- Budget Planner
- Savings Goals
- Multi-currency Support
- AI Spending Insights
- Dark Mode Improvements
- Bank Integration
- Cloud Backup
- Offline Support

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push your branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 👨‍💻 Author

### Emmanuel Seun Shittu

Backend & Full Stack Developer

GitHub

https://github.com/shem4soul

Portfolio

https://my-portfolio-trj2.vercel.app

LinkedIn

https://www.linkedin.com/in/emmanuelseunshittu/

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📄 License

This project is licensed under the MIT License.
