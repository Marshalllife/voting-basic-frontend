# Voting Basic Frontend

A simple voting dApp frontend for Cedra Network. Create proposals, vote, and see results in real-time.

## Quick Start

```bash
# Install dependencies
npm install

# Copy env file and configure
cp .env.local.example .env.local

# Run dev server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Environment

```env
NEXT_PUBLIC_PLATFORM_ADDRESS=<your-contract-address>
```

## Tech Stack

- Next.js 16
- React 19
- Cedra TS SDK
- TailwindCSS 4
- Framer Motion

## Features

- Wallet connection
- Create proposals
- Vote on proposals
- View all voters
- Real-time updates

## Live Demo

[voting-basic-frontend.vercel.app](https://voting-basic-frontend.vercel.app/)

## License

MIT
