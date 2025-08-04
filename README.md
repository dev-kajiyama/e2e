# e2e

This repository uses an npm workspace monorepo setup. The `apps/web` directory contains a Next.js application.
The `apps/laravel` directory now includes a minimal Laravel skeleton that can be expanded with `composer install` when network access is available.

## Development

Install dependencies:

```
npm install
```

Run the development server:

```
npm run dev -w web
```
