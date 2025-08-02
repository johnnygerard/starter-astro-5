# Astro 5 Starter

A minimal starter template for building modern web applications with [Astro 5](https://astro.build/). This template provides a clean foundation to get started with Astro's latest features and best practices.

## About Astro

Astro is a modern web framework that delivers lightning-fast performance by shipping zero JavaScript by default. It allows you to build content-focused websites using your favorite UI components and frameworks.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (version 18.17.1 or higher)
- **npm** (comes with Node.js)

## Getting Started

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd starter-astro-5
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:4321`

## Available Scripts

This project includes several npm scripts to help with development and deployment:

- `npm run dev` - Start the development server with hot reload
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run format` - Format code using Prettier
- `npm run format:check` - Check if code is properly formatted
- `npm run astro` - Run Astro CLI commands

## Project Structure

```
├── public/                 # Static assets (favicons, images, etc.)
├── src/
│   ├── components/        # Reusable Astro components
│   ├── pages/            # File-based routing (each file becomes a route)
│   ├── styles/           # CSS and styling files
│   └── Layout.astro      # Base layout component
├── astro.config.ts       # Astro configuration
├── package.json          # Project dependencies and scripts
└── tsconfig.json         # TypeScript configuration
```

## Development Workflow

1. **Pages**: Add new pages by creating `.astro` files in the `src/pages/` directory
2. **Components**: Create reusable components in `src/components/`
3. **Styling**: Add styles in the `src/styles/` directory
4. **Static Assets**: Place images, fonts, and other static files in the `public/` directory

## Code Formatting

This project uses [Prettier](https://prettier.io/) for consistent code formatting. The configuration includes support for Astro files via the `prettier-plugin-astro` plugin.

## Learn More

- [Astro Documentation](https://docs.astro.build/) - Learn about Astro features and API
- [Astro Discord](https://astro.build/chat) - Join the community
- [Astro GitHub](https://github.com/withastro/astro) - View the source code

## License

This project is licensed under the terms specified in the [LICENSE.txt](LICENSE.txt) file.
