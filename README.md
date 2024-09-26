# Tic-Tac-Toe AI Game

## Overview

This repository contains two Jupyter notebooks that allow you to play Tic-Tac-Toe against an AI opponent and analyze various AI strategies through simulations.

- **`tictactoe_main_game.ipynb`**: Play Tic-Tac-Toe against an AI using a minimax algorithm with alpha-beta pruning.
- **`tictactoe_test_cases.ipynb`**: Run simulations to analyze the performance of different AI strategies.

---

## `tictactoe_main_game.ipynb`

### Overview

This notebook lets you play a game of Tic-Tac-Toe against an AI directly within the notebook. The AI uses advanced algorithms to determine the best possible moves based on the current game state.

### Instructions for Playing

1. **Starting the Game:**
   - Open the `tictactoe_main_game.ipynb` notebook in Jupyter Notebook or JupyterLab.
   - Run all cells to initialize the game. You can do this by clicking **Kernel** > **Restart & Run All** in the menu bar.

2. **Playing Your Move:**
   - When prompted, enter your move by specifying the **row** and **column** numbers separated by a space. For example, typing `2 0` places your tile on the 3rd row and 1st column.
   - Make sure the position you choose is empty; otherwise, you'll be asked to try again.

3. **Viewing Game Output:**
   - After each move, the current state of the board is displayed.
   - Continue entering your moves when prompted until the game concludes.

### Game Rules

- The game is played on a **4x4 grid**.
- **You** play as **'O'**, and the **AI** plays as **'X'**.
- The objective is to align **four** of your symbols vertically, horizontally, or diagonally.
- The game ends when a player wins or when the board is full, resulting in a tie.

### Technical Details

- The AI uses a **minimax algorithm with alpha-beta pruning** to efficiently search the game tree and determine optimal moves.
- The 4x4 grid increases the game's complexity, providing a more challenging experience.

---

## `tictactoe_test_cases.ipynb`

### Overview

This notebook is designed to simulate multiple Tic-Tac-Toe games using different AI strategies. It helps analyze the performance of various strategies under controlled conditions.

### Running Simulations

1. **Setting Up:**
   - Open the `tictactoe_test_cases.ipynb` notebook in Jupyter Notebook or JupyterLab.
   - Run all cells sequentially to set up functions and variables.

2. **Running Simulations:**
   - The last cell initiates the simulation process, playing multiple games using different AI strategies.
   - Adjust parameters like `num_simulations` and `depth_limit` to control the number of games and AI search depth.

3. **Simulation Duration:**
   - Depending on the number of simulations and complexity, experiments may take several minutes to complete.
   - Progress and results are displayed as simulations run.

### Results and Analysis

- The notebook calculates and displays statistics for each strategy, including:
  - **Win/Loss/Draw ratios**
  - **Average decision times**
- Data is visualized through plots, providing insights into each strategy's performance.

### Experiment Details

- **Strategies Tested:**
  - **Aggressive**: Prioritizes offensive moves to win quickly.
  - **Defensive**: Focuses on blocking the opponent's winning opportunities.
  - **Balanced**: Combines offensive and defensive tactics.
  - **Random**: Chooses moves randomly.
  - **Corner**: Prioritizes taking corner positions.

- **Effectiveness Metrics:**
  - Strategies are evaluated based on predefined metrics to assess their performance comprehensively.

### Usage

- Ideal for those interested in AI strategy development and analysis.
- Modify simulation parameters to explore different aspects of AI performance.

---

## Requirements

- **Python 3.x**
- **Jupyter Notebook** or **JupyterLab**
- **Python Packages:**
  - `math`
  - `random`
  - `time`
  - `pandas`
  - `matplotlib`

## Installation

1. **Clone the Repository:**

   ```bash
   git clone <repository_url>
   ```

2. **Install Required Packages:**

   Install any missing packages using `pip`:

   ```bash
   pip install pandas matplotlib
   ```

3. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

4. **Open the Notebooks:**

   - Navigate to `tictactoe_main_game.ipynb` or `tictactoe_test_cases.ipynb` within the Jupyter interface.

## Notes

- Ensure that all cells are run in order for proper initialization.
- The game and simulations are designed to run within the Jupyter environment.
- Be patient with longer simulations; complex AI calculations may take time.

## License

[Include license information here if applicable.]

---

Feel free to reach out if you have any questions or need further assistance!
