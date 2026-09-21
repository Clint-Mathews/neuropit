# Primary

- Can a simulated fly-brain network control a simple game using encoded sensory information?
- Can two independent fly-brain instances compete against each other?

# Secondary

- Can agents develop measurably different behavior under identical conditions?
- How does a fly-brain agent compare against deterministic and probabilistic agents?
- Can Jev dynamically adjust game difficulty using game telemetry?
- How does performance change as sensory information becomes incomplete or noisy?

# Core Game

The first environment will be Pong.
The game engine must implement:

- Two paddles
- Ball
- Collision detection
- Paddle movement
- Ball movement
- Scoring
- Game reset
- Match termination
- Deterministic simulation
- Configurable tick rate

Game physics MUST NOT depend on wall-clock time when running headless.

Given the same:

- seed
- configuration
- agent actions

the simulation should produce the same result.