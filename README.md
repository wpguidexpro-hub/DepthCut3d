# DepthCut3D

Browser-based 3D studio inspired by Blender and Prisma3D.

## Run
`npm install`
`npm run dev`

## Desktop Bridge
The local bridge is included in `desktop-bridge.mjs` and listens on `127.0.0.1:4317`. Run `npm run bridge` on the connected PC. The editor can save project JSON through the bridge and also download a local copy.

## Roadmap
GLB/GLTF import, real transform gizmos, materials, camera presets, animation timeline, project autosave, desktop render/export, and a lightweight scene graph.