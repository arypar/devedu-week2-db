# Database Intro Project

This is an introductory Next.js project designed to demonstrate database reads and writes operations. Built with [Next.js](https://nextjs.org) and modern web technologies, this project serves as a learning tool for understanding how to interact with databases in a web application.

## Project Overview

This project showcases:
- Database connection and configuration
- CRUD operations (Create, Read, Update, Delete)
- Data persistence and retrieval
- Modern React patterns with Next.js App Router
- UI components built with Tailwind CSS

## Getting Started

### Prerequisites

- Node.js 18+ installed
- Database setup (see Environment Variables section)

### Installation

1. Clone the repository
2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

### Environment Variables

Create a `.env.local` file in the root directory with the necessary environment variables for database connection and Next.js configuration.

**Required variables:**
- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`

### Running the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `app/` - Next.js App Router pages and layouts
- `components/` - Reusable UI components
- `lib/` - Utility functions and database configurations
- `public/` - Static assets

## Features

- Database integration examples
- User interface for data manipulation
- Responsive design with Tailwind CSS
- Modern React patterns and hooks

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Database Integration Guide](https://nextjs.org/docs/app/building-your-application/database)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
