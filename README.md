# Alien_Invasion 
## Overview

**Alien Invasion** is a simple yet engaging game inspired by the classic "Space Invaders". This is my first game project, and it follows a tutorial from Eric Matthes' "Python Crash Course, 2nd Edition". The game involves controlling a ship to shoot down waves of aliens before they reach the bottom of the screen.

## Features

- Control a spaceship using the keyboard to move left, right, and shoot bullets.
- Waves of aliens descend from the top of the screen.
- Score points by shooting down aliens.
- Fullscreen mode for an immersive experience.
- A "Play" button to start the game.

## Screenshots

![start_screen](https://github.com/robmad93/Alien_Invasion/assets/131868277/81c288b4-643f-4e1b-81f0-43b08226bcf1)


## Installation

### Prerequisites

Make sure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/).

### Steps

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/your-username/alien-invasion.git
    cd alien-invasion
    ```

2. **Install Required Libraries**:

    Install the necessary libraries using pip:

    ```bash
    pip install -r requirements.txt
    ```

    Make sure `requirements.txt` contains:

    ```
    pygame
    ```

3. **Run the Game**:

    ```bash
    python alien_invasion.py
    ```

## How to Play

- Use the left and right arrow keys to move your spaceship.
- Press the space bar to shoot bullets.
- Press "P" or click "Play" to start the game.
- Avoid aliens reaching the bottom of the screen or colliding with your spaceship.

## Credits

- **Eric Matthes**: This project was developed by following the tutorial in "Python Crash Course, 2nd Edition". A big thank you to Eric Matthes for his comprehensive guide to learning Python.
- **Pixabay**: For providing access to freely licensed graphics used in this project. Visit [Pixabay](https://pixabay.com/) for more resources.

## Possible future updates
- Include a settings option from within the game that allows easier changes to ship/alien/bullet attributes and difficulty.
- Give aliens the ability to shoot down at the player with projectiles.
- Provide temporary power-ups (e.g., faster firing, scatter-shot bullets, etc.) upon meeting certain criteria (e.g., reaching a set number of points).
