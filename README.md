# Task Manager

A React 18 app skeleton created with Create React App. It has the testing libraries installed but no task features yet.

**Status:** Stub. `App.js` renders only the text "App", and the source folder has three files with no features.

## The problem

The package is named `task-manager`, but the code does not yet show what the app is for. There are no task, project or user features in the source.

## What it does

- Renders the text "App" into the page root from `src/index.js`, inside `React.StrictMode`.
- Provides the Create React App scripts for development, production builds and tests.

## How it's built

- React 18 with `react-scripts` 5.0.1 (Create React App).
- Testing Library packages and `web-vitals` are installed as dependencies.
- No routing, state management or styling beyond the defaults.

## Running it locally

```bash
pnpm install   # or: npm install
npm start      # runs: react-scripts start
npm test       # runs: react-scripts test
npm run build  # runs: react-scripts build
```

Open `http://localhost:3000` after `npm start`.

## What's left

- `App.js` is a placeholder, so there is no UI to speak of.
- No tests have been written, although the testing libraries are installed.
- The Create React App boilerplate README has been replaced by this file.
