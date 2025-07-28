# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a React practices repository built with Vite as the build tool. It's a minimal React setup intended for learning and experimentation with React concepts.

## Architecture

- **Frontend Framework**: React 19 with JSX
- **Build Tool**: Vite with Hot Module Replacement (HMR)
- **Entry Point**: `src/main.jsx` renders the App component into the DOM
- **Main Component**: `src/App.jsx` contains the root application component
- **Linting**: ESLint with React-specific rules and plugins

## Development Commands

```bash
# Start development server with HMR
npm run dev

# Build for production
npm run build

# Run ESLint to check code quality
npm run lint

# Preview production build locally
npm run preview
```

## Code Standards

The project uses ESLint with:
- Standard JavaScript recommended rules
- React recommended rules and JSX runtime rules
- React Hooks rules for proper hook usage
- React Refresh plugin for fast refresh during development

## Key Configuration Files

- `vite.config.js`: Vite configuration with React plugin
- `eslint.config.js`: ESLint configuration with React-specific rules
- `package.json`: Project dependencies and scripts

## Development Notes

- The project uses ES modules (`"type": "module"` in package.json)
- React components should be written as functional components
- The build outputs to a `dist` directory (ignored by ESLint)
- Uses React 19's latest features and patterns