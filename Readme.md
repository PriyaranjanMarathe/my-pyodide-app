# my-pyodide-app

A zero-backend demo of client-side Python running in your browser via Pyodide & WebAssembly, hosted for free on GitHub Pages.

## Demo

👉 [https://priyaranjanmarathe.github.io/my-pyodide-app/](https://priyaranjanmarathe.github.io/my-pyodide-app/)

## Features

- Loads Pyodide v0.23.4 from CDN
- Runs Python code entirely in-browser
- No servers, no billing—100% static HTML/JS

## Getting Started

### 1. Clone

```bash
git clone git@github.com:priyaranjanmarathe/my-pyodide-app.git
cd my-pyodide-app
```

### 2. Test Locally

Start a local server with Python:

```bash
python -m http.server 8080
```

Visit [http://localhost:8080](http://localhost:8080) in your browser.

### 3. Use

Click "**Run Python**" to print `sys.version` on the page.

## Deploy to GitHub Pages

1. Push your changes to the `main` branch.
2. In your repo’s **Settings → Pages**, set the source to `main` (root).
3. Wait a minute, then visit your live URL.

## Persistence & Scaling

- **Small data**: Use `localStorage` or `IndexedDB` via the JS↔Python bridge.
- **Larger models**: Stream WASM shards or fetch them from a CDN.

## License

MIT © 2025 Priyaranjan Marathe

## Acknowledgements

Inspired by Simon Willison’s blog post “[If you want to create completely free software for other people to use…](https://simonwillison.net/2022/May/14/free-software/)”
