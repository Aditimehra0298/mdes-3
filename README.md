# MDES - Machinery Design Excellence

This is a static website for MDES (Machinery Design Excellence) featuring collaborator cards and interactive elements.

## Netlify Deployment

This site is configured for Netlify deployment with the following settings:

- **Publish directory**: `.` (root directory)
- **Build command**: `echo 'Static site - no build required'`
- **Node version**: 18

## Files Structure

- `index.html` - Main website file
- `styles.css` - All CSS styles
- `script.js` - JavaScript functionality
- `_redirects` - Netlify redirects configuration
- `netlify.toml` - Netlify build configuration
- `_headers` - Security headers

## Local Development

To run locally:
```bash
python3 -m http.server 8000
# or
npx http-server
```

Then visit `http://localhost:8000`

## Features

- Responsive design
- Interactive collaborator cards
- 3D flip animations
- QR code modal functionality
- Orange theme matching brand colors
