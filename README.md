# Artificial-Intelligence

## Tic-Tac-Toe (Minimax AI)
## ScreenShots
![1](https://github.com/user-attachments/assets/47163d0a-1685-4538-b766-e973adb9abda)
![2](https://github.com/user-attachments/assets/9866bd86-e141-4944-9196-b3cad4c23a91)

**This repository** contains a Tic-Tac-Toe game in Python featuring:


- A human player vs. an AI player
- The AI makes optimal moves using the Minimax algorithm
- A graphical interface built with pygame

---

## Repository Contents

- **tictactoe.py**  
  Contains the core game logic including:
  - Board representation and initialization
  - Functions to determine the current player (`player`)
  - Finding available actions (`actions`)
  - Generating the result of a move (`result`)
  - Checking for a winner (`winner`)
  - Determining terminal states (`terminal`)
  - Evaluating board utility (`utility`)
  - The Minimax algorithm and its helper functions (`minimax`, `max_value`, `min_value`)
  - 

- **runner.py**  
  Contains the pygame graphical interface that:
  - Draws the Tic-Tac-Toe board
  - Handles user clicks and updates the game state
  - Integrates with `tictactoe.py` to process moves

- **requirements.txt**  
  Lists the required Python packages (e.g., `pygame`) for running the project.



## How to Run the Game

1. **Install Python 3.x** (if not already installed) from [python.org](https://www.python.org/downloads/).

2. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/YourUsername/Artificial-Intelligence-Assignments.git
   ```


   Or download the ZIP file and extract it.

4. **Navigate to the Project Directory:**

   ```bash
   cd Artificial-Intelligence-Assignments
   
5. **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

6. **Run the Game:**
  ```bash
     python runner.py
  ```




**A pygame window should open where you can play Tic-Tac-Toe against the AI.**




















