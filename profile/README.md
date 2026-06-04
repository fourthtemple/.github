# Fourth Temple

Fourth Temple builds production-ready creative tools for audiovisual work.

The work spans music creation, animation, asset workflows, and experimental production systems, with an emphasis on outstanding engineering quality, unique features, and carefully designed software. Some tools are open source, some are in active development, and the long-term goal is a suite that works well online and offline, including high-performance native builds where they make sense.

## Projects

### Rhythm Artist

A music creation system for building and shaping musical ideas quickly.

### Cleanup

An animation and asset workflow for imported, generated, or motion-tracked material. Cleanup focuses on practical editing, repair, and export tools for creative production.

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
