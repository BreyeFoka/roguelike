# Roguelike

A turn-based 2D roguelike made in Unity while following Unity's official [2D Roguelike tutorial](https://learn.unity.com/project/2d-roguelike-tutorial): a procedurally generated board of tiles that the player moves across one cell at a time.

## What's here

| Path | What it is |
| --- | --- |
| `Assets/Scripts/BoardManager.cs` | Builds the board from tiles |
| `Assets/Scripts/PlayerController.cs` | Moves the player cell by cell from input |
| `Assets/Roguelike2D/` | The tutorial's sprites, audio and other assets |
| `Assets/Tiles/`, `Assets/Scenes/` | Tile palette and scenes |

Uses the Universal Render Pipeline (2D) and the Input System package.

## Status and limitations

- Early stage: the board and player movement from the first parts of the tutorial.
- The repo doesn't include Unity's `ProjectSettings/` and `Packages/` folders, so it won't open as a project on its own. To run it, create a new Unity 2D (URP) project and copy `Assets/` into it.
- No CI: building Unity projects in GitHub Actions needs a Unity licence.
