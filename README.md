# 💣 Bomberman Clone

A Bomberman-inspired game made with **Python and Pygame**. The project recreates some classic Bomberman mechanics: destructible walls, timed bombs, explosions, and an enemy with basic AI.

## 🎮 Features

- Randomly generated maps.
- Breakable and indestructible walls.
- Bombs with timed explosions.
- Explosions that spread in four directions and stop at walls.
- Enemy AI that moves around, avoids danger, and tries to attack the player.
- Collision detection.
- Main menu, pause menu, and victory and defeat screens.

## 🕹️ Controls

| Key | Action |
|---|---|
| `W` / `↑` | Move up |
| `A` / `←` | Move left |
| `S` / `↓` | Move down |
| `D` / `→` | Move right |
| `SPACE` | Place a bomb / Select menu option |
| `ESC` | Pause / Resume / Return to main menu |

## ▶️ Download and Run

### Windows executable (recommended)

You don't need to install Python or Pygame to run the game.

1. Open the repository's [Actions page](https://github.com/At-Carvalho/bomberman-clone/actions).
2. Select the latest successful **Build Windows executable** workflow run.
3. Under **Artifacts**, download `Bomberman-Windows`.
4. Extract the downloaded ZIP file.
5. Run `Bomberman.exe`.

> Windows may show a SmartScreen warning because the executable is not signed. Only run it if you downloaded it from this repository.

### Run from source

If you prefer to run the Python source code, install [Python 3](https://www.python.org/downloads/) first.

Clone the repository:

```bash
git clone https://github.com/At-Carvalho/bomberman-clone.git
cd bomberman-clone
```

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Run the game:

```bash
python main.py
```

## 📁 Project Structure

```text
bomberman-clone/
├── .github/
│   └── workflows/
│       └── build-windows.yml  # Builds the Windows executable
├── main.py                    # Main game loop and event handling
├── config.py                  # Game settings and constants
├── mapa.py                    # Map generation
├── logica.py                  # Bombs, explosions, movement, and enemy AI
├── desenho.py                 # Game rendering and menus
├── requirements.txt           # Python dependencies
└── README.md
```

## ⚙️ Configuration

Gameplay settings can be changed in `config.py`, including:

- Map dimensions and tile size.
- Breakable wall spawn rate.
- Bomb timer and explosion duration.
- Bomb range.
- Enemy decision intervals.

## About

This is a personal project I made to practice Python and learn more about game development. While building it, I worked with modular code, game loops, keyboard input, collision detection, timers, and basic enemy AI.

## License

Feel free to explore the code and use it for learning purposes.
