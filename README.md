# Tower Defense

A Tower Defense game for the Jack platform (Nand2Tetris).

## Features
- **3 Maps**: Classic, ZigZag, and U-Turn.
- **Visuals**: Skeleton enemies and Arrow towers (Bitmap Sprites).
- **Gameplay**:
  - Build towers (Cost: 50c) to defend the path.
  - Earn money by defeating enemies.
  - Survive 10 Waves to win.
  - Lives system (20 Lives).
- **Interface**:
  - Start Screen with instructions.
  - HUD with Wave, Enemies, Gold, and Lives.
  - Win/Game Over screens.

## Controls
- **Arrows**: Move cursor
- **Space**: Build Tower / Sell Tower (+30c refund)
- **S**: Start Next Wave
- **1, 2, 3**: Select Map (at start)
- **Q**: Quit

## How to Run
1. Open the **VM Emulator**.
2. Load the compiled `.vm` files (or the directory).
3. Set Animate to **No Animation** (Fast) or **Line**.
4. Run the simulation.
5. Follow the on-screen instructions.

## Project Structure
- `Game.jack`: Main game loop and logic.
- `Tower.jack`: Tower logic and drawing.
- `Enemy.jack`: Enemy movement and sprites.
- `Cursor.jack`: Player cursor handling.
- `Main.jack`: Entry point.
