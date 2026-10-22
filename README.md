# MetalForge CD Case

Static export for a MetalForge 3D CD jewel case and album collection page.

The site showcases realistic 3D jewel cases with album art, disc visuals, layout presets, and supporting help content.

## Project structure

```text
.
├── index.html          # Main landing page
├── help                # Help page export
├── cdcase/             # CD case route and assets
├── _next/              # Exported Next.js static assets
├── api/                # Exported API route output
└── opengraph-image     # Social preview asset
```

## Run locally

Serve the folder from the project root so absolute asset paths like `/_next/...` resolve correctly:

```bash
python3 -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Deployment

Deploy the entire folder as a static site. Keep `_next/`, `cdcase/`, and the root HTML files together so all routes and assets continue to work.
