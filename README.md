# Magic Park Explorer

A Unity project (2022.3 LTS).

## Opening the project

1. Install [Unity Hub](https://unity.com/download) and a **Unity 2022.3** editor (e.g. 2022.3.x LTS).
2. In Unity Hub, click **Add** → **Add project from disk** and choose this folder.
3. Open the project. Unity will create any missing `ProjectSettings` and the `Library` folder on first load.

## Project structure

- **Assets/** – Scenes, scripts, prefabs, and other game content  
  - `Scenes/` – Unity scenes  
  - `Scripts/` – C# scripts  
  - `Resources/` – Runtime-loaded assets  
- **Packages/** – Package Manager manifest and lockfile  
- **ProjectSettings/** – Project and build settings  

## Requirements

- Unity 2022.3.x (LTS) or compatible 2022.3 version

## Why Unity?

- Unity provides a **mature 3D engine** with built-in tooling (scene editor, lighting, physics) that fits an explorable park environment well.
- The **cross-platform build pipeline** makes it straightforward to target desktop, web, and potentially mobile builds from the same project.
- The **component-based workflow** (GameObjects + MonoBehaviours) maps naturally to park attractions, points of interest, and interactive UI elements.
- A large ecosystem of **packages, assets, and learning resources** reduces implementation time for navigation, UI, and environment art.
