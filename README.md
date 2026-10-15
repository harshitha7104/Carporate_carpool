# Corporate Carpool

A carpooling web application built with React, Vite, Express, and MongoDB.

## Features

- User signup and registration
- Ride offer form
- Carpool trip details collection
- Responsive frontend UI
- Backend API with MongoDB integration

## Tech Stack

- Frontend: React + Vite
- Backend: Node.js + Express
- Database: MongoDB
- Styling: CSS modules

## Project Structure

```bash
corporate-carpool/
├── backend/
│   ├── app.js
│   ├── package.json
│   └── models/
├── front-end/
│   └── carpool/
│       ├── package.json
│       ├── vite.config.js
│       └── src/
├── README.md
└── .gitignore
```

## Local Development

### 1) Start the backend

```bash
cd backend
npm install
npm start
```

The backend runs on:

```bash
http://localhost:4000
```

### 2) Start the frontend

```bash
cd front-end/carpool
npm install
npm run dev -- --host 0.0.0.0
```

The frontend runs on:

```bash
http://localhost:5173
```

## Deployment Notes

This project is configured for a single-host friendly deployment pattern:

- Frontend uses relative API paths instead of hardcoded localhost URLs
- Vite dev server proxies `/api` requests to the backend
- Backend can serve the built frontend in production mode

## GitHub

Repository:

https://github.com/harshitha7104/corporate-carpool

## License

This project is for educational/demo use.
