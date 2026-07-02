# 🚶 StepTracker - Walking Distance Counter

Track your walks, count steps, measure distance, and reach your fitness goals!

![StepTracker](https://img.shields.io/badge/StepTracker-v1.0.0-emerald)

## Features

- ⏱️ **Real-time Step Tracker** - Count steps with live timer
- 📊 **Dashboard** - Weekly charts and statistics
- 🎯 **Goals** - Set and track walking goals
- 🗺️ **Map View** - Visualize your walks
- 📝 **Walk History** - Full CRUD for all walks
- 🔐 **Authentication** - Secure user accounts

## Tech Stack

- **Frontend**: Next.js 16, React 19, Tailwind CSS
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL with Drizzle ORM
- **Auth**: JWT with HTTP-only cookies

## Getting Started

```bash
# Install dependencies
npm install

# Set up environment
cp .env.example .env

# Push database schema
npx drizzle-kit push

# Run development server
npm run dev
```

## Environment Variables

```
DATABASE_URL=postgresql://user:pass@host:5432/dbname
JWT_SECRET=your-secret-key
```

## Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

## License

MIT
