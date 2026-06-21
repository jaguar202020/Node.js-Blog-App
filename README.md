# YouTube Blog

Simple Node.js blog application using Express, EJS and MongoDB.

## Features
- Create and view blog posts
- File uploads for images
- User authentication with JWT

## Requirements
- Node.js >= 16
- MongoDB

## Install

1. Install dependencies

```bash
npm install
```

2. Create a `.env` file with at least:

- `MONGODB_URI` — your MongoDB connection string
- `JWT_SECRET` — secret for signing JWTs
- `PORT` — optional, defaults to 3000

## Run

Start in development:

```bash
npm run dev
```

Start production:

```bash
npm start
```

## Project Structure

- `app.js`, `index.js` — application entry points
- `routes/` — route definitions
- `controllers/` — request handlers
- `models/` — Mongoose models
- `views/` — EJS templates
- `public/` — static assets and uploads

## Notes
- Add any local secrets to `.env` (this file is gitignored).

## License
ISC
# Node.js-Blog-App
A full-stack blogging platform built with Node.js, Express, MongoDB, and EJS featuring authentication, blog management, image uploads, and MVC architecture.
