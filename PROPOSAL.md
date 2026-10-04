# Quantum Break-in
**Author:** Nestors Starostins, ns23044

## Concept
This is a puzzle game where the player tries to hack into a quantum-protected system by typing the correct bit password.
The player sees a grid of qubits and as a step can apply gates to one (H, X, Z, ...) or multiple adjacent ones (CNOT, ...)
in order to achieve the target configuration with a 100% probability in a limited amount of steps or as few steps as possible.
The task is further made more difficult by having sentinels that measure certain qubits at certain step intervals.
If they measure 0, the qubit simply collapses to that state, which may influence other qubits as well because of entanglement.
Else the sentinel detects the player, which results in game over.
The game is divided into levels, which have different target passwords, grids, allowed gate sets, step limits etc.

The game covers all the main concepts of an introductory Quantum Computing course, including superposition, entanglement, measurement, gates and states.
In theory, it could further be extended to cover some aspects of real physical quantum computers, like the amplitudes "fading" back to 0 over time.

As far as my research went, no similar games exist. Quantum mechanics are at the core of the game, so it's hard to define what a similar non-quantum game would be,
but the concept was born from the idea of "cheating" or "escape" games where you try to do something while avoiding the guards.

## Development
I would like to attempt making the game in Godot in order to learn the engine.
But, if it doesn't work out, the fallback option is Pygame.
