# <center> **PROJECT: Deep Q-Network (DQN) Implementation**

Implementation of the classic Deep Q-Network algorithm with experience replay and target network. Comparison with tabular Q-Learning on CartPole and Atari environments.

---

<div align="center">
  <img src="image/ChatGPT Image 12 июня 2026 г., 21_58_05.png" width="100%" alt="Deep Q-Network Project">
</div>

---

### **Project Goal**

Implement and test one of the most influential deep reinforcement learning algorithms — **Deep Q-Network (DQN)** — and evaluate its performance against traditional tabular Q-Learning.

---

### **Project Structure**

**Part 1: Debugging (CartPole)**
- Simple environment for quick algorithm validation
- Fast training cycle (~few minutes)

**Part 2: Main Task (Atari)**
- More complex visual environment
- Full-scale DQN training

---

### **Key Components Implemented**

- Experience Replay Buffer
- Target Network (for training stability)
- Epsilon-greedy exploration strategy
- Deep Q-Network architecture
- Training loop with loss calculation
- Evaluation and visualization of agent performance

---

### **Technologies Used**

- `PyTorch`
- `Gymnasium` (CartPole + Atari)
- `numpy`, `matplotlib`
- Experience Replay implementation from scratch
- Target Network stabilization

---

### **Project Stages**

1. Environment setup (CartPole and Atari)
2. Tabular Q-Learning baseline implementation
3. Deep Q-Network architecture development
4. Experience Replay and Target Network implementation
5. Training and hyperparameter tuning
6. Comparison and analysis of results

---

### **Conclusion**

This project demonstrates a solid implementation of the groundbreaking Deep Q-Network algorithm. Successfully training DQN on both simple (CartPole) and complex visual environments (Atari) highlights deep understanding of modern reinforcement learning techniques, including stabilization methods like experience replay and target networks.

---

### **Project Structure**

- `notebooks/` — main training notebooks (CartPole + Atari)
- `src/` — custom DQN agent, replay buffer, utilities
- `figures/` — training curves, agent gameplay visualization
- `requirements.txt`

---

### **How to run**

```bash
cd Deep-Q-Network-DQN

pip install -r requirements.txt

# Debugging version (fast)
jupyter notebook "PROJECT - DQN - CartPole.ipynb"

# Main version (Atari)
jupyter notebook "PROJECT - DQN - Atari.ipynb"