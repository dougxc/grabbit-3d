This is a simple app to display the generous gift Thomas and I received from the Graal team as part of starting new endeavors.

**Live Site:** [https://dougxc.github.io/milestone/](https://dougxc.github.io/milestone/)

Interactive 3D viewer built for GitHub Pages that loads `Meshy_AI_Cybernetic_Reverie_1027093131_texture.glb` and encases the figure inside a solid refractive resin block using Three.js's physically-based [`THREE.MeshPhysicalMaterial`](https://threejs.org/docs/#api/en/materials/MeshPhysicalMaterial).


## Local Preview

Because browsers block loading `.glb` files via `file://` URLs due to CORS, run any local static HTTP server in this directory:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.
