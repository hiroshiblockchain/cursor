## Cursor Cloud specific instructions

This is a minimal static HTML repository with no build tools, package managers, or frameworks.

### Running the application

Serve the site locally with Python's built-in HTTP server:

```
python3 -m http.server 8000 --directory /workspace
```

The site is then available at `http://localhost:8000`.

### Lint / Test / Build

There are no linters, test frameworks, or build steps configured. The repository contains only a static `index.html`.
