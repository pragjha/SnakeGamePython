Snake Game in Python (Turtle & OOP)

This is a simple implementation of the classic Snake game using Python's `turtle` module and Object-Oriented Programming (OOP) principles. The game is built with the goal of demonstrating the application of OOP in game development.

Table of Contents

1. About
2. Features
3. How to Play
4. Code Structure

About-This project is a basic version of the Snake game built with Python using the `turtle` module for graphics. The game is designed with OOP concepts to structure the game logic into multiple classes such as Snake, Food, Scoreboard and main.

Features

- Snake Movement: Control the snake with arrow keys.
- Growing Snake: Each time the snake eats food, it grows longer.
- Collision Detection: Detect collisions with the walls and itself.
- Score Tracking: Keep track of your score as the snake eats food.
- Game Over Screen: The game ends when the snake hits the wall or itself.


How to Play

- Use the  arrow keys (Up, Down, Left, Right) to control the snake's direction.
- Eat the food(green squares) to grow the snake.
- Avoid colliding with the walls or the snake's own body.
- The game will end when the snake collides with itself or the wall.
- Your score is displayed on the top left of the screen.

Code Structure

Main Components:

1. Snake Class- Manages the snake's creation, position, movement, and growth.

2. Food Class-Handles food generation and interaction with the snake.

3. main Class- Controls the overall game flow, including initialization, score tracking, and collision detection.

4. Scoreboard Class-Keeps track of your score. Everytime the snake eats food, your score increases by one.



Feel free to replace `snake_game.py` with your actual filename and modify any sections to fit your actual project structure and specific instructions.
