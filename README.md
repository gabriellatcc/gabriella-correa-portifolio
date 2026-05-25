# Gabriella Correa Portfolio

A modern, responsive portfolio website built with cutting-edge web technologies. This project showcases a professional portfolio with a sleek design, smooth animations, and an optimal user experience.

## About the Project

This portfolio is a single-page application (SPA) designed to present professional work, skills, and accomplishments. It features a modern UI with smooth transitions, dark mode support, and an interactive interface that highlights Gabriella Correa's professional profile.

## Technologies

### Frontend Framework & Build Tool
- **[React 19](https://react.dev/)** - Latest React version for building interactive UIs
- **[Vite](https://vite.dev/)** - Next generation frontend build tool with lightning-fast HMR
- **[TypeScript](https://www.typescriptlang.org/)** - Typed superset of JavaScript for safer code

### UI & Styling
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework for rapid UI development
- **[Radix UI](https://www.radix-ui.com/)** - Low-level UI components library with accessibility built-in
- **[shadcn/ui](https://ui.shadcn.com/)** - High-quality component collection built on Radix UI
- **[Framer Motion](https://www.framer.com/motion/)** - Animation library for smooth, production-ready animations
- **[Lucide React](https://lucide.dev/)** - Beautiful, consistent icon library
- **[React Icons](https://react-icons.github.io/react-icons/)** - Popular icon libraries bundled as React components

### Routing & State Management
- **[TanStack Router](https://tanstack.com/router/)** - Type-safe, framework-agnostic router
- **[TanStack Query](https://tanstack.com/query/)** - Powerful data synchronization and state management

### Forms & Validation
- **[React Hook Form](https://react-hook-form.com/)** - Performant, flexible form validation
- **[Zod](https://zod.dev/)** - TypeScript-first schema validation with static type inference
- **[@hookform/resolvers](https://github.com/react-hook-form/resolvers)** - Validation resolvers for React Hook Form

### Data & HTTP
- **[Axios](https://axios-http.com/)** - Promise-based HTTP client for API requests
- **[Orval](https://orval.dev/)** - OpenAPI/Swagger code generator (DevDependency)

### Utilities
- **[Next Themes](https://github.com/pacocoursey/next-themes)** - Dark mode support with zero config
- **[Tailwind Merge](https://github.com/dcastil/tailwind-merge)** - Tailwind CSS class merger
- **[clsx](https://github.com/lukeed/clsx)** - Utility for constructing class names
- **[Class Variance Authority](https://cva.style/)** - CSS-in-JS solution for managing component variants
- **[Sonner](https://sonner.emilkowal.ski/)** - Toast notification library

### Typography
- **[Geist Variable Font](https://vercel.com/font)** - Beautiful, modern font by Vercel

### Development Tools
- **[ESLint](https://eslint.org/)** - JavaScript linter
- **[TypeScript ESLint](https://typescript-eslint.io/)** - TypeScript support for ESLint
- **[@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react)** - React plugin for Vite
- **[TanStack Router Plugin](https://tanstack.com/router/)** - Vite plugin for file-based routing

## Prerequisites

- **Node.js** (v18 or higher recommended)
- **npm** or **yarn** package manager

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd gabriella-correa-portifolio
```

2. Install dependencies:
```bash
npm install
```

## Running the Project

### Development Server
Start the development server with hot module replacement (HMR):
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build for Production
Create an optimized production build:
```bash
npm run build
```

### Preview Production Build
Preview the production build locally:
```bash
npm run preview
```

### Lint Code
Run ESLint to check code quality:
```bash
npm run lint
```

### Deploy to GitHub Pages
Deploy the built project to GitHub Pages:
```bash
npm run deploy
```

For automated deployment, see [DEPLOYMENT.md](./DEPLOYMENT.md) for GitHub Actions setup.

## GitHub Pages Deployment

This project is configured for easy deployment to GitHub Pages.

### Quick Start

1. Create the `.github/workflows/deploy.yml` file (see [WORKFLOW_SETUP.md](./WORKFLOW_SETUP.md))
2. Update `vite.config.ts` base URL if needed (default: `/portifolio/`)
3. Push to `main` or `master` branch
4. GitHub Actions will automatically build and deploy

### Configuration

- **Base URL:** Automatically set to `/portifolio/` for GitHub Pages
- **Output:** Production build goes to `dist/` directory
- **Linting:** Runs before each deployment
- **Source Map:** Disabled for smaller bundle size

For detailed setup instructions, see [DEPLOYMENT.md](./DEPLOYMENT.md) and [WORKFLOW_SETUP.md](./WORKFLOW_SETUP.md).

## Project Structure

```
src/
├── components/       # Reusable React components
├── routes/          # Route definitions (TanStack Router)
├── providers/       # Context providers and global state
├── lib/            # Utility functions and helpers
├── assets/         # Images, icons, and static files
├── App.tsx         # Main application component
├── main.tsx        # Application entry point
└── global.css      # Global styles
```

## Features

- **Responsive Design** - Optimized for all device sizes
- **Dark Mode** - Seamless theme switching with next-themes
- **Smooth Animations** - Framer Motion for polished interactions
- **Type-Safe** - Full TypeScript support
- **Accessible Components** - Built with Radix UI for WCAG compliance
- **Fast Development** - Vite's instant HMR for rapid iteration
- **Modern Tooling** - ESLint and TypeScript for code quality

## Customization

### Themes
Dark mode support is built-in. Customize theme colors in your Tailwind CSS configuration.

### Components
Modify or create new components in the `src/components` directory using shadcn/ui and Radix UI components.

### Routes
Add or modify routes in the `src/routes` directory following TanStack Router conventions.

## License

This project is open source and available under the MIT License.

## Author

**Gabriella Correa** - [Portfolio Website]

---

Built with pacience using modern web technologies
