# Riftbound Lab

Unified research and engineering ecosystem for **Riftbound TCG** simulation, autonomous gameplay agents (LLM via MCP & Reinforcement Learning), and co-evolutionary deck building.

## Repositories

| Repository | Role | Description |
| :--- | :--- | :--- |
| **[iftbound-engine](https://github.com/riftbound-lab/riftbound-engine)** | **Simulator & Ground Truth** | Deterministic rules engine, Gymnasium environment (RiftboundEnv), FastAPI REST server, Rift Table web UI, and MCP server (iftbound-mcp). |
| **[iftbound-agents](https://github.com/riftbound-lab/riftbound-agents)** | **Gameplay Agents (Pilots)** | Autonomous agents that play matches via MCP (LLMs) or Gymnasium (RL / MCTS), plus the Arena match runner. |
| **[l-deck-builder](https://github.com/riftbound-lab/rl-deck-builder)** | **Deck Architect & Meta** | Contrastive card embeddings, Set Transformer deck encoders, and co-evolutionary deck optimization. |