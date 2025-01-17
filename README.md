# Snake Game with AI and Human Playable Version

Welcome to the **Snake Game Project**! This repository contains two versions of the classic Snake game:

1. **Human Playable Version** - Play the game yourself using arrow keys.
2. **AI-Powered Version** - An AI trains itself to play the game using reinforcement learning.

Additionally, this project includes visualizations of the AI training process and supplementary media to demonstrate the game.

---

## Features

### 1. Human Playable Version

The traditional Snake game implemented using Python and Pygame:

- **Simple Controls**: Use arrow keys to move the snake.
- **Dynamic Gameplay**: The snake grows and the game speeds up as you progress.
- **Collision Detection**: Ends the game when the snake hits a wall or itself.
- **Score Tracking**: Your score is displayed in real-time.

### 2. AI-Powered Version

This version leverages **Deep Q-Learning** to train an AI to play Snake:

- **Neural Network Architecture**:
  - Input Layer: Game state representation.
  - Hidden Layer: Processes the state.
  - Output Layer: Predicts the best move.
- **Training Process**:
  - Rewards for collecting food and penalties for collisions.
  - Updates Q-values using the Bellman equation.
- **Dynamic Visualizations**:
  - Training progress is plotted in real-time to track scores and performance.

### 3. Supplementary Media

- **Screenshots**: Captures of the gameplay experience.
- **Video Demonstration**: A walkthrough of the game in action.

---

## Installation

### Prerequisites

- Python 3.8+
- Required libraries:
  - `pygame`
  - `torch`
  - `matplotlib`

Install the dependencies using pip:

```bash
pip install pygame torch matplotlib
```

### Clone the Repository

```bash
git clone https://github.com/your-repo-name/snake-game.git
cd snake-game
```

---

## How to Run

### Human Playable Version

1. Navigate to the project directory.
2. Run the `human_snake_game.py` file:
   ```bash
   python human_snake_game.py
   ```
3. Use the arrow keys to control the snake and enjoy the game.

### AI-Powered Version

1. Run the `ai_snake_game.py` file:
   ```bash
   python ai_snake_game.py
   ```
2. Observe the training progress and watch the AI improve over time.

---

## Media

### Screenshots

Below are some snapshots of the game:

- **Game Start**:

  ![Game Start](Screenshot1.png)

- **Mid-Game**:

  ![Mid-Game](Screenshot2.png)

- **Game Over**:

  ![Game Over](Screenshot3.png)

### Video Demonstration

Watch the full gameplay demonstration here:

[Gameplay Video](Screen%20Recording.mov)

---

## Project Structure

```plaintext
snake-game/
|-- ai_snake_game.py        # AI-powered version of Snake
|-- human_snake_game.py     # Human playable version
|-- model/                  # Saved AI model
|-- README.md               # Project documentation
|-- requirements.txt        # List of dependencies
|-- Screenshot1.png         # Gameplay screenshot 1
|-- Screenshot2.png         # Gameplay screenshot 2
|-- Screenshot3.png         # Gameplay screenshot 3
|-- Screen Recording.mov    # Gameplay video demonstration
```

---

## Acknowledgments

This project was developed using:

- **Pygame** for the human-playable version.
- **PyTorch** for implementing the deep learning model.
- **Matplotlib** for visualizing training progress.

---

## License

This project is licensed under the MIT License. Feel free to use and modify it as you see fit.

---

## Contact

For questions or suggestions, please reach out:

- **Author**: Matej Popovski
- **Email**: [matejpopovski@example.com](mailto:matejpopovski@example.com)

Enjoy the game!
