# St. Austin Teaching Platform

Next.js application with PostgreSQL via Prisma.

## Prerequisites

- Node.js 20+
- PostgreSQL running locally on your machine

## Setup

1. Install dependencies:

```bash
npm install
```

2. Set your database connection string:

```bash
cp .env.example .env
# Edit .env and provide a valid DATABASE_URL
```

3. Create your database:

```bash
createdb st_austin
```

4. Run migration and generate Prisma client:

```bash
npm run db:migrate
```

5. Start the app:

```bash
npm run dev
```

## Database Scripts

- `npm run db:generate` generates Prisma client
- `npm run db:migrate` runs Prisma migrations in dev
- `npm run db:studio` opens Prisma Studio
