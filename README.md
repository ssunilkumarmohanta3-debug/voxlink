# VoxLink

  A production-grade social audio/video calling mobile app.

  ## Stack
  - **Mobile**: React Native (Expo 54) + expo-router
  - **Backend**: Cloudflare Workers + Hono.js + D1 (SQLite) + R2 + Durable Objects
  - **Admin Panel**: React + Vite + Tailwind CSS

  ## Admin Panel Features
  - Dashboard with charts (revenue, calls, users)
  - User management
  - Host management  
  - Call sessions history
  - Ratings & reviews
  - Withdrawal requests
  - Coin plans
  - Coin transactions
  - Push notifications
  - Talk topics
  - FAQs
  - App settings

  ## Admin Credentials
  - Email: `admin@voxlink.app`
  - Password: `admin123`

  ## Getting Started
  ```bash
  pnpm install
  pnpm --filter @workspace/api-server run dev   # API on :8080
  pnpm --filter @workspace/admin-panel run dev  # Admin on :20130
  pnpm --filter @workspace/voxlink run dev      # Mobile on :20426
  ```
  