# GameDesignBalance

🧩 Project Scope – AI Simulation & Analysis for Chkoba
🎯 Objective
Develop a system that simulates matches of Chkoba (including ability usage), and applies machine learning models to analyze performance, discover strategic patterns, and suggest balance adjustments based on player decisions, win rates, and ability counters.

📚 Project Phases & Deliverables
📌 Phase 1 – Match Simulation Engine
Goal: Create a rule-based engine to play Chkoba matches autonomously with ability triggers.

Implement:

Card representation (value, suit, effects, artifact tags).

Table & hand logic (playing, capturing, swapping, triggering abilities).

Ability handler (swap, reveal, bonus triggers).

Deliverable: Match log output with full game state history.

Tools:

Programming: Python (PyGame or custom logic), JavaScript (Node.js)

Data Structuring: Pandas, JSON, SQLite (for event storage)

📌 Phase 2 – Supervised Learning Models
Goal: Use match logs to train ML models to classify optimal plays and assess ability efficiency.

Dataset:

Input: Game state snapshot (hand, table, score, active abilities).

Label: Action taken (card played, ability triggered).

Models:

Decision Tree, Random Forest

XGBoost, LightGBM (for efficiency)

Optional: LSTM or Transformers (if treating turns as sequences)

Tools:

Python: scikit-learn, TensorFlow, PyTorch

Jupyter Notebook (for training & visualization)

📌 Phase 3 – Reinforcement & Unsupervised Learning
Goal: Let agents learn strategy by playing against themselves, and cluster player behavior types.

RL Model:

Q-learning or PPO (via Stable Baselines3)

Unsupervised Insights:

Use k-means or DBSCAN to group players by style

Metrics:

Frequency of ability use

Win/loss trends by playstyle

Tools:

Libraries: stable-baselines3, gym (for RL environment)

Clustering: scikit-learn or seaborn for visual mapping

📌 Phase 4 – Tactical Analysis & Game Balance
Goal: Analyze key gameplay data to help refine character design and abilities.

Output Insights:

Hero win rates

Most triggered abilities

Ability efficiency vs. win rate

Counter graphs (who consistently beats whom)

Bonus:

Detect unfair synergies or untriggered abilities needing a redesign

Tools:

Visualization: Matplotlib, Seaborn, Plotly Dash

Reporting: Jupyter Notebook, Excel exports, Streamlit dashboard

🧠 Optional Add-Ons
✨ AI Explainer: Build a bot that narrates why it chose each move (great for debugging).

🎮 Gameplay Replay: Frontend using JS or PyGame that visualizes matches step-by-step.

📊 Dashboard: Streamlit or Dash app to explore hero stats, counter data, win rates interactively.
