# Cursor Project Guide

This file provides context and instructions for Cursor AI when working in this project.

## Project Overview

- **Name:** test-project
- **Description:** A Node.js web application built with TypeScript and Next.js.
- **Status:** Initial setup

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **Package Manager:** npm
- **Styling:** (to be decided — e.g. Tailwind CSS)
- **Linting:** ESLint

## Project Structure

```
test-project/
├── app/               # Next.js App Router pages and layouts
├── components/        # Reusable React components
├── lib/               # Utility functions and shared logic
├── public/            # Static assets
├── cursor.md          # AI project guide
├── next.config.ts     # Next.js configuration
├── tsconfig.json      # TypeScript configuration
└── package.json       # Project dependencies and scripts
```

## Coding Conventions

- Use TypeScript strictly — avoid `any` unless absolutely necessary.
- Prefer React Server Components; use `"use client"` only when client-side interactivity is needed.
- Follow existing Next.js App Router patterns in the codebase.
- Keep changes focused and minimal.
- Prefer clear names over abbreviations.
- Add comments only when the logic is not obvious.

## Commands

```bash
npm install          # Install dependencies
npm run dev          # Start development server (http://localhost:3000)
npm run build        # Create production build
npm run start        # Start production server
npm run lint         # Run ESLint
```

## Notes for AI

- Read surrounding code before making changes.
- Do not commit unless explicitly asked.
- Do not add unrelated files or over-engineer solutions.
- Ask before making large architectural changes.
