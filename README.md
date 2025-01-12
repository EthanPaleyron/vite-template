# Use my template

## Features

- ⚡️ **Vite** for blazing fast development.
- 📦 **PNPM** for efficient dependency management.
- 🎨 **SASS** for powerful and flexible CSS preprocessing.

## Prerequisites

Before getting started, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/en)
- [PNPM](https://pnpm.io/installation)

## Install the dependencies

```bash
pnpm install
```

## Development Server

To start the development server and preview your project:

```bash
pnpm run dev
```

This will start the server on http://localhost:5173 by default.

## Available Scripts

Here are some useful scripts you can run:

- Start development server: `pnpm run dev`
- Build for production: `pnpm run build`
- Preview production build: `pnpm run preview`

## Project Structure

```bash
public
├─ fonts
├─ images
├─ js
└─ sass
index.html
```

## SASS Structure

Below is the SASS folder structure with a brief explanation of each file's purpose:

```bash
sass
├─ abstracts
│  ├─ _colors.scss
│  ├─ _fonts.scss
│  ├─ _index.scss
│  ├─ _texts.scss
│  └─ _variables.scss
├─ base
│  ├─ _base.scss
│  ├─ _index.scss
│  ├─ _reset.scss
│  └─ _titles.scss
├─ components
│  ├─ _index.scss
│  ├─ _link.scss
│  └─ ...
├─ utilities
│  ├─ mixins
│  │  ├─ _all-navigator.scss
│  │  ├─ _aspect-ratio.scss
│  │  ├─ _computed-margin.scss
│  │  ├─ _ez-fonts.scss
│  │  ├─ _index.scss
│  │  └─ _responsive.scss
│  ├─ _index.scss
│  └─ ...
├─ homepage.scss
├─ main.scss
└─ ...
```

Explanation of Sections:

- `abstracts`: Contains all global variables and configurations to ensure consistent styling.
- `base`: Provides base styles for the project, including resets and default styles.
- `components`: Manages styles for reusable elements (buttons, cards, etc.).
- `utilities`: Includes mixins and functions to simplify the creation of modular styles.
- `homepage.scss`: A dedicated file for styling the homepage.
- `main.scss`: The main entry file that imports all other SASS files.
