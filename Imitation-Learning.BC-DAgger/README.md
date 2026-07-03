# <center> **PROJECT: Imitation Learning — Behavioral Cloning & DAgger**

Implementation of two key Imitation Learning algorithms: Behavioral Cloning (BC) and Dataset Aggregation (DAgger).

---

### **Project Goal**

Learn to train agents by imitating expert behavior without direct reward signals from the environment. This approach is particularly useful when rewards are sparse or hard to define.

---

### **Implemented Algorithms**

1. **Behavioral Cloning (BC)**  
   Simple supervised learning approach: treat imitation as a regression/classification problem — predict expert actions from observed states.

2. **DAgger (Dataset Aggregation)**  
   Iterative algorithm that solves the **covariate shift** problem by actively collecting new data from the learner's policy and aggregating it with the expert dataset.

---

### **Technologies Used**

- `Gymnasium` + `dm_control` environments
- `PyTorch` (neural network policies)
- `h5py` — working with expert datasets
- `numpy`, `matplotlib`
- Custom Dataset and DataLoader for training

---

### **Key Results**

- **Behavioral Cloning** suffers from covariate shift and shows limited performance.
- **DAgger** significantly outperforms BC: after 3–5 iterations, performance improves by 20–50 points and approaches expert level.
- DAgger effectively mitigates the distribution shift problem by continuously expanding the dataset with states visited by the learner.

---

### **Project Stages**

1. Loading and exploring expert demonstration dataset
2. Implementation of Behavioral Cloning (BC)
3. Training and evaluation of BC policy
4. Implementation of DAgger algorithm
5. Iterative dataset aggregation and retraining
6. Comparison of BC vs DAgger performance
7. Visualization of agent behavior

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook
- `src/` — models, datasets, utilities
- `data/` — expert demonstrations
- `figures/` — training curves and visualizations
- `requirements.txt`

---

### **Conclusion**

This project demonstrates a deep understanding of Imitation Learning techniques. By implementing both Behavioral Cloning and its improved iterative version DAgger, I gained practical experience in training agents from expert demonstrations and solving the covariate shift problem — one of the core challenges in imitation learning.

---