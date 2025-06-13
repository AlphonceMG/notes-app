# Keeper App

A simple and elegant note-taking application built with React and Vite. This app allows users to create, view, and manage their notes in a clean and intuitive interface.

## Features

- Create notes with titles and content
- View all your notes in a card-based layout
- Delete notes you no longer need
- Responsive design with a modern UI
- Real-time updates using React's state management

## Tech Stack

- React 17
- Vite for fast development and building
- Modern CSS for styling
- ESLint for code quality

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Building for Production

1. Create a production build:
   ```bash
   npm run build
   ```
   This will create a `dist` directory with optimized files.

2. Preview the production build:
   ```bash
   npm run preview
   ```

## Deployment

### Option 1: Deploy to Netlify

1. Install Netlify CLI:
   ```bash
   npm install -g netlify-cli
   ```

2. Deploy to Netlify:
   ```bash
   netlify deploy
   ```

### Option 2: Deploy to Vercel

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy to Vercel:
   ```bash
   vercel
   ```

### Option 3: Deploy to GitHub Pages

1. Add `homepage` field to `package.json`:
   ```json
   {
     "homepage": "https://yourusername.github.io/notes-app"
   }
   ```

2. Install gh-pages:
   ```bash
   npm install --save-dev gh-pages
   ```

3. Add deploy scripts to `package.json`:
   ```json
   {
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d dist"
     }
   }
   ```

4. Deploy:
   ```bash
   npm run deploy
   ```

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the app for production
- `npm run preview` - Preview the production build
- `npm run lint` - Run ESLint to check code quality

## Project Structure

- `src/App.jsx` - Main application component
- `src/CreateArea.jsx` - Component for creating new notes
- `src/Note.jsx` - Component for displaying individual notes
- `src/Header.jsx` - Application header
- `src/Footer.jsx` - Application footer
- `src/index.css` - Global styles
