<div align="center">
  <br>
  <img width="400" src="https://raw.githubusercontent.com/mrdoob/three.js/dev/files/logo_three.js.png" alt="Three.js logo">
  <br><br>
  <h1>Awesome Three.js</h1>
  <p>
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
    <a href="https://threejs.org"><img src="https://img.shields.io/badge/three.js-r175-blue" alt="Three.js"></a>
  </p>
  <p>A curated list of awesome <a href="https://threejs.org">Three.js</a> resources, libraries, tools, shaders, and demos.</p>
</div>

---

## Contents

- [Official](#official)
- [Getting Started](#getting-started)
- [Libraries & Extensions](#libraries--extensions)
- [Physics](#physics)
- [Shaders & Materials](#shaders--materials)
- [Post-Processing](#post-processing)
- [Loaders](#loaders)
- [Controls](#controls)
- [Helpers & Debugging](#helpers--debugging)
- [React & Framework Integrations](#react--framework-integrations)
- [Animation](#animation)
- [Particles](#particles)
- [Text & Fonts](#text--fonts)
- [Audio](#audio)
- [XR / WebXR](#xr--webxr)
- [Performance](#performance)
- [Tools & Editors](#tools--editors)
- [Boilerplates & Starters](#boilerplates--starters)
- [Learning Resources](#learning-resources)
- [Books](#books)
- [YouTube Channels](#youtube-channels)
- [Blogs & Newsletters](#blogs--newsletters)
- [Showcase & Inspiration](#showcase--inspiration)
- [Community](#community)

---

## Official

- [three.js](https://github.com/mrdoob/three.js) - The library itself.
- [three.js docs](https://threejs.org/docs/) - Official documentation.
- [three.js examples](https://threejs.org/examples/) - Hundreds of official examples.
- [three.js editor](https://threejs.org/editor/) - Browser-based 3D editor.
- [three.js forum](https://discourse.threejs.org/) - Official community forum.

---

## Getting Started

- [Three.js Journey](https://threejs-journey.com) - The best paid course for learning Three.js from scratch (Bruno Simon).
- [Three.js Fundamentals](https://threejsfundamentals.org) - Free, thorough intro to Three.js concepts.
- [Discover Three.js](https://discoverthreejs.com) - Free online book for beginners.
- [Three.js Crash Course](https://www.youtube.com/watch?v=YK1Sw_hnm58) - Quick video intro.

---

## Libraries & Extensions

### Scene Graph & Helpers
- [drei](https://github.com/pmndrs/drei) - 🌟 A huge collection of helpers and abstractions for React Three Fiber.
- [theatre.js](https://www.theatrejs.com/) - Motion design editor for Three.js scenes.
- [troika-three-utils](https://github.com/protectwise/troika/tree/main/packages/troika-three-utils) - Utilities for Three.js scenes.

### Physics
- [rapier.js](https://rapier.rs/docs/user_guides/javascript/getting_started_js) - Fast Rust-powered physics engine with JS bindings.
- [cannon-es](https://github.com/pmndrs/cannon-es) - Maintained fork of Cannon.js physics.
- [Oimo.js](https://github.com/lo-th/Oimo.js) - Lightweight 3D physics for JavaScript.
- [ammo.js](https://github.com/kripken/ammo.js) - Direct port of Bullet physics to JavaScript.

### Shaders & Materials
- [lygia](https://github.com/patriciogonzalezvivo/lygia) - 🌟 Granular and modular shader library.
- [three-custom-shader-material](https://github.com/FarazzShaikh/three-custom-shader-material) - Extend Three.js materials with custom shaders.
- [glslify](https://github.com/glslify/glslify) - Node.js-style module system for GLSL.
- [three-projected-material](https://github.com/marcofugaro/three-projected-material) - Texture projection onto 3D objects.
- [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) - BVH for fast raycast and spatial queries.

### Post-Processing
- [postprocessing](https://github.com/pmndrs/postprocessing) - High-performance post-processing library.
- [three/addons/postprocessing](https://threejs.org/docs/#manual/en/introduction/Installation) - Official EffectComposer and passes.

### Loaders
- [GLTFLoader](https://threejs.org/docs/#examples/en/loaders/GLTFLoader) - Load GLTF/GLB models (official).
- [draco3d](https://github.com/google/draco) - Google Draco mesh compression.
- [basis_universal](https://github.com/BinomialLLC/basis_universal) - GPU texture compression.
- [three-obj-mtl-loader](https://github.com/mrdoob/three.js/tree/dev/examples/jsm/loaders) - OBJ/MTL loader.

### Controls
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) - Orbit camera around a target (official).
- [PointerLockControls](https://threejs.org/docs/#examples/en/controls/PointerLockControls) - FPS-style controls (official).
- [camera-controls](https://github.com/yomotsu/camera-controls) - Smooth camera controls with damping.

---

## React & Framework Integrations

- [React Three Fiber](https://github.com/pmndrs/react-three-fiber) - 🌟 React renderer for Three.js. The de facto standard.
- [drei](https://github.com/pmndrs/drei) - Helpers for React Three Fiber.
- [Threlte](https://threlte.xyz) - Three.js component framework for Svelte.
- [TresJS](https://tresjs.org) - Three.js for Vue.js.
- [angular-three](https://github.com/nartc/angular-three) - Three.js for Angular.
- [lunchbox](https://github.com/breakfast-studio/lunchboxjs) - Vue Three.js integration.

---

## Animation

- [GSAP](https://gsap.com) - 🌟 Industry-standard animation library, works beautifully with Three.js.
- [tween.js](https://github.com/tweenjs/tween.js) - Lightweight tweening engine.
- [three-vrm](https://github.com/pixiv/three-vrm) - Load and use VRM avatars.
- [mixamo](https://www.mixamo.com/) - Free character animations from Adobe.
- [motion](https://motion.dev) - Modern animation library, great with R3F.

---

## Particles

- [three-nebula](https://github.com/creativelifeform/three-nebula) - WebGL particle engine for Three.js.
- [GPUParticleSystem](https://threejs.org/examples/#webgl_gpu_particle_system) - GPU-accelerated particles (official example).
- [quarks](https://github.com/Alchemist0823/three.quarks) - High-performance particle VFX system.

---

## Text & Fonts

- [troika-three-text](https://github.com/protectwise/troika/tree/main/packages/troika-three-text) - 🌟 SDF-based 3D text rendering.
- [TextGeometry](https://threejs.org/docs/#examples/en/geometries/TextGeometry) - Extruded 3D text (official).
- [three-mesh-ui](https://github.com/felixmariotto/three-mesh-ui) - VR-ready UI with text.

---

## Audio

- [Howler.js](https://howlerjs.com) - Web audio library that pairs well with Three.js.
- [Tone.js](https://tonejs.github.io) - Web Audio framework for musical interactions.
- [PositionalAudio](https://threejs.org/docs/#api/en/audio/PositionalAudio) - Spatial audio (official).

---

## XR / WebXR

- [WebXR Device API](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API) - The web standard.
- [Three.js WebXR](https://threejs.org/docs/#manual/en/introduction/How-to-create-VR-content) - Official VR/AR guide.
- [handy-work](https://github.com/nicktarnold/handy-work) - Hand tracking for WebXR.
- [natuerlich](https://github.com/coconut-xr/natuerlich) - WebXR interaction framework for R3F.

---

## Performance

- [Stats.js](https://github.com/mrdoob/stats.js) - FPS / memory monitor (by Three.js author).
- [Spector.js](https://spector.babylonjs.com) - WebGL frame inspector.
- [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) - Speed up raycasting dramatically.
- [instanced-mesh](https://threejs.org/docs/#api/en/objects/InstancedMesh) - Render thousands of objects efficiently (official).
- [progressive-shadows](https://github.com/pmndrs/drei#progressiveshadowmap) - Baked soft shadows with no performance cost.

---

## Tools & Editors

- [Blender](https://www.blender.org) - Free 3D modeling and animation suite. Export to GLTF.
- [gltf.report](https://gltf.report) - Analyze and optimize GLTF files online.
- [Leva](https://github.com/pmndrs/leva) - React-first GUI for tweaking Three.js parameters.
- [Theatre.js](https://www.theatrejs.com) - Visual motion design tool for Three.js.
- [WebGL Insight](https://github.com/3Dparallax/insight) - Chrome extension for WebGL debugging.
- [three-inspect](https://github.com/nksaraf/three-inspect) - Scene inspector for Three.js.

---

## Boilerplates & Starters

- [vite-three-starter](https://github.com/nicktarnold/vite-three-starter) - Minimal Vite + Three.js starter.
- [threejs-starter](https://github.com/brunosimon/threejs-starter) - Bruno Simon's starter template.
- [r3f-starter](https://github.com/pmndrs/react-three-next) - React Three Fiber + Next.js starter.
- [3d-game-starter](https://github.com/nicktarnold/3d-game-starter) - Game-focused starter with physics.

---

## Learning Resources

### Courses
- [Three.js Journey](https://threejs-journey.com) - Best paid course by Bruno Simon (80+ hours).
- [WebGL Fundamentals](https://webglfundamentals.org) - Master the WebGL layer beneath Three.js.
- [ShaderToy](https://www.shadertoy.com) - Learn GLSL shaders interactively.
- [The Book of Shaders](https://thebookofshaders.com) - Free, beautiful guide to fragment shaders.

### Tutorials
- [Codrops Three.js tutorials](https://tympanus.net/codrops/tag/three-js/) - High-quality creative coding tutorials.
- [Maxime Heckel's Blog](https://blog.maximeheckel.com) - In-depth R3F and shader articles.
- [Yuri Artiukh (akella)](https://www.youtube.com/@akella_) - Real-world creative coding breakdowns.
- [SimonDev](https://www.youtube.com/@simondev758) - Game dev and Three.js tutorials.

---

## Books

- [Three.js Cookbook](https://www.packtpub.com/product/threejs-cookbook/9781788473989) - Recipes for common Three.js tasks.
- [Learning Three.js](https://www.packtpub.com/product/learning-threejs-third-edition/9781788833288) - Comprehensive introduction.
- [Discover Three.js](https://discoverthreejs.com) - Free online book.
- [The Book of Shaders](https://thebookofshaders.com) - Essential for shader programming.

---

## YouTube Channels

- [Three.js Journey](https://www.youtube.com/@threejsjourney) - Bruno Simon's channel.
- [Yuri Artiukh (akella)](https://www.youtube.com/@akella_) - Creative WebGL.
- [SimonDev](https://www.youtube.com/@simondev758) - 3D games and Three.js.
- [Suboptimal Engineer](https://www.youtube.com/@SuboptimalEng) - Visualizations and algorithms in Three.js.
- [Waverider Dev](https://www.youtube.com/@waverider_dev) - Short, focused Three.js tips.

---

## Blogs & Newsletters

- [Codrops](https://tympanus.net/codrops/) - Creative front-end techniques and experiments.
- [Maxime Heckel](https://blog.maximeheckel.com) - Deep dives into shaders and R3F.
- [Three.js forum](https://discourse.threejs.org/) - Community discussions and showcases.

---

## Showcase & Inspiration

- [Awwwards](https://www.awwwards.com/websites/three-js/) - Award-winning Three.js websites.
- [chrome experiments](https://experiments.withgoogle.com/collection/webgl) - Google's WebGL experiments.
- [Bruno Simon Portfolio](https://bruno-simon.com) - The legendary Three.js portfolio.
- [Active Theory](https://activetheory.net) - Studio known for immersive WebGL work.
- [Lusion](https://lusion.co) - Award-winning creative studio using Three.js.

---

## Community

- [Three.js Forum](https://discourse.threejs.org/) - Official community forum.
- [Three.js Discord](https://discord.gg/threejs) - Real-time chat.
- [r/threejs](https://reddit.com/r/threejs) - Reddit community.
- [Twitter #threejs](https://twitter.com/hashtag/threejs) - Follow creative coders.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [NzJulien](https://github.com/NzJulien) has waived all copyright and related rights to this work.
