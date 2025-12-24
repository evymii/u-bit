# Deployment

Documentation about deployment procedures will go here.

## Prerequisites

- Node.js (version X.X.X)
- npm or yarn

## Backend Deployment

1. Install dependencies:
```bash
cd apps/backend
npm install
```

2. Set environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

3. Build and start:
```bash
npm run build
npm start
```

## Frontend Deployment

1. Install dependencies:
```bash
cd apps/frontend
npm install
```

2. Set environment variables:
```bash
cp .env.local.example .env.local
# Edit .env.local with your configuration
```

3. Build and start:
```bash
npm run build
npm start
```

## Vercel Deployment

The frontend is configured for Vercel deployment. See `apps/frontend/vercel.json` for configuration.

