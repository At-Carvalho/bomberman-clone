# 💣 Bomberman Clone

A Bomberman-inspired game built with **Python and Pygame**.

The idea was to recreate some of the classic Bomberman mechanics, including destructible walls, timed bombs, explosions, and an enemy with basic AI.

## 🎮 Features

- Randomly generated maps.
- Breakable and indestructible walls.
- Bombs with timed explosions.
- Explosions that spread in four directions.
- Enemy AI with basic movement, attack, and escape behaviors.
- Collision detection.
- Main menu, pause menu, and separate victory and defeat screens.

## 🕹️ Controls

| Key | Action |
|---|---|
| `W` / `↑` | Move up |
| `A` / `←` | Move left |
| `S` / `↓` | Move down |
| `D` / `→` | Move right |
| `SPACE` | Place a bomb / Select menu option |
| `ESC` | Pause / Resume / Return to main menu |

## 🛠️ Technologies

- Python 3
- Pygame

## 📁 Project Structure

The project is divided into five Python files to keep the code organized.

```text
bomberman-clone/
│
├── main.py       # Main game loop and event handling
├── config.py     # Game settings and constants
├── mapa.py       # Map generation and movement validation
├── logica.py     # Bombs, explosions, and enemy AI
├── desenho.py    # Game rendering and menus
│
└── README.md
```

## 🚀 Getting Started

### 1. Install Python 3

If you don't have Python installed, download it from the official website:

[https://www.python.org/downloads/](https://www.python.org/downloads/)

Follow the installation instructions for your operating system.

**Windows users:** Make sure to check the *"Add Python to PATH"* option during installation.

### 2. Clone the Repository

```bash
git clone https://github.com/At-Carvalho/bomberman-clone.git
```

### 3. Navigate to the project folder:

```bash
cd bomberman-clone
```

### 4. Install Pygame

```bash
pip install pygame
```

### 5. Run the Game

```bash
python main.py
```

## ⚙️ Configuration

You can change some game settings in `config.py`, such as:

- Map dimensions and tile size.
- Breakable wall spawn rate.
- Bomb timer and explosion duration.
- Bomb explosion range.
- Enemy decision intervals.

## 📚 About

This is a personal project developed to practice Python and learn more about game development.

It was also an opportunity to work with modular code, game loops, event handling, collision detection, and basic enemy AI.

## 📄 License

Feel free to explore the code and use it for learning purposes.
