# Emonada - Vue 3 Static Website

A simple, elegant static website built with Vue 3 and Tailwind CSS, featuring a main page and a subpage with smooth routing.

![Home Page](https://github.com/user-attachments/assets/5f51c0bd-07b9-4617-a979-b25bd74be7b4)

## Features

- ⚡ **Vue 3** - Progressive JavaScript framework
- 🎨 **Tailwind CSS** - Utility-first CSS framework
- 🚀 **Vite** - Next-generation frontend tooling
- 🔄 **Vue Router** - Official routing for Vue.js
- 📱 **Responsive Design** - Mobile-first approach
- 🎯 **Simple & Clean** - Easy to understand and extend

## Project Structure

```
emonada-www/
├── public/                 # Static assets
│   └── favicon.ico        # Website favicon
├── src/                   # Source files
│   ├── assets/           # Asset files (CSS, images)
│   │   ├── base.css      # Base CSS styles (from Vue template)
│   │   ├── logo.svg      # Vue logo
│   │   └── main.css      # Main CSS with Tailwind directives
│   ├── components/       # Reusable Vue components (from template)
│   │   ├── HelloWorld.vue
│   │   ├── TheWelcome.vue
│   │   ├── WelcomeItem.vue
│   │   └── icons/        # Icon components
│   ├── router/           # Router configuration
│   │   └── index.js      # Vue Router setup with routes
│   ├── views/            # Page components
│   │   ├── Home.vue      # Main landing page
│   │   └── About.vue     # About page (subpage)
│   ├── App.vue           # Root Vue component
│   └── main.js           # Application entry point
├── .gitignore            # Git ignore rules
├── .vscode/              # VS Code settings
│   ├── extensions.json   # Recommended extensions
│   └── settings.json     # Editor settings
├── index.html            # HTML entry point
├── jsconfig.json         # JavaScript configuration
├── package.json          # NPM dependencies and scripts
├── package-lock.json     # NPM lock file
├── postcss.config.js     # PostCSS configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── vite.config.js        # Vite configuration
└── README.md             # This file
```

## Key Files Explained

### Configuration Files

- **`vite.config.js`** - Vite build tool configuration with Vue plugin
- **`tailwind.config.js`** - Tailwind CSS configuration, defines content paths for purging unused styles
- **`postcss.config.js`** - PostCSS configuration for processing Tailwind CSS
- **`jsconfig.json`** - JavaScript project configuration for better IDE support
- **`package.json`** - Project metadata, dependencies, and npm scripts

### Source Files

- **`src/main.js`** - Application entry point that creates the Vue app and registers the router
- **`src/App.vue`** - Root component that contains the router view
- **`src/router/index.js`** - Router configuration defining all routes (/, /about)
- **`src/views/Home.vue`** - Main landing page with hero section and features
- **`src/views/About.vue`** - About page with project information
- **`src/assets/main.css`** - Main stylesheet with Tailwind directives (@tailwind base, components, utilities)

### Build Output

When you run `npm run build`, Vite creates a `dist/` directory containing:
- Optimized HTML, CSS, and JavaScript files
- Hashed filenames for cache busting
- Minified and compressed assets

## Getting Started

### Prerequisites

- Node.js (v20.19.0 or higher)
- npm (v10.8.2 or higher)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vojkoh/emonada-www.git
cd emonada-www
```

2. Install dependencies:
```bash
npm install
```

### Development

Start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:5173`

### Production Build

Build for production:
```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

## Routes

- **`/`** - Home page (main page)
- **`/about`** - About page (subpage)

## Dependencies

### Runtime Dependencies
- **vue** (^3.5.26) - The Vue.js framework
- **vue-router** (^4.x) - Official router for Vue.js

### Development Dependencies
- **@vitejs/plugin-vue** (^6.0.3) - Vite plugin for Vue 3
- **@tailwindcss/postcss** - PostCSS plugin for Tailwind CSS v4
- **autoprefixer** - PostCSS plugin to add vendor prefixes
- **tailwindcss** - Utility-first CSS framework
- **vite** (rolldown-vite) - Next-generation frontend build tool
- **vite-plugin-vue-devtools** (^8.0.5) - Vue DevTools integration

## Customization

### Adding New Pages

1. Create a new component in `src/views/`:
```vue
<!-- src/views/NewPage.vue -->
<template>
  <div>Your content here</div>
</template>
```

2. Add the route in `src/router/index.js`:
```javascript
import NewPage from '../views/NewPage.vue'

const routes = [
  // ... existing routes
  {
    path: '/new-page',
    name: 'newpage',
    component: NewPage
  }
]
```

3. Add navigation link in your components:
```vue
<router-link to="/new-page">New Page</router-link>
```

### Styling

The project uses Tailwind CSS for styling. You can:
- Use Tailwind utility classes directly in your components
- Extend the theme in `tailwind.config.js`
- Add custom CSS in `src/assets/main.css`

## Browser Support

This application supports all modern browsers that support ES2015+ features.

## License

This is a demonstration project. Feel free to use it as a starting point for your own projects!

## Screenshots

### Home Page
![Home Page](https://github.com/user-attachments/assets/5f51c0bd-07b9-4617-a979-b25bd74be7b4)

### About Page
![About Page](https://github.com/user-attachments/assets/ef8d5d20-c2e2-4c00-be1b-f6728a93560f)
