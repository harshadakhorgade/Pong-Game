
# Pong Game 🏓  
A fun and classic **Pong Game** built using Python and the `turtle` module. Challenge a friend and enjoy this retro-inspired two-player game!

---

## Features ✨  
- **Two-player gameplay**: Compete with a friend using simple keyboard controls.  
- **Dynamic ball movement**: The ball speeds up as the game progresses.  
- **Score tracking**: Displays points for both players during the game.  
- **Retro aesthetics**: Black background and clean paddles for a nostalgic look.  

---

## How to Play 🎮  
- **Player 1 (Left Paddle)**:  
  - Move up: Press `W`  
  - Move down: Press `S`  

- **Player 2 (Right Paddle)**:  
  - Move up: Press `Up Arrow`  
  - Move down: Press `Down Arrow`  

- **Objective**: Hit the ball past your opponent’s paddle to score points.  

---

## Installation 🚀  
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/Pong-Game.git
   cd Pong-Game
   ```  
2. **Run the Game**:  
   Ensure Python 3 is installed, then run:  
   ```bash
   python main.py
   ```  

---

## Preview 📸  
![Pong Game Screenshot](assets/Screenshot%202024-12-02%20205506.png) 

---

## Code Highlights 💡  
This game is built using Python's `turtle` module for graphics and animations.  
Here’s how the game detects collisions with the wall:  
```python
if ball.ycor() > 280 or ball.ycor() < -280:
    ball.bounce_y()
```

Enjoy the game and let the best player win! 🎉
