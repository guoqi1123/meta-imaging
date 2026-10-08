# Third-Party 3D Models

## stanford-bunny.glb

- **Title:** Stanford Bunny
- **Source:** Stanford Computer Graphics Laboratory — Stanford 3D Scanning Repository
  (https://graphics.stanford.edu/data/3Dscanrep/)
- **Notes:** Classic scanned test model. Used in the optics scenes as the
  subject placed on the table / shown on the sensor readout.
- **Format:** Draco-compressed glTF binary (95.6 KB), converted from the
  original 2.4 MB OBJ (MeshLab export, 35,947 vertices / 69,451 faces, no
  normals) with `obj2gltf` + `gltf-transform draco`. The OBJ is in git history
  (before the perf/adaptive-quality branch) if a re-export is ever needed.
  The Draco decoder in `public/assets/draco/` is copied verbatim from
  `three/examples/jsm/libs/draco/gltf/` (three r160).
