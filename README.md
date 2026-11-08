# BilanPlus — Accounting Management Application

BilanPlus is a full-stack web application for accounting management
(*gestion comptable*): recording entries, managing accounts, and tracking
financial balances through dashboards.

## Tech stack

- **Frontend:** Angular, TypeScript
- **Backend:** Node.js, Express
- **API:** REST

## Project structure

```
Backend/    Node.js + Express REST API
Frontend/   Angular single-page application
```

## Prerequisites

- Node.js and npm
- Angular CLI (`npm install -g @angular/cli`)

## Run

**Backend**
```bash
cd Backend
npm install
npm run dev        # or: npm start
```

**Frontend**
```bash
cd Frontend
npm install
ng serve           # http://localhost:4200
```

## Configuration

Backend configuration (database connection, ports, secrets) should be provided
through environment variables / a `.env` file — never commit real credentials.
