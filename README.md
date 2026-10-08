# BRING RAIDO

BRING RAIDO is a multi-service delivery and commerce platform.

## Final scope

- Customer web/app
- Restaurant partner
- Delivery Captain
- Admin
- Food delivery
- BRING MART / quick commerce
- Parcel delivery
- Payments
- Maps
- Notifications
- Coupons
- Rate cards
- Commission and settlements
- Android APK

**Taxi/ride-hailing is intentionally excluded.**

## Phase 1 foundation

This starter contains:
- React + Vite customer web foundation
- Node.js + Express API foundation
- Prisma + PostgreSQL schema foundation
- Shared environment examples
- Health endpoint
- Initial role model

## Local requirements

- Node.js 22+
- Git
- PostgreSQL (local) OR Supabase PostgreSQL later

## Run

### Backend
```bash
cd backend
copy .env.example .env
npm install
npx prisma generate
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

Backend: http://localhost:5000
Frontend: http://localhost:5173

Do not put real API keys/passwords in GitHub.
