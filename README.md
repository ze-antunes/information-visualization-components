# Information Visualization — Individual Components

A collection of small information-visualization and interaction experiments. Each example is organized in its own directory.

## Examples

| Directory | Focus |
| --- | --- |
| `Comments Carousel/` | Carousel-style interface for comments |
| `Map Zoom/` | Map zoom interaction |
| `Stream Chart/` | Stream chart visualization |
| `Word Cloud/` | Word cloud visualization |

The `Word Cloud/` example includes `index.html`, `index.js` and a UFO sightings CSV dataset.

## Exploring the components

Open the relevant example directory and inspect its `index.html` or other entry files. If an example loads local data, serve it over HTTP rather than opening files directly:

```bash
python3 -m http.server 8000
```

Visit `http://localhost:8000` and navigate to the relevant component directory.

## Context

Individual experiments related to information visualization and interactive web interfaces. The examples are independent rather than a single packaged application.
