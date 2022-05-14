# Card App 🎴🃏

Simple card app created with Typescript Stack

# Features

-Mutiple Routes for each action.
-Local Backend Database
-You can View, Create, Update, Delete simple cards.

# Stack

## Front End

- React ⚛
- React Router DOM 🔀
- Tailwind CSS 🐦

## Back End

- Fastify 🚀
- Prisma ORM 🅿
- SQLite ▪

# Deploy

The front end works in port 3000 and the backend works in the port 3001.

## Back End

```bash
npm install

npm run prisma-setup

npm run start
```

## Front End

```bash
npm install

npm run dev
```

To deploy a final build with static files:

```bash
npm run build

cd ./dist

npx serve -p 3000 -s
```
