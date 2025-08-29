# Auth File Frontend

A modern, responsive frontend for the Auth & File Upload System built with Next.js 15, TypeScript, and Tailwind CSS.

## Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: React Query + Zustand
- **Form Handling**: React Hook Form + Zod
- **HTTP Client**: Axios

## Getting Started

### Prerequisites

- Node.js 18.17 or later
- npm or yarn or pnpm

### Installation

1. Install dependencies:
```bash
npm install
```

2. Create `.env.local` file:
```env
NEXT_PUBLIC_API_URL=http://localhost:8001
```

3. Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser.

## Available Scripts

```bash
npm run dev       # Start development server
npm run build     # Build for production
npm run start     # Start production server
npm run lint      # Run ESLint
npm run type-check # Run TypeScript compiler check
```

## Project Structure

```
src/
├── app/                    # App Router pages
├── components/            # Reusable components
├── lib/                  # Utilities and configs
├── hooks/               # Custom React hooks
├── store/              # Zustand stores
└── types/             # TypeScript types
```

## Features

- 🔐 JWT Authentication
- 📁 File Upload & Management
- 🎨 Modern UI with Tailwind
- 📱 Fully Responsive
- 🌙 Dark Mode Support
- ⚡ Optimized Performance

## Deployment

This app can be deployed on Vercel with zero configuration:

[\![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/nabiilNajm26/auth-file-frontend)

## License

MIT
