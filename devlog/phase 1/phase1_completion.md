## 🏠 Civilizism Phase 1 Prototype: Agents in a World

We’ve moved from abstract minds to embodied beings.
**Agents now live in a shared environment, explore objects, build beliefs, and reflect on their experiences.**

### 🧩 What’s New in Phase 1:

* ✅ Multi-agent simulation with environmental awareness
* ✅ Object and room interaction logic (agents can sit, wander, explore)
* ✅ Spatial memory formation (`known_map`, `known_objects`)
* ✅ Memory system with emotional tags, semantic embeddings, and reflection
* ✅ Personality traits influencing behavior and value formation
* ✅ Goal construction and belief evolution based on daily life
* ✅ Streamlit UI for structured simulation viewing

---

### 🧠 Agents Now Have:

* Belief systems (with net\_importance tracking)
* Memory banks (emotion-tagged experiences)
* Internal summaries and personality profiles
* Social awareness of other agents
* Reflection mechanics (what happened, and what it meant)

They are, in short, *living digital citizens*—not just talkers, but thinkers and doers.

---

### 🧪 Sample Observations:

* Agents develop opposing top beliefs like “conflict” vs “protection”
* One agent may hoard chairs; another just walks in circles philosophizing
* Memory emotion tags affect goal-making (and venting, often)
* Interaction with objects (e.g., sofas) leads to tangible memory entries
* Social memory tracks presence, even without active dialogue

It’s like watching a bunch of self-absorbed philosophers move into IKEA.

---

### 📦 Simulation Output:

* A full **`run_phase1_trial()`** generates agent info for post-analysis
* Outputs include belief rankings, goal traces, memory lists, personality embeddings
* Easily exportable for future phase testing, UI visualization, and meta-analysis

Streamlit UI lets you drop in, pick an agent, and spy on their thoughts guilt-free.

---

### 🧱 Core Modules Built:

* `agent_core`: The brain and body loop
* `memory_manager`: Stores, clusters, and updates emotional memory
* `perception.py`: Updates environmental knowledge per tick
* `environment.py`: Houses rooms, objects, and their interaction logic
* `system.py`: Runs the full tick-based engine, returns structured output

---

### 🔭 What’s Next (Phase 2 Prep):

* Add visible belief tension (conflicting agents start avoiding each other)
* Timeline viewer: Track belief evolution over ticks
* Belief inheritance and multi-day simulation
* UI upgrades: memory graphs, room heatmaps, agent comparison
* And of course… let them fight. (Conflict resolution loop coming soon)

---

### 📸 Screenshot:

![Streamlit Phase 1](https://github.com/timchensuper999/Civilizism/blob/main/devlog/phase_1_streamlit_ui.png?raw=true)

> *“They live. They walk. They reflect. And they’re weirdly obsessed with chairs.”*
