<div align="center">

# Xmas 2024

### A React + TypeScript + Vite starter project

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
[![Repo](https://img.shields.io/badge/GitHub-jackinf%2Fxmas2024-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jackinf/xmas2024)

</div>

## Overview

Xmas 2024 is a front-end project bootstrapped with the React + TypeScript + Vite template. It currently contains the default scaffold (the Vite + React starter screen with hot module replacement), providing a clean baseline to build on top of. The run commands and configuration below are taken directly from the project files.

## Tech Stack

| Area       | Tools                                                     |
| ---------- | --------------------------------------------------------- |
| Language   | TypeScript (~5.6)                                         |
| UI         | React 18.3, React DOM                                     |
| Build tool | Vite 6                                                    |
| Linting    | ESLint 9, typescript-eslint, React Hooks/Refresh plugins  |

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (a recent LTS release recommended)
- npm (bundled with Node.js)

### Installation

```bash
git clone https://github.com/jackinf/xmas2024.git
cd xmas2024
npm install
```

### Running

Scripts defined in `package.json`:

```bash
npm run dev      # start the Vite dev server with HMR
npm run build    # type-check (tsc -b) and build for production
npm run preview  # preview the production build locally
npm run lint     # run ESLint over the project
```

## Project Structure

```
xmas2024/
├── index.html          # App entry HTML
├── public/             # Static assets served as-is
├── src/
│   ├── main.tsx        # React entry point
│   ├── App.tsx         # Root component
│   └── *.css           # Styles
├── vite.config.ts      # Vite configuration
├── eslint.config.js    # ESLint configuration
└── tsconfig*.json      # TypeScript configuration
```
