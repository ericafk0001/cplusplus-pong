# Ping Pong Game

This Ping Pong game is a simple recreationof the classic Pong game built with **C++** using the **raylib** library. Control the player's paddle using `W` (up) and `S` (down) keys.

## Technical Details

- **Language:** C++
- **Library:** raylib
- **Game Mechanics:**
  - Collision detection between the ball and paddles.
  - Ball bounces off walls and paddles at adjustable speeds.
  - Paddle movement is restricted to stay within screen boundaries.
- **Display:**
  - Real-time score updates on both sides of the screen.
  - A dividing line in the center for a classic Pong look.

## How It Works

The game loop handles drawing, updating positions, and detecting collisions. Key classes include:

- **Ball:** Manages ball movement, collision, and scoring logic.
- **Paddle:** Represents the player's paddle with movement controls.
- **cpuPaddle:** An AI-controlled paddle that reacts to the ball's position.

## Acknowledgments

This project utilizes the **raylib** library for graphics rendering, known for its simplicity and performance, making it ideal for game development.
