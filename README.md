# MB Portal Svelte Front

A modern web application built with SvelteKit, TypeScript, and TailwindCSS.

## Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/sacalito/mb-portal-svelte-front.git
cd mb-portal-svelte-front
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Create environment file:

For Mac/Linux:

```bash
cp .env.example .env
```

For Windows:

```bash
copy .env.example .env
```

4. Configure your environment variables in `.env` file:

```env
# API Configuration
VITE_API_BASE_URL=https://api-test.mbsmart.dev/apiv2

# Security
COOKIE_SECURE=true
COOKIE_SAME_SITE=strict
```

5. Start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run check` - Type-check the code
- `npm run format` - Format code with Prettier
- `npm run lint` - Lint code with ESLint

## Project Structure

- `/src/routes` - Application routes and pages
- `/src/lib` - Shared components and utilities
- `/src/app.html` - HTML template
- `/static` - Static assets

## Technologies Used

- SvelteKit
- TypeScript
- TailwindCSS
- Axios for API calls
- Lucide Icons
- Inter Font

## Deployment

The project is configured for deployment on Vercel with the following configuration:

```json
{
	"rewrites": [{ "source": "/(.*)", "destination": "/index.html" }]
}
```

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Submit a pull request
# MB-front
