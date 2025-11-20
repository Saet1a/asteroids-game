# Asteroids

A Python implementation of the classic arcade game "Asteroids,". This project demonstrates object-oriented game design, vector mathematics, and real-time collision handling using the Pygame engine.

## Features

* **Player Movement:** Physics-based spaceship controls including rotation and acceleration.
* **Shooting Mechanics:** Projectile system with cooldown timers.
* **Asteroid Logic:**
    * Randomized spawning at the screen edges.
    * **Splitting Mechanic:** Large asteroids split into two smaller, faster asteroids when hit.
    * Varied asteroid sizes and movement vectors.
* **Collision Detection:** Precise collision handling using circular hitboxes (`circleshape.py`).
* **Game Loop:** Standardized update and draw loops handling delta time for frame-rate independence.

## Requirements

* **Python**: 3.13+
* **Pygame**: 2.6.1

## Installation

This project uses `uv` for dependency management, but it can also be run with standard `pip`.

### Option 1: Using uv (Recommended)
If you have `uv` installed:
```bash
uv sync
