# CS330 Final Project: 3D Scene

Final project for SNHU's CS-330 (Computational Graphics and Visualization): an OpenGL scene that recreates a real 2D reference photo as a lit, textured 3D environment. This built on the weekly exercises in [CS-330](https://github.com/KewaneeMcGhee-Wiggins/CS-330).

## Tech stack

- C++, OpenGL (GLEW + GLFW, vendored under `Final Project Scene/Module3/Module3/`)
- Wavefront `.obj` models with texture maps, custom camera controls (`Camera.h`)

## ⚠️ Repo status: incomplete

This repo currently only has the **assets** for the final scene — the 3D models (`.obj`), textures, the camera header, and the vendored GLEW/GLFW libraries. The actual scene source file (the `.cpp`/`main.cpp` that builds and renders the scene) and the Visual Studio project/solution file were never committed, so **this can't currently be built or run**.

If you still have the original project folder locally, adding the missing `.cpp` and `.vcxproj`/`.sln` files here would make this buildable again.

## What's here

```
Final Project Scene/Module3/Module3/
├── Camera.h                  # first-person camera controls
├── AcetoneBottle*.obj        # 3D models used in the scene
├── AcetoneLabel.png/.JPG     # label texture
├── glew-2.1.0/               # vendored OpenGL Extension Wrangler library
└── glfw-3.3.2.bin.WIN64/     # vendored GLFW (windowing/input) library
```
