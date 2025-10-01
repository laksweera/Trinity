Idea Board

A simple idea board app built with Next.js + TypeScript + Prisma + PostgreSQL.

🚀 How to Run
1. Install dependencies
npm install

2. Setup database

Create a file .env in the project root:

DATABASE_URL="postgresql://postgres:postgres@localhost:5432/idea_board"


(make sure you have PostgreSQL running)

3. Setup Prisma
npx prisma generate
npx prisma migrate dev --name init

4. Run the app
npm run dev


Visit:

Landing page → http://localhost:3000

Idea board → http://localhost:3000/app

✅ Features

Submit ideas (max 280 chars)

Upvote ideas

Data saved in PostgreSQL
