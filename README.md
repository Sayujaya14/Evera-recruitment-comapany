# Evera Recruitment Company

Welcome to the Evera Recruitment frontend repository! This application is built using React, Vite, TypeScript, and Tailwind CSS. 

This guide will walk you through setting up and running the application on your local machine.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (Version 18 or higher is recommended)
- `npm` (comes bundled with Node.js)

---

## Getting Started

Follow these steps to get the development server running locally.

### 1. Open the UI Directory
The frontend application lives inside the `evera-ui` folder. All commands must be run from inside this directory.
```bash
cd evera-ui
```

### 2. Install Dependencies
Install all the required packages and dependencies needed for the application to work.
```bash
npm install
```

### 3. Start the Development Server
Start the local Vite development server. This will enable Hot Module Replacement (HMR) so you can see your changes instantly.
```bash
npm run dev
```

Once the server starts, it will output a local URL (usually `http://localhost:5173/`). Open this URL in your web browser to view the app!

---

## Available Commands

Here are a few other helpful commands you can run (make sure you are inside the `evera-ui` folder):

- **Build for Production**
  Compiles the application into static files for deployment.
  ```bash
  npm run build
  ```

- **Preview Production Build**
  Locally preview the built production app to ensure everything works before deploying.
  ```bash
  npm run preview
  ```

- **Lint Code**
  Runs ESLint to find and fix any code formatting or syntax issues.
  ```bash
  npm run lint
  ```

## Tech Stack
- **Framework**: React 18 + Vite
- **Language**: TypeScript
- **Styling**: Tailwind CSS (v3.4)
- **Routing**: React Router DOM
