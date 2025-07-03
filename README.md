# Space Blasters: A 2D Pygame Space Shooter
A fast-paced, two-player local combat game where players pilot spaceships and battle to be the last one standing. This project was built using Python and the Pygame library.

## Features

* **Two-Player Local Multiplayer**: Battle against a friend on the same keyboard.
* **Health System**: Each ship has a limited amount of health. The first player to deplete their opponent's health wins.
* **Sound Effects**: Each player has unique sound effects for firing their weapons.
* **Background Music**: Continuous background music plays throughout the game for an immersive experience.
* **Win Condition**: The game ends when one player's health reaches zero, and a victory message is displayed.

## Controls

The controls are split between the left and right sides of the keyboard for two players.

| Player            | Action          | Key(s)                             |
| ----------------- | --------------- | ---------------------------------- |
| **Player 1 (Yellow)** | Move Ship       | W (Up), A (Left), S (Down), D (Right) |
|                   | Fire Bullet     | Q                                  |
| **Player 2 (Red)** | Move Ship       | Arrow Keys (Up, Left, Down, Right) |
|                   | Fire Bullet     | M                                  |

## Getting Started

To run this game on your local machine, follow these simple steps.

### Prerequisites

* Python 3.x
* Pygame library

### Installation

1.  **Clone the repository (or download the source files):**
    ```sh
    git clone [https://your-repository-url.git](https://your-repository-url.git)
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd your-project-folder
    ```

3.  **Install Pygame:**
    ```sh
    pip install pygame
    ```

4.  **Run the game:**
    ```sh
    python main.py
    ```

## Asset Files

The game requires an `Assets` folder in the same directory as `main.py` with the following files:

* **Images:**
    * `spaceship_yellow.png`
    * `spaceship_red.png`
    * `space.png`
* **Sounds & Music:**
    * `Gun+Silencer.mp3` (Yellow Ship Fire Sound)
    * `Grenade+1.mp3` (Red Ship Fire Sound)
    * `background-music.mp3` (Background Music)

---

Developed by ASHLEY WYATT 
