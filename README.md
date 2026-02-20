# St. Austin Teaching Platform

Next.js app with PostgreSQL initialized via Prisma.

## Prerequisites

- Node.js 20+
- PostgreSQL running locally

## Setup

1. Install dependencies:

```bash
npm install
```

2. Copy env file and set your local database URL:

```bash
cp .env.example .env
```

3. Create the local database (example):

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

