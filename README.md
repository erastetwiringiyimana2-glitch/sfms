# SFMS — School Fee Management System

MongoDB + Express + React: JWT auth, students, payments, and date-range reports.

## Installation

```bash
cd backend && npm install
cd ../frontend && npm install
```

## Run Development Server

Backend (port 5000):

```bash
cd backend
cp .env.example .env
npm run dev
```

Frontend (port 5173):

```bash
cd frontend
npm run dev
```

## Environment Variables

| Variable | Description |
|----------|-------------|
| PORT | API port (5000) |
| JWT_SECRET | Secret for JWT tokens |
| MONGO_URI | MongoDB connection string |

## Folder Structure

```
sfms/
├── README.md
├── backend/
└── frontend/
```
