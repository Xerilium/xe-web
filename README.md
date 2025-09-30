# xe-web

A simple Vite/TypeScript web project that immediately redirects to [https://about.me/flanakin](https://about.me/flanakin).

## Features

- Built with Vite and TypeScript
- Immediate temporary redirect (HTTP 302 equivalent via JavaScript)
- Automatically deployed to GitHub Pages on push to main branch

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

This project is automatically deployed to GitHub Pages when changes are pushed to the main branch via GitHub Actions.