# Rostom's people — 3D friend network

Interactive 3D force-directed map of friends, clusters, relationship types, and closeness.

This repo is **private**, so public GitHub Pages / htmlpreview links do not work.

## View the graph

**Repo (collaborators only):**  
https://github.com/rostom-baccar/network-graph

### Option A — open the file

1. Clone or download the repo
2. Open [`index.html`](./index.html) in Chrome / Edge / Firefox  
   (needs internet once — the 3D engine loads from a CDN)

### Option B — local server (recommended)

```bash
git clone https://github.com/rostom-baccar/network-graph.git
cd network-graph
python3 -m http.server 8765
```

Then open: **http://127.0.0.1:8765/**

### Want a public live demo link again?

Either:
- make the repo **public** and re-enable GitHub Pages, or
- use **GitHub Pro** (private Pages for private repos)

## Controls

- **Left-drag** — orbit
- **Scroll** — zoom
- **Right-drag** — pan
- **Click a ball** — open that person’s note and ties
- **Auto-rotate** — toggle in the toolbar
- Filters: search, cluster, strength, hide weak ties, only-you

## What’s in the graph

- ~60 people as colored spheres (size ≈ closeness to you)
- Clusters (poetry, Cité, INSA, Science Po, Tunisia, …)
- Relationship edges (friend, romantic, family, work, tension, …)
- Per-person notes and tie notes in the side panel
