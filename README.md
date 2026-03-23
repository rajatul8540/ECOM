# Ecom

A Next.js ecommerce application with user authentication using NextAuth and Prisma with PostgreSQL.

## Setup

1. Install dependencies:
   ```bash
   yarn install
   ```

2. Set up PostgreSQL database and update `.env` with your `DATABASE_URL`.

3. Run Prisma migrations:
   ```bash
   npx prisma migrate dev
   ```

4. Generate Prisma client:
   ```bash
   npx prisma generate
   ```

5. Run the development server:
   ```bash
   yarn dev
   ```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Features

- User registration and login
- PostgreSQL database with Prisma ORM
- Next.js App Router
- Tailwind CSS for styling