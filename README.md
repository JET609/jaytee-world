# Portfolio Site Preview

This project is a static portfolio website served from `index.html`.

## Previewing Locally

You can preview the site locally in any of the following ways:

### 1. Open the file directly
1. Clone the repository.
2. Open `index.html` in your browser (double-click or drag it into a browser window).

### 2. Use a simple HTTP server
Serving the site through a local web server more closely matches production behavior and avoids browser restrictions on local files.

#### Python
```bash
python3 -m http.server 8000
```
Then visit [http://localhost:8000](http://localhost:8000) in your browser.

#### Node.js
If you have Node.js installed, you can use `npx serve`:
```bash
npx serve .
```
This will launch a server (typically at http://localhost:3000).

## Deployment
Because this is a static site, it can be deployed using any static hosting service (GitHub Pages, Netlify, Vercel, etc.).
