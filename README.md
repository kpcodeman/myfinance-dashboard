# Finance Dashboard

A modern full-stack finance dashboard for importing, classifying, and analyzing transactions, with automated notifications for regular spending.

## Features

- Import transactions (CSV)
- Automated classification (rules-based, ML-ready)
- Recurring spending detection
- Email/SMS notifications for upcoming bills
- Analytics and charts
- Modern UI (React + Tailwind)
- Full API backend (Node.js/Express)

---

### Getting Started

#### Frontend

```bash
cd frontend
npm install
npm run dev
```

#### Backend

```bash
cd backend
npm install
npm run dev
```

- Configure backend notification credentials in `.env` (see backend/README.md).
- Frontend expects backend at `http://localhost:4000` by default.