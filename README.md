# Hexbound
## ✅ Tower Tactics: Hexbound – MVP Checklist
### 🎮 Core Gameplay Loop

Player enters a procedurally-generated hex-based floor

Fights enemies using tactical, turn-based combat

    Proceeds to the next floor upon winning

### 🛠️ Hex Grid System

Implement axial coordinate hex grid

Draw hex tiles using Java2D (Polygon)

Convert screen coordinates to hex coordinates

Highlight tile on mouse hover/click

    Store tile data (walkable, occupied, etc.)

### 🧍 Player

Add a player unit with starting stats (HP, ATK, MOV)

Select player unit via mouse

Move to valid adjacent tiles

Attack adjacent enemy

    Display player stats on screen

### 👾 Enemies

Spawn 2–3 enemies on each floor

Simple AI: move toward player

Attack if adjacent to player

    Enemy has HP and damage stats

### 🔄 Turn System

Implement turn order (player → enemies)

Highlight available moves during player turn

Lock input during enemy turn

    End player turn after move/attack

### 🧱 Floor Generation

Generate a connected blob of hex tiles for each floor

Place player and enemies on opposite ends

    Keep floor size manageable (10–20 tiles radius)

### 🏆 Victory / Defeat

Win condition: all enemies defeated

Lose condition: player HP ≤ 0

Show simple game over screen

    Show “Next Floor” button on win

### ✨ Optional (Stretch Goals)

Add a simple stat upgrade after each floor

Add fog of war (reveal tiles within vision range)

Use colored shapes to represent attacks or health

Play sound on attack or movement

    Add hex tile terrain types (obstacles, slow terrain, etc.)

### 🎨 Visual Design (MVP Style)

Use flat-colored hexagons for tiles

Red = enemy, Blue = player, Gray = neutral

UI: show current turn and health bars

Keep it functional over pretty—for now!
