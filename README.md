# NeuroPit
NeuroPit is a local AI-agent game arena written primarily in Go.

The initial experiment connects two simulated fly-brain agents to a Pong-style environment and lets them compete against each other.

The project should support multiple interchangeable agents so the same environment can later be used to compare:

- Fly Brain vs Fly Brain
- Fly Brain vs Rule-Based Agent
- Fly Brain vs Random Agent
- Fly Brain vs Jev
- Jev vs Jev
- Human vs Fly Brain
- Other future agents

Jev can additionally operate as an AI difficulty director that modifies environmental difficulty without directly controlling either player.

The entire project should be runnable and testable locally on an Apple Silicon Mac, initially targeting Mac M1.