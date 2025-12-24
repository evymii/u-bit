# Architecture

Documentation about the system architecture will go here.

## Overview

This is a monorepo containing:
- Backend API (Node.js/Express)
- Frontend application (Next.js)
- Shared packages

## Backend

The backend is located in `apps/backend/` and follows a layered architecture:

- `src/config/` - Configuration files
- `src/controllers/` - Route controllers
- `src/middleware/` - Express middleware
- `src/models/` - Database models
- `src/routes/` - API routes
- `src/services/` - Business logic
- `src/types/` - TypeScript types
- `src/utils/` - Utility functions

## Frontend

The frontend is located in `apps/frontend/` and uses Next.js with the App Router:

- `src/app/` - Next.js App Router pages
- `src/components/` - React components
  - `features/` - Feature-specific components
  - `layout/` - Layout components
  - `ui/` - Reusable UI components
- `src/contexts/` - React contexts
- `src/hooks/` - Custom hooks
- `src/lib/` - Libraries and configs
- `src/types/` - TypeScript types
- `src/utils/` - Utility functions

