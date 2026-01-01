# Lama Dev School Management Dashboard

## Getting Started

### PostgreSQL Database Setup

This project uses PostgreSQL running in Docker. The database is configured via Docker Compose.

**Start the database:**
```bash
docker-compose up -d
```

**Stop the database:**
```bash
docker-compose stop
```

**Reset the database (deletes all data):**
```bash
docker-compose down -v
```

**Database Connection Details:**
- Host: `localhost`
- Port: `5432`
- Database: `dashboard`
- User: `postgres`
- Password: `postgres`
- Connection URL: `postgresql://postgres:postgres@localhost:5432/dashboard`

Environment variables are configured in `.env.local`

### Development Server

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Lama Dev Youtube Channel](https://youtube.com/lamadev) 
- [Next.js](https://nextjs.org/learn)