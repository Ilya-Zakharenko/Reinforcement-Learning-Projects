# <center> **PROJECT: Classic RL Algorithms**  

Value Iteration & Policy Iteration on Grid World and Frozen Lake

Implementation and comparison of two fundamental Reinforcement Learning algorithms: Value Iteration and Policy Iteration.

---

### **Project Goal**

Implement and compare classic tabular Reinforcement Learning methods on standard environments (Grid World and Frozen Lake) to understand their convergence, strengths, and limitations in deterministic and stochastic settings.

---

### **Environments**

- **Grid World** — Simple grid environment with start (S), goal (G), and holes (H)
- **Frozen Lake** — Deterministic and stochastic versions (`FrozenLake-v1`)

---

### **Implemented Algorithms**

1. **Value Iteration**
   - Iterative method for finding optimal value function
   - Used on Grid World environment

2. **Policy Iteration**
   - Alternating Policy Evaluation and Policy Improvement
   - Applied to both deterministic and stochastic Frozen Lake

---

### **Key Results**

- Both algorithms successfully converge to the optimal policy.
- In the stochastic Frozen Lake environment, Policy Iteration remains stable despite randomness.
- Statistical analysis (100 runs) confirmed robustness of the solution.

---

### **Technologies Used**

- `Python`
- `Gymnasium` (OpenAI Gym)
- `numpy`
- Custom implementations of Value Iteration and Policy Iteration

---

### **Project Stages**

1. Environment setup and understanding
2. Implementation of Value Iteration
3. Implementation of Policy Iteration (deterministic)
4. Testing on stochastic environment
5. Statistical validation and analysis
6. Conclusions

---

### **Conclusion**

This project demonstrates a solid understanding of foundational Reinforcement Learning algorithms. Successfully implementing Value Iteration and Policy Iteration on both deterministic and stochastic environments provides strong intuition about how tabular RL methods work and their practical limitations.

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook
- `src/` — algorithm implementations
- `figures/` — visualizations of policies and value functions
- `requirements.txt`

---

### **How to run**

```bash
cd RL.Classic-Algorithms.GridWorld-FrozenLake

pip install -r requirements.txt

jupyter notebook "PROJECT - Reinforcement Learning. Value Iteration and Policy Iteration.ipynb"