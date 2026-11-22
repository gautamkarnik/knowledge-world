# Tacit Mosaic Music Festival

An interactive 3D visualization that presents five areas of tacit knowledge as a music festival at night: Main Stage, Concessions, Arts & Crafts, Setting Up, and Astronomy. Each area summarizes its session count, topic mix, recurring themes, and a key insight.

## Explore the page

- Select a zone from the menu or click its label in the scene to see its details.
- Drag to orbit around the festival and scroll to zoom.
- Choose **Overview** to return to the full scene.
- Choose **Look up: Winter Hexagon** to view the astronomy feature.

## Run locally

This is a static page; it does not require a build step or package installation. From the project directory, start a local web server:

```bash
python3 -m http.server 5178
```

Open [http://localhost:5178](http://localhost:5178) in a browser. Stop the server with `Ctrl+C`.

The page imports Three.js from a CDN, so an internet connection is needed to load the 3D libraries. A browser with WebGL support is also required.
