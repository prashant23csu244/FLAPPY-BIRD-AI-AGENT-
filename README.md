# 🐦 Flappy Bird AI Agent

An AI-powered Flappy Bird game where an intelligent agent learns to play automatically using Machine Learning / Reinforcement Learning techniques. The agent improves its performance through training and eventually learns to navigate pipes, maximize score, and survive longer without human intervention.

---

# 📌 Project Overview

The Flappy Bird AI Agent demonstrates how Artificial Intelligence can learn and make decisions in a game environment.

## Features
- Automated Flappy Bird gameplay
- AI-based decision making
- Training and evaluation pipeline
- Performance visualization
- Model saving and loading
- Reinforcement Learning / NEAT support

---

# 🎯 Objectives

- Develop a playable Flappy Bird game
- Implement an AI agent
- Train the agent to achieve high scores
- Analyze learning performance
- Demonstrate Game AI concepts

---

# 🛠 Technologies Used

- Python
- Pygame
- NumPy
- Matplotlib
- NEAT-Python
- Pickle

---

# 📂 Project Structure

```text
FlappyBird-AI/
│
├── assets/
├── models/
├── graphs/
├── config/
├── src/
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚙️ System Requirements

## Hardware
- Intel i3 or higher
- 4 GB RAM minimum
- 500 MB free storage

## Software
- Python 3.8+
- Pygame
- NumPy
- Matplotlib
- NEAT-Python

---

# 🚀 Installation

```bash
git clone https://github.com/yourusername/flappy-bird-ai.git
cd flappy-bird-ai
pip install -r requirements.txt
```

---

# ▶️ Running the Project

## Train Agent

```bash
python train.py
```

## Test Agent

```bash
python test.py
```

## Play Game

```bash
python game.py
```

---

# 🧠 AI Agent Workflow

State:
- Bird Position
- Bird Velocity
- Distance to Pipe
- Pipe Gap Position

Actions:
- 0 = Do Nothing
- 1 = Jump

Rewards:
- Pass Pipe: +10
- Survive: +0.1
- Collision: -100

---

# 📈 Performance Metrics

- Best Score
- Average Score
- Fitness
- Survival Time
- Pipes Passed

---

# 🔍 Learning Algorithm

The project can use:
- Reinforcement Learning
- NeuroEvolution
- NEAT (NeuroEvolution of Augmenting Topologies)

---

# 🧪 Testing

```bash
python test.py
```

---

# 🔐 Future Improvements

- Deep Q Networks (DQN)
- PPO
- Double DQN
- Multi-Agent Training
- Real-Time Analytics

---

# 👨‍💻 Author

Prashant Kumar , Prateek Khatana

B.Tech CSE (AI & ML)

---

# 📄 License

MIT License

---

# ⭐ Acknowledgements

- Python Community
- Pygame Developers
- NEAT-Python Contributors
- Open Source AI Community
