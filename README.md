# PoorlyDesignedRobots


Instructions
===============
- Control the orange and blue robots to navigate through the different levels.
- The orange robot can only move left and right, whereas the blue robot can only move up and down. 
- To complete a level, each robot needs to reach their corresponding coloured endzone. 
- Each robot can push eachother or stack upon eachother.
- Use the Button, Pressure Plate, Translocator, and Bridge Tiles to navigate through the levels.


Controls
===============
**Orange Robot:**   A/D Keys or Left/Right Arrow Keys  <br>
**Blue Robot:**     W/S Keys or Up/Down Arrow Keys  <br>


Game Architecture
===============
* Our game uses a 3D grid tile system. Each individual tile keeps track of its surrounding neighbours. 
* There are multiple different tile types:
  * Floor Tile
  * Air Tile
  * Bridge Tile
  * Button Tile
  * Pressure Plate Tile
  * Translocator Tile
  * Orange EndZonet Tile
  * Blue EndZone Tile
