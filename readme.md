[![Preview](https://github.com/tetreum/brickcraft/raw/main/Preview/preview.gif)](https://github.com/tetreum/brickcraft/raw/main/Preview/preview.gif)

[![Logo](https://github.com/tetreum/brickcraft/raw/main/Assets/Textures/Logo.png)](https://github.com/tetreum/brickcraft/raw/main/Assets/Textures/Logo.png)

# Brickcraft

WIP. Combining Lego like bricks + Minecraft buidling style in Unity.

[![Preview](https://github.com/tetreum/brickcraft/raw/main/Preview/1.png)](https://github.com/tetreum/brickcraft/raw/main/Preview/1.png)

## Controls

- WASD - Move character
- Space - Jump
- TAB - Switch between fast inventory slots
- I - Open inventory
- Left click - Remove blocks
- Right click (having a block selected in inventory) - Adds a block
- Mouse wheel (having a block selected in inventory) - Rotates block


## How can i add a new model?

1. Brick models & their prefabs are stored in https://github.com/tetreum/brickcraft/tree/main/Assets/Models/Bricks
2. The icon is stored at https://github.com/tetreum/brickcraft/tree/main/Assets/Resources/Textures/Bricks
3. Prefab must be listed at Server -> prefabs scene object.
4. Model specs must be added at Server.cs#setupBrickModels() (https://github.com/tetreum/brickcraft/blob/main/Assets/Scripts/Server.cs#L146)
2. Items using it must be added at Server.cs#items var (https://github.com/tetreum/brickcraft/blob/main/Assets/Scripts/Server.cs#L12)

## How can i add a new brick material/texture?

1. They're stored in Assets/Materials/BrickColors/ (https://github.com/tetreum/brickcraft/tree/main/Assets/Materials/BrickColors)
2. List the new materials at Canvas (scene object) -> Game -> BrickMaterials var.

## Credits

- Tapping sound effect - https://freesound.org/people/rioforce/sounds/233654/
- Dig + remove block sound effect - https://freesound.org/people/Agaxly/sounds/213005/
- Brick models - https://www.mecabricks.com/