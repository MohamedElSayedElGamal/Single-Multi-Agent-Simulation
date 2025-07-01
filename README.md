# Single & Multi-Agent Simulation

This project explores agent-based modeling by comparing **single-agent** and **multi-agent** systems in a simulated environment. The aim is to analyze behavioral differences, task efficiency, and reward outcomes over multiple episodes using real simulation data.

---

## 🧠 Project Overview

The notebook implements a grid-based simulation environment in which agents move to maximize rewards over time. It supports both:

- **Single-agent mode:** one agent operating alone
- **Multi-agent mode:** multiple agents acting simultaneously

Key objectives include:
- Comparing cumulative rewards
- Evaluating agent performance trends over episodes
- Understanding coordination and conflict among agents

---

## 📂 Included Datasets

### 📊 `single_agent_results.csv`
- **Columns:** `Episode`, `Total Reward`
- Contains reward data per episode for a single agent.

### 📊 `multi_agent_results.csv`
- **Columns:** `Episode`, `Agent ID`, `Total Reward`
- Tracks the reward of each agent in a multi-agent setup over multiple episodes.

These CSV files are used within the notebook for visual analysis and comparison between single and multi-agent performance.

---

## 📓 Notebook Overview

### `Single & Multi-Agent Simulation.ipynb`

This notebook is divided into the following main sections:

1. **Environment Setup**
   - Libraries imported
   - Data loading from CSV files
   - Plotting configurations

2. **Data Exploration**
   - Preview of datasets
   - Summary statistics

3. **Visualization**
   - Line plots showing total rewards per episode
   - Comparison of single vs. multi-agent performance
   - Boxplots or histograms (if implemented)

4. **Insights**
   - Performance differences across agents and strategies
   - Effect of episode count on reward accumulation
   - Behavioral patterns in agent coordination
