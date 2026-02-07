# GridGuard AI

AI-powered power grid monitoring dashboard with live anomaly detection, a US map view, and explainable risk analysis.

## What it does
- Simulates grid telemetry across US nodes (load, voltage, frequency)
- Detects anomalies and ranks severity
- Shows live alerts, node history, and analysis
- Persists incident history in Postgres

## Tech stack
- Frontend: Next.js (App Router) + TypeScript + Tailwind + Leaflet
- Backend: FastAPI (Python) + WebSockets
- DB: PostgreSQL (Docker)

## Run locally

### Backend
bash
docker compose up --build

### Frontend
cd frontend
npm install
npm run dev
