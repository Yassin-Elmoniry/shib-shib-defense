# Shib-Shib Defense

A 2D lane-defense game written from scratch in **C++ with modern OpenGL** (GLFW + GLAD, custom shaders). No game engine is used. An Egyptian family defends the kitchen from pests: **Teta** blocks, **Mama** attacks up close with her shib-shib (slipper), and **Brother** fires bug spray from range.

## Features
- Lane-based gameplay with mouse lane selection and highlighted lanes
- Coin economy with purchasable unit cards; cards gray out when you can't afford them
- Three unit types: melee, ranged with projectiles, and a blocker that protects units behind it
- Enemy waves, collision and damage, and a game-over condition when a pest reaches the pot
- Main menu, pause menu, cutscene with voice-over, and a seven-segment coin display
- Every shape is drawn from primitives (rectangles, triangles, circles) through a shader pipeline

## Tech
C++ · OpenGL 3.3 · GLFW · GLAD · GLSL · Visual Studio

## Build
Open `Project1.slnx` in Visual Studio 2022 and build x64. GLFW and GLAD are included in `Libraries/`.

## Team & My Contributions
Built as a team project for **DMET502 Computer Graphics** at the German University in Cairo. Original repository: [Wahba475/Graphics-project](https://github.com/Wahba475/Graphics-project). Full commit history is preserved here.

**My part (Yassin Elmoniry), player systems and UI:**
- Character drawings and attack animations for Teta, Mama, and Brother
- Mouse input: lane selection, lane highlighting, and buying and placing units
- Coin economy, unit cards with prices, hover effects, and grayscale for locked cards
- Seven-segment digit rendering for the coin counter and card prices
- Player movement, Teta's protection logic, and Brother's projectile shooting
