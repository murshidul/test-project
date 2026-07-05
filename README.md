# test-project

A Node.js web application built with TypeScript and Next.js.

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **Package Manager:** npm
- **Linting:** ESLint

## Getting Started

```bash
npm install
npm run dev
```

## Project Structure

```
test-project/
├── app/               # Next.js App Router pages and layouts
├── components/        # Reusable React components
├── lib/               # Utility functions and shared logic
├── public/            # Static assets
├── cursor.md          # AI project guide
├── README.md          # This file
└── package.json       # Dependencies and scripts
```

## Commands

| Command | Description |
|---------|-------------|
| `npm install` | Install dependencies |
| `npm run dev` | Start development server |
| `npm run build` | Create production build |
| `npm run start` | Start production server |
| `npm run lint` | Run ESLint |

## Notes for AI Assistants

When working in this project:

1. Read [`cursor.md`](cursor.md) first for project-wide context.
2. Follow existing Next.js App Router and TypeScript conventions.
3. Keep diffs minimal and do not commit unless explicitly asked.
4. Do not store secrets (API keys, tokens, credentials) in the repo.
