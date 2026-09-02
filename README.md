# Rostom's people — 3D friend network

Interactive 3D force-directed map of friends, clusters, relationship types, and closeness.

## View the graph

**Live demo (GitHub Pages):**  
https://rostom-baccar.github.io/friend-network/

**Direct graph page:**  
https://rostom-baccar.github.io/friend-network/index.html

**Alternate preview (if Pages is still warming up):**  
https://htmlpreview.github.io/?https://github.com/rostom-baccar/friend-network/blob/main/index.html

**Raw file on GitHub:**  
https://github.com/rostom-baccar/friend-network/blob/main/index.html

> Needs an internet connection — the 3D engine loads from a CDN (`3d-force-graph`, Three.js, sprite text).

## Controls

- **Left-drag** — orbit
- **Scroll** — zoom
- **Right-drag** — pan
- **Click a ball** — open that person’s note and ties
- **Auto-rotate** — toggle in the toolbar
- Filters: search, cluster, strength, hide weak ties, only-you

## Local

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8765
```

Then visit http://127.0.0.1:8765/

## What’s in the graph

- ~60 people as colored spheres (size ≈ closeness to you)
- Clusters (poetry, Cité, INSA, Science Po, Tunisia, …)
- Relationship edges (friend, romantic, family, work, tension, …)
- Per-person notes and tie notes in the side panel
