# Acme Dashboard

A full-featured financial dashboard application built with Next.js, featuring authentication, database integration, and real-time data visualization.

![Acme Dashboard Preview](/public/hero-desktop.png)

## Features

- **User Authentication**: Secure login with NextAuth.js
- **Invoice Management**: Create, edit, and delete invoices
- **Customer Database**: Manage customer information
- **Dashboard Analytics**: Revenue charts and recent activity
- **Search & Pagination**: Filter and navigate through data efficiently
- **Responsive Design**: Optimized for all screen sizes

## Tech Stack

- [Next.js 16](https://nextjs.org/) - React framework with App Router
- [React 19](https://react.dev/) - UI library
- [Tailwind CSS 4](https://tailwindcss.com/) - Styling
- [TypeScript](https://www.typescriptlang.org/) - Type safety
- [NextAuth.js v5](https://next-auth.js.org/) - Authentication
- [Vercel Postgres](https://vercel.com/storage/postgres) - Database
- [Zod 4](https://zod.dev/) - Schema validation

## Getting Started

```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Seed the database
npm run seed

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the app.

## Demo Credentials

```
Email: user@nextmail.com
Password: 123456
```

## Live Demo

[https://nextjs-dashboard-pied-psi.vercel.app](https://nextjs-dashboard-pied-psi.vercel.app)

## Project Structure

```
app/
├── dashboard/     # Protected dashboard routes
├── login/         # Authentication page
├── lib/           # Utilities and data fetching
└── ui/            # Reusable UI components
```

---

*Based on the official [Next.js Learn Course](https://nextjs.org/learn)*
