# <center> **PROJECT: LunarLander with PPO, A2C and Reward Shaping**

Comparative study of reinforcement learning algorithms (PPO and A2C) on the LunarLander-v2 environment with custom reward shaping.

---

### **Project Goal**

Train and compare two popular on-policy RL algorithms — **PPO** and **A2C** — on the LunarLander environment. Investigate the effect of reward shaping (fuel consumption penalty) on learning efficiency, landing quality, and final performance.

---

### **Environment**

- **Gymnasium Environment**: `LunarLander-v2`
- **Objective**: Safely land the lunar module on the landing pad
- **Challenges**: Limited fuel, unstable physics, need for precise control

---

### **Experiments**

1. **Baseline Comparison**: PPO vs A2C (standard reward)
2. **Reward Shaping**: Added penalty for fuel usage to encourage more efficient landings
3. **Analysis**: Training stability, final performance, fuel efficiency, and landing success rate

---

### **Technologies Used**

- `Gymnasium`
- `Stable-Baselines3` (PPO, A2C)
- `PyTorch`
- `matplotlib` — training curves and visualizations
- `imageio` — agent behavior recording
- Custom `RewardWrapper` for fuel penalty

---

### **Key Results**

- **PPO** significantly outperformed **A2C** in both stability and final score.
- Adding **fuel consumption penalty** improved landing efficiency, though it slightly increased training time.
- A2C showed poor convergence and high variance.
- PPO demonstrated robust learning and better sample efficiency.

---

### **Project Stages**

1. Environment setup and baseline training
2. Implementation of custom reward shaping
3. Training PPO and A2C agents with different configurations
4. Comparative analysis of learning curves
5. Agent behavior visualization and video recording
6. Final evaluation and conclusions

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with experiments
- `src/` — custom wrappers, utilities, evaluation scripts
- `models/` — saved trained agents
- `videos/` — recorded agent episodes
- `figures/` — training plots and analysis
- `requirements.txt`

---

### **Conclusion**

This project demonstrates practical application of modern RL algorithms (PPO and A2C) and the importance of reward design. Through controlled experiments and reward shaping, I explored how small modifications in the reward function can significantly impact agent behavior and performance.

---