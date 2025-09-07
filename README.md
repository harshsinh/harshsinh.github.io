# Harsh Sinha - Personal Website

A minimal, clean academic personal website built with pure HTML, CSS, and JavaScript. No build process required.

## Overview

This website follows a simple, content-focused design philosophy inspired by sites like gwern.net and voiceaiandvoiceagents.com. It emphasizes typography, readability, and minimal complexity.

## Features

- **Clean, minimal design** focused on content and readability
- **Dark/light mode toggle** with persistent preference storage
- **Responsive design** that works on all devices
- **No build process** - pure static HTML, CSS, and JavaScript
- **Fast loading** with minimal dependencies
- **Accessible** with semantic HTML and proper ARIA labels

## File Structure

```
├── index.html          # Main website content
├── style.css           # Minimal CSS styling and theme variables
├── script.js           # Dark mode toggle and smooth animations
└── README.md           # This file
```

## Local Development

To view the website locally:

```bash
# Using Python (recommended)
python3 -m http.server 8000

# Using Node.js (if you have it installed)
npx serve .

# Using PHP (if available)
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

### GitHub Pages
1. Push the files to your GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main` or `gh-pages`)
4. Your site will be available at `https://username.github.io/repository-name`

### Other Static Hosting
This website can be deployed to any static hosting service:
- Netlify (drag and drop)
- Vercel
- Surge.sh
- Any web server

## Customization

### Theme Colors
Edit CSS variables in `style.css`:
```css
:root {
  --accent-color: #2563eb;    /* Change primary accent color */
  --bg-color: #ffffff;        /* Light mode background */
  --text-color: #333333;      /* Light mode text */
}
```

### Content
Update `index.html` sections:
- **About**: Personal bio and research interests
- **Publications**: Academic papers and publications
- **Projects**: Research projects and code repositories
- **Contact**: Email and social media links

### Dark Mode
The dark mode toggle automatically switches between themes and saves preference to localStorage. No configuration needed.

## Design Philosophy

- **Typography-first**: Clean, readable fonts and proper spacing
- **Minimal complexity**: No frameworks, build tools, or dependencies
- **Content-focused**: Design serves the content, not the other way around
- **Performance**: Fast loading with minimal HTTP requests
- **Accessibility**: Semantic HTML and proper contrast ratios

## Browser Support

Works in all modern browsers including:
- Chrome/Chromium 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## License

Feel free to use this as a template for your own academic website.