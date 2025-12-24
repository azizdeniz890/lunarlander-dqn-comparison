# **Deep Reinforcement Learning Analysis with LunarLander-v3**

This project provides a comprehensive experimental analysis of **value-based deep reinforcement learning algorithms** applied to the **LunarLander-v3** environment from Gymnasium.  
The primary goal is to compare different Deep Q-Learning variants under identical conditions and analyze their **learning stability, convergence behavior, and performance characteristics**.

The study focuses on the following algorithms:
- **Deep Q-Network (DQN)**
- **Double Deep Q-Network (DDQN)**
- **Dueling Deep Q-Network (Dueling DQN)**

All models are trained from scratch, evaluated using standardized metrics, and analyzed through reward curves, loss dynamics, and qualitative gameplay rollouts.

---

## **Project Structure**

```text
├── LunarLander_Models/
│   ├── dqn_model.py
│   ├── ddqn_model.py
│   └── dueling_dqn_model.py
│
├── assets/
│   ├── training_base.png
│   ├── training_ddqn.png
│   ├── training_dueling.png
│   ├── training_dueling_final.png
│   ├── arcdqn_dueling.png
│   ├── arcv2.png
│   ├── dqn.mp4
│   ├── ddqn.mp4
│   └── DUELING INIŞ BEST.mp4
│
├── notebook/
│   └── experiments.ipynb
│
├── report/
│   └── project_report.pdf
│
└── main.py

