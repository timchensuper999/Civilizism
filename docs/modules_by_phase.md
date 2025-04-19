# Civilizism — Modules by Phase (v3.0 Timeline)

This document outlines the full modular architecture of Civilizism, organized by development phase. Each module contributes to simulating agents with memory, belief, reflection, and emergent behavior in a dynamic society.

---

## Phase 0 — Minimum Viable Simulation  
**Goal:** Simulate the cognitive loop of 2 agents interacting with a single object

**Modules:**
- **Storage** — Stores agent memory entries for experiences and observations
- **Perceiving** — Encodes environmental or social input into memory entries
- **Retrieving** — Allows agents to recall relevant past experiences
- **Reflecting** — Internal self-evaluation triggered by memory recall or CTS
- **Planning** — Chooses next action based on goals and reflection outcome
- **Physical Map** — Minimal spatial system for agent movement and object interaction
- **Time/Replay** — Basic simulation clock and timeline tracking

---

## Phase 1 — Prototype with Core Cognition (4 Agents + Small Map)  
**Goal:** Build foundational diversity in agent state, interaction, and environment

**Modules:**
- **Clustering** — Organizes similar memories into thematic or emotional groups
- **Social Memory** — Stores and updates agent-specific relationship/emotion data
- **Emotion State** — Tracks short-term emotional response affecting decisions
- **Agent Interaction** — Enables agents to perceive and react to one another
- **Object Interaction** — Agents interact with objects and store consequences
- **Map Object Algorithm** — Determines object state changes and environmental rules
- **Periodic Map Cleaning** — Resets or decays inactive objects or clutter
- **Periodic Memory Cleaning** — Removes or decays irrelevant or old memories
- **Activity Log** — Logs key events for replay or timeline display
- **Agent Info** — Structure for real-time agent state readout
- **Preliminary UI** — Command line or basic display for inspecting agents

---

## Phase 2 — MVP: 20-Agent Society with Visible Social Dynamics  
**Goal:** Enable emergent social behavior, belief propagation, and macro pattern output

**Modules:**
- **Reflection Trigger** — Defines when an agent enters a reflection state
- **Belief Making** — Forms new beliefs via memory + reflection synthesis
- **Summary Statistics** — Tracks overall belief trends, reflection frequency, etc.
- **Key Events** — Highlights events with strong agent-wide impact
- **Heatmap** — Visualizes regional or social belief/CTS/emotion states
- **Timeline** — Displays belief/emotion changes over time per agent or group
- **Agent Social Connection Map** — Network graph of trust, tension, and affinity
- **Summary Playback** — Compact replay of simulation arc and belief changes
- **Basic UI** — Expanded display of agents, stats, and maps

---

## Phase 3 — Pre-Beta: Multigen, Belief Evolution, Tech & Pressure  
**Goal:** Add cross-generational evolution, agent identity growth, and internal control

**Modules:**
- **Recency Decay / Rebound** — Adjusts memory impact based on time + salience
- **Coefficient Tuning** — Dynamically adjusts agent personality via reflection
- **Belief Inheritance** — Agents pass baseline belief system or weights to successors
- **Initial Customization (Seeding)** — Controls for environment and agent presets
- **Key Agents** — Spotlight individuals with outlier beliefs, influence, or trajectories
- **System Control** — Admin-like system toggle for sim speed, pause, etc.
- **Command Input** — Inject events, variables, or tweaks during simulation

---

## Phase 4+ — Beta & Beyond: Full UI, Player Control, Academic Use  
**Goal:** Polish interface, enable user input, and finalize features for public release

**Modules:**
- **Profession** — Role-based behavior shaping agent goals and reflection patterns
- **Resource Pressure Index** — Systemic stressor tied to environment + decision-making
- **Global Events** — Inject world-level disruptions (famine, ideology, disaster)
- **Technology** — Cultural or utility innovation emerging from belief convergence
- **All/Advanced UI** — Final simulation interface with full control and display layers

---

This file reflects the **v3.0 module timeline** as of April 2025. Module names and dependencies may evolve with development.
