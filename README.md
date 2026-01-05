# 🚀 Turborepo starter with shared shadcn/ui components (Vite, Next.js). Tailwind 4 support.

[![Build](https://github.com/evgenius1424/turborepo-vite-shadcn-ui/actions/workflows/build.yml/badge.svg)](https://github.com/evgenius1424/turborepo-vite-shadcn-ui/actions/workflows/build.yml)
[![Update Dependencies](https://github.com/evgenius1424/turborepo-vite-shadcn-ui/actions/workflows/update-dependencies.yml/badge.svg)](https://github.com/evgenius1424/turborepo-vite-shadcn-ui/actions/workflows/update-dependencies.yml)

## ✨ 2026 Structure & Standards

**This repository is fully updated to follow 2026 conventions and best practices:**

- **🏗️ Modern Architecture**: Both NextJS and Vite apps follow latest 2026 structure standards
- **📦 @workspace Namespace**: Migrated from `@repo/*` to `@workspace/*` for better organization
- **⚡ ESLint Flat Config**: Using the new flat configuration system for consistent linting
- **🔧 TypeScript ES2022**: Updated to ES2022 target with latest compiler options
- **🎨 Centralized shadcn/ui**: Improved component sharing with centralized configuration
- **🚀 Latest Dependencies**: All packages updated to 2026 versions
- **📏 Consistent Standards**: Unified structure across all apps and packages

Both applications maintain full compatibility with shared `@workspace/ui` components while following the latest industry standards.

This repository is a monorepo starter kit utilizing [Turborepo](https://turbo.build/repo) for managing multiple
applications with shared [shadcn/ui](https://github.com/shadcn-ui/ui) components. It includes two applications (`vite`
and `nextjs`) in the `apps`
directory, both of which use shared components from the `@workspace/ui` package.

The goal of this repository is to provide up-to-date starters for vite-react and Next.js, and probably something else.

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/en/download/) (version 20 or higher)
- [pnpm](https://pnpm.io/installation) (version 10 or higher)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/evgenius1424/turborepo-vite-shadcn-ui.git
   cd turborepo-vite-shadcn-ui
   ```

2. Install dependencies using `pnpm`:

   ```bash
   pnpm install
   ```

3. Build

   ```bash
   pnpm build
   ```

4. Develop

```bash
   pnpm dev
```

5. Add new [component](https://ui.shadcn.com/docs/components/tabs) (replace card with button, tabs, you name it)

```bash
pnpm ui card
```

Enjoy working with your new Turborepo starter kit and feel free to raise a PR! 🎉
