# Redirect page

This project is a static HTML page. It redirects visitors to `https://www.google.com`, preserving the URL fragment (everything after `#`).

## Preview

Run the **Start application** workflow. It copies `index.html` into the generated `public/` folder and serves that folder on port 5000 using Python's HTTP server. No packages or secrets are required.

## Publishing

Static publishing is configured with `public/` as the public directory. The build command copies only `index.html` there, keeping project configuration and documentation out of the published site.

Use Replit's Publish action to publish. The redirect runs immediately, so the preview will navigate away from this site; Google may refuse to display inside the preview iframe.
