# 🐢 Turtle Racing Game

A fun and simple terminal + GUI-based racing game built with Python’s `turtle` module. You can race between 2 to 10 colorful turtles, and the first one to reach the top wins!

---

## 📂 File Structure

```
turtle-racing/
├── main.py         # Main game script
└── README.md       # Documentation
```

---

## 🚀 How to Run

### ✅ Requirements

- Python 3.x  
- No external libraries — uses the built-in `turtle`, `time`, and `random` modules

### ▶️ Run the Game

```bash
python main.py
```

---

## 🎮 How to Play

1. When the program starts, it will ask:

```
Enter the number of racers (2 - 10):
```

2. Input a number between 2 and 10.

3. The turtle window will launch with each turtle assigned a random color.

4. Turtles will race vertically upwards. The first to reach the top wins.

5. After the race, the winner will be printed in the terminal:

```
The winner is the turtle with color: red
```

---

## 📦 Game Details

- **Turtle Colors**: Randomly chosen from a list of 10 (`red`, `green`, `blue`, etc.)
- **Movement**: Each turtle moves forward by a random distance on each turn
- **Winning Condition**: First turtle to reach near the top of the screen wins

---

## 🧠 How It Works

- `get_number_of_racers()` — Prompts and validates number of racers
- `init_turtle()` — Initializes the game window using turtle screen
- `create_turtles(colors)` — Creates turtle objects, assigns colors, positions them
- `race(colors)` — Main loop where turtles move until one wins
- `main` block — Orchestrates the whole game

---

## 📄 License

This project is open-source and free to use for learning or extension purposes.

---

Enjoy racing turtles! 🐢💨
