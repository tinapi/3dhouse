# 3dhouse
A 3D house explorer using webGL

- Built a 3D house model using Maya and exported it to WebGL
- Implemented following features
  - Room floor highlighting upon mouse over
  - Go to a designated camera position and enter first-person view upon clicking a room’s floor
  - A roof that is transparent in top-down view and non-transparent in first-person view
  - Mirrors in the bedroom and bathroom
  - Drop-down selector for changing the floor textures in every room (and the hallways) Skybox
  - First-person mouse movement boundary that the GUI can be manipulated without the camera still moving
  - Collision detection while in first-person view ONLY from the front, not form the back
  - One custom shader used to add color to the bedroom walls
  - Drop down selector to switch between default positions for top-down view and first-person view
  - Texture swapping for all ground level textures via the GUI
  - Light intensity adjustment from the GUI for one light
  - Night lighting of the house via a GUI toggle
  - Help instructions available from the GUI
  - Two different GUI’s implemented; one for top-down view, the other for first-person view
  - Two different types of controllers; firstPersonControls and orbitControls
