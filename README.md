# SaaS Landing Page

A modern landing page for SaaS, built with React, Vite, and Tailwind CSS v4.

## Features
- Responsive design for all devices
- Smooth scroll navigation
- Modular and reusable components
- Fast development and build with Vite
- Utility-first styling with Tailwind CSS v4

## Technologies Used
- **React 19**: Main library for building the UI
- **Vite**: Fast bundler for development and production
- **Tailwind CSS v4**: Utility-first CSS framework
- **ESLint**: Code quality and linting
- **Prettier**: Code formatting
- **clsx**: Conditional className utility
- **react-scroll**: Smooth scrolling between sections

## Folder Structure
```
public/
  images/         # Images used in the UI
  logos/          # Partner logos
  socials/        # Social media icons
  testimonials/   # Testimonial photos
src/
  assets/         # SVGs and internal images
  components/     # Reusable components (Button, Marker)
  constants/      # Global constants
  sections/       # Landing page sections (Header, Hero, Features)
  App.jsx         # Main app component
  index.css       # Global styles
  main.jsx        # Entry point
```

## Available Scripts
- `npm run dev`: Start the development server
- `npm run build`: Build for production
- `npm run preview`: Preview the production build locally
- `npm run lint`: Run ESLint

## Installation
```bash
npm install
```

## Usage
```bash
npm run dev
```

## Build
```bash
npm run build
```

## Additional Information
- The project uses only standard Tailwind v4 utilities, with no custom tailwind.config.js.
- Images and assets are organized in the `public/images` folder.
- For details on Tailwind classes, see the [official documentation](https://tailwindcss.com/docs/installation).

## License
This project is for study and demonstration purposes only.
