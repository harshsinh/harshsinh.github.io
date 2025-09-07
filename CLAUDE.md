# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands

### Local Development
```bash
python3 -m http.server 8000    # Start local development server
# OR
npx serve .                    # Alternative using Node.js
```

Visit `http://localhost:8000` to view the site.

## Architecture Overview

This is a minimal personal website built with pure HTML, CSS, and JavaScript. No build process or framework dependencies required.

### File Structure

```
├── index.html          # About page (homepage)
├── experience.html     # Experience & publications
├── projects.html       # Project portfolio
├── style.css          # All styling and themes
├── script.js          # Dark mode toggle and interactions
├── assets/docs/       # PDF files and documents
└── README.md          # Project documentation
```

### Key Features

**Simple Architecture:**
- Pure HTML/CSS/JS - no build process
- CSS variables for easy theming
- Dark/light mode with localStorage persistence
- Mobile-responsive design
- Minimal dependencies

**Content Organization:**
- **About** (index.html): Bio, current role, contact info
- **Experience** (experience.html): Work history organized by company/institution, includes publications
- **Projects** (projects.html): Academic and professional projects with links

**Styling:**
- Clean typography-focused design
- CSS Grid and Flexbox for layouts
- Theme toggle using ◑/◐ symbols
- Hover effects and smooth transitions

## Deployment

### GitHub Pages
1. Push to GitHub repository
2. Settings → Pages → Select source branch
3. Site will be available at `https://username.github.io/repository-name`

### Static Hosting
Deploy to any static host: Netlify, Vercel, Surge.sh, or any web server.

## Customization

### Theme Colors
Edit CSS variables in `style.css`:
```css
:root {
  --accent-color: #2563eb;    /* Primary links and accents */
  --bg-color: #ffffff;        /* Background */
  --text-color: #333333;      /* Main text */
}
```

### Content Updates
- Edit HTML files directly
- Add PDF links to `/assets/docs/` directory
- Update contact links in index.html

### Dark Mode
Automatic toggle with persistent preference storage. Uses ◑ (light) and ◐ (dark) symbols.