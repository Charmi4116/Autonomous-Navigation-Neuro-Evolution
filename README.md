# Autonomous Navigation via Neuro-Evolutionary Algorithms

An AI-based autonomous navigation system where agents learn to navigate complex and dynamic environments using **neuro-evolution**, without relying on human-labelled datasets or hand-crafted navigation rules. The system evolves intelligent behaviour over generations through a combination of neural networks and genetic algorithms.

## 🚀 Project Highlights

* Custom-built **feedforward neural network** implemented from scratch (no ML libraries for core logic)
* 5 directional **ray-cast sensors** for real-time obstacle detection and environment awareness
* **Genetic Algorithm (GA)** used to evolve agent behaviour across generations
* Fitness-based selection, crossover, and mutation for continuous performance improvement
* Real-time visualization of **agent movement and neural decision-making**
* Persistent storage of best-performing models using **SQLite database**
* Fully simulation-driven learning with no external training data required

## 🧠 How It Works

* Each agent is controlled by a neural network
* Inputs come from ray-cast sensors detecting nearby obstacles
* The network outputs movement decisions (forward, left, right, etc.)
* Agents are evaluated using a **fitness function** based on survival time and distance traveled
* The best-performing agents are selected to produce the next generation
* Over time, navigation strategies evolve automatically

## 📊 Results

* **50+** agents per generation simulated in parallel
* **30+** evolution generations completed
* **78%** reduction in collision rate over time
* **12×** improvement in overall fitness score
* Emergent behaviour observed: smoother navigation paths and obstacle avoidance strategies

## 🛠️ Tech Stack

**Python · NumPy · Neural Networks · Genetic Algorithms · SQLite · Pygame (Simulation Visualization)**

## 📄 Conference Poster

[View Conference Poster](poster/Autonomous-Navigation-Conference-Poster.pdf)

## 👩‍💻 Authors

**Charmi Shah · Salomi Kureshi**
Guide: **Vishal Acharya**

> *“Teaching machines to drive through survival of the fittest — no rules, no teacher, just evolution.”*
