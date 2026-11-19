# Playwright Project

TypeScript Playwright Test project for end-to-end browser testing.

## Prerequisites

- Node.js 20 or later
- npm

## Setup

```powershell
npm ci
npx playwright install chromium
```

## Run tests

```powershell
npm test
npm run test:ui
npm run test:headed
npm run test:report
```

Test files are located in `e2e/`. Playwright configuration is in `playwright.config.ts`.
