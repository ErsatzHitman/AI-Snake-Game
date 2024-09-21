# 🐍 Snake Game AI with Reinforcement Learning 🎮🤖

This project demonstrates how to build an **AI agent** that learns to play the classic **Snake** game using **reinforcement learning**. The AI is trained using **Deep Q-Learning**, a value-based method, and utilizes neural networks for decision-making. 

The environment is built with **Pygame** for the game interface and **PyTorch** for the neural network implementation.

---

## 🚀 **Project Overview**

- **🤖 Agent**: The AI learns by interacting with the Snake environment, receiving rewards for positive actions (eating food) and penalties for negative actions (hitting walls or itself).
- **📈 Reinforcement Learning**: The project uses **Q-learning** to train the agent, where the model estimates future rewards for taking actions in given states.
- **🧠 Neural Network**: The model consists of a simple feed-forward neural network to approximate the Q-values for each possible action.
- **📊 Performance Visualization**: Real-time plotting is done using **Matplotlib** to display the agent's learning progress over time.

---

## 🛠 **Technologies Used**

- **🐍 Python**: Primary language for implementing the game and AI.
- **🎮 Pygame**: To create the Snake game environment and manage rendering, user input, and frame updates.
- **🔥 PyTorch**: To build and train the neural network using deep reinforcement learning techniques.
- **📊 Numpy**: For efficient numerical computations and matrix manipulations.
- **📈 Matplotlib**: For real-time plotting and visualization of the agent's performance (score tracking).

---

## 🚀 **How to Run the Project**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ErsatzHitman/AI-Snake-Game.git
    ```
   
2. **Install Dependencies**: 
Make sure you have Python installed. Install the required dependencies using `pip`:

```bash
pip install -r requirements.txt
 ```

3. **Train the AI Agent**: 
To start training the Snake AI, simply run the following command in your terminal:

```bash
python agent.py
 ```

4. **Play the Game Yourself**: 
If you want to play the Snake game manually, run the following command:

```bash
python snake_game_human.py
 ```


## 📁 **Files Overview**

- **`agent.py`**: Contains the core logic for the AI agent and reinforcement learning training loop.
- **`game.py`**: Implements the Snake game environment for the AI.
- **`helper.py`**: Handles the real-time plotting for performance visualization.
- **`model.py`**: Defines the neural network model and training logic using PyTorch.
- **`snake_game_human.py`**: Allows a human player to manually play the game.

---

