# 🎮 Tic-Tac-Toe AI Game (4x4 Grid) — Minimax + Strategy Simulation

This project implements a customizable **Tic-Tac-Toe AI game** on a **4x4 board**, powered by the **Minimax algorithm with alpha-beta pruning**. It also includes a simulation notebook to evaluate multiple AI strategies using statistical analysis and visualizations.

> 🧠 Built for those exploring **AI search strategies**, **heuristic design**, or **automated game simulations**.

---

## 🚀 Key Components

- 🧠 `tictactoe_main_game.ipynb`: Play Tic-Tac-Toe against an AI using **Minimax + Alpha-Beta Pruning**.
- 📊 `tictactoe_test_cases.ipynb`: Simulate and evaluate **5 AI strategies** (aggressive, defensive, random, etc.) over multiple games.

---

## 🧠 Gameplay: `tictactoe_main_game.ipynb`

### How to Play

1. Open the notebook in **Jupyter Notebook** or **JupyterLab**.
2. Click **Kernel > Restart & Run All** to start the game.
3. When prompted, enter your move as `row column` (e.g., `2 0`).

### Game Details

- **Grid**: 4x4
- **You**: `'O'`  
- **AI**: `'X'`  
- **Goal**: Align 4 of your symbols vertically, horizontally, or diagonally.

### AI Design

- **Algorithm**: Minimax with alpha-beta pruning.
- **Heuristic Evaluation**: Scores board states based on win conditions and future threats.
- **Search Depth**: Balanced for real-time interactivity and strategic depth.

---

## 🤖 AI Strategy Simulation: `tictactoe_test_cases.ipynb`

Use this notebook to run simulations comparing different strategies in self-play and AI-vs-AI settings.

### Included Strategies

| Strategy     | Behavior |
|--------------|----------|
| 🎯 **Aggressive** | Maximizes own win conditions |
| 🛡️ **Defensive**  | Blocks opponent’s winning paths |
| ⚖️ **Balanced**   | Blends offense and defense |
| 🎲 **Random**     | Makes arbitrary legal moves |
| 🔲 **Corner-Based** | Prioritizes corners and edges |

### Metrics Collected

- ✅ **Win / Loss / Draw ratios**
- ⏱️ **Average decision time per move**
- 📊 **Effectiveness plots** (matplotlib visualizations)

### Customization

You can adjust:
```python
num_simulations = 100
depth_limit = 3
```
to control simulation size and search depth.

---

## ⚙️ Installation & Setup

Follow these steps to get started:

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/tictactoe-ai.git
cd tictactoe-ai
```

### 2. (Optional) Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3. Install Required Dependencies
```bash
pip install pandas matplotlib
```

### 4. Launch Jupyter Notebook
If needed:
```bash
pip install notebook
```
Then:
```bash
jupyter notebook
```

### 5. Open the Notebooks
Navigate to:
- `tictactoe_main_game.ipynb` to play the game.
- `tictactoe_test_cases.ipynb` to run strategy comparisons.

---

## 📁 File Structure

```
tictactoe-ai/
├── tictactoe_main_game.ipynb     # Playable 4x4 Tic-Tac-Toe AI game
├── tictactoe_test_cases.ipynb    # Strategy simulation and analysis
├── README.md                     # You're here!
```

---

## 🌱 Future Improvements

- 🔄 **Custom Grid Sizes**: Generalize to NxN boards.
- 🧠 **Reinforcement Learning Agent**: Train with Q-learning or DQN.
- 📊 **Move Explainability**: Add heatmaps for predicted scores.
- 🌐 **Web Interface**: Deploy as a web app using Streamlit or Flask.
- 🎮 **Multiplayer Mode**: Add human-vs-human or online support.

---

## 👩‍💻 Ideal For

- CS students learning **AI search algorithms**
- Developers exploring **heuristic modeling**
- Researchers benchmarking **decision-making strategies**
- Educators teaching **game theory and algorithms**

---

## 💬 Questions or Contributions?

Feel free to open an issue or submit a pull request if you'd like to contribute!  
Let’s level up the game—one move at a time. 🧠✨
