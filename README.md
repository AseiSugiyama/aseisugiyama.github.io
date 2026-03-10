# Asei Sugiyama Profile

This is a personal profile website for Asei Sugiyama.

## Architecture

This project is a static website built with:

- **Svelte 5**: Used for component-based UI development.
- **Vite**: Used as the fast build tool and development server.
- **HTML/CSS**: Basic styling and structure.

The application uses Svelte 5's new `mount` API to render the `App.svelte` component into the `index.html` file.

## Development

To run the project locally:

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the development server:

   ```bash
   npm run dev
   ```

3. Format code:
   ```bash
   npm run format
   ```

## Deployment

The project is configured to be built as a static site.

1. Build the project:

   ```bash
   npm run build
   ```

2. The output will be in the `dist/` directory.

3. The `dist/` directory can be deployed to any static site hosting service, such as:
   - GitHub Pages
   - Vercel
   - Netlify
   - Cloudflare Pages

   For most of these services, you can connect your Git repository and set the build command to `npm run build` and the output directory to `dist/`.
