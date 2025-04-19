# Civilizism

**Civilizism** is an agent-based cognitive simulation platform that models belief formation, reflection, emotional feedback, and society-scale dynamics.

Unlike traditional behavior simulators, Civilizism is built on the premise that:
- **Agents possess memory, beliefs, goals, and conflicting internal states**
- **Actions are chosen via internal reflection, not predefined rules**
- **Social interactions evolve based on belief diffusion, emotional resonance, and emergent identity**

This project is being developed solo by [Tim Chen](https://www.linkedin.com/in/tim-chen-303276329/), an undergraduate at UCLA, with the goal of creating a fully traceable, modular civilization simulator designed for education, experimentation, and (eventually) commercial deployment.

---

## Key Features (Planned)

### 🧠 Agent Engine
- Memory storage, reflection, decay, and reinforcement
- Belief evolution and generational inheritance
- Emotion-influenced planning and goal weighting
- Personality growth via internal tuning

### 🌍 Environment
- Physical map with interactable objects
- Resource pressure index and environmental dynamics
- Global events and location-specific variation

### 🛠️ System Layer
- Technology development and systemic events
- Customization and initial seeding
- Memory cleaning and event tracking
- Global summary stats and belief heatmaps

### 🧩 Display & Input
- Agent info interface and social connection graph
- Belief state visualization and timeline tracing
- Command line control and future UI integration

---

## Development Roadmap (v3.0 Timeline)

| Phase | Target Completion | Description |
|-------|--------------------|-------------|
| **Phase 0** | Apr 27, 2025 | 2 agents + 1 object interaction test (memory + reflection MVP)  
| **Phase 1** | Jun 29, 2025 | 4 agents + house object + base personality and memory UI  
| **Phase 2** | Sep 7, 2025 | 20 agents + belief conflict + macro map + heatmap and stat displays  
| **Phase 3** | Nov 30, 2025 | Multigenerational agents, belief inheritance, technology layer  
| **Phase 4** | Feb 15, 2026 | Commercial beta: UI/UX polish, export tools, player interaction

Full architecture and module timeline:  
→ [`docs/modules_by_phase.md`](https://github.com/timchensuper999/Civilizism/blob/main/docs/modules_by_phase.md)

---

## Project Philosophy

Civilizism was born out of a simple question:  
> *“Can we simulate a society not just by what people do, but by how they think?”*

Rather than optimizing for behavior patterns or economic metrics, Civilizism models the **internal architecture of thought**—beliefs that conflict, reflections that change us, and decisions made under uncertainty.

Agents are not bots. They are **cognitive mirrors**—each capable of growth, contradiction, and transformation.

---

## Project Structure

```text
Civilizism/
├── /docs           # System design notes, module breakdowns
├── /log            # Weekly devlog for traceable progress
├── /src            # Core simulation engine (in progress)
├── README.md       # You're here
├── LICENSE         # MIT license
└── .gitignore
```


---

## Status

Currently in **Phase 0** development. First MVP interactions underway.

Follow updates via `log/` or on [Notion overview page](https://www.notion.so/Civilizism-Simulating-Society-through-Thought-Not-Rules-1dab7e9fbfd380829809c703941ca81c?pvs=4).

---

## Licensing

Civilizism is open-sourced under the MIT License.  
Feel free to explore, cite, or contribute with proper credit.

---

## Contact

Built and maintained by Tim Chen  
[LinkedIn](https://www.linkedin.com/in/tim-chen-303276329/) | [GitHub](https://github.com/timchensuper999)


