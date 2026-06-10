# Asteroids

A classic Asteroids arcade game built with Python and Pygame.

## Gameplay

Pilot a spaceship and survive as long as possible by shooting down asteroids before they collide with you. Large asteroids split into smaller ones when shot.

## Features

- Player-controlled spaceship with rotation and thrust
- Asteroids that split into smaller fragments when shot
- Shooting cooldown to prevent spamming
- Game-over on player–asteroid collision

## Controls

| Key | Action |
|-----|--------|
| `W` | Move forward |
| `S` | Move backward |
| `A` | Rotate left |
| `D` | Rotate right |
| `Space` | Shoot |

## Requirements

- Python 3.13+
- [uv](https://github.com/astral-sh/uv) (recommended) or pip

## Setup & Running

### With uv (recommended)

```bash
uv sync
uv run python main.py
```

### With pip

```bash
pip install pygame==2.6.1
python main.py
```
