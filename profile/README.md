# Fourth Temple

Fourth Temple builds production-ready open-source creative tools for audiovisual work.

The suite focuses on outstanding engineering quality, unique features, and impeccably designed software for rhythm-driven music creation, animation cleanup, character asset repair, and browser-first production workflows.

## Projects

### Rhythm Artist

A beat-making and rhythm composition system for building musical ideas quickly in the browser.

### Cleanup

A browser-based character cleanup workflow for imported, generated, or motion-tracked assets. Cleanup focuses on practical fixes for animation, rigging, textures, and export.

### [`@fourthtemple/fbx-exporter`](https://github.com/fourthtemple/fbx-exporter)

A from-scratch binary FBX exporter for browser and Node pipelines.

It exports Three.js-style scenes with meshes, hierarchy, materials, textures, embedded texture content, skeletons, skinning, morph targets, and baked animation curves. The package is plain ESM JavaScript, has no runtime dependencies, includes TypeScript declarations, and supports target presets for Three.js/Web, Unity, Unreal, Blender, and Maya.

Install from npm:

```bash
npm install @fourthtemple/fbx-exporter
```

Use it from JavaScript:

```js
import { exportFbx } from "@fourthtemple/fbx-exporter";

const bytes = exportFbx(scene, {
  target: "blender",
  embedTextures: true
});
```

## Links

- npm: [`@fourthtemple/fbx-exporter`](https://www.npmjs.com/package/@fourthtemple/fbx-exporter)
- GitHub: [`fourthtemple/fbx-exporter`](https://github.com/fourthtemple/fbx-exporter)
