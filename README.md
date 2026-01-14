
---

# 🐦 Flappy Bird Game – Python & Pygame

## 📌 Project Overview

This project is a fully functional **Flappy Bird game clone** built using **Python and the Pygame library**. The game recreates the popular Flappy Bird mechanics where the player controls a bird and must navigate it through moving pipes without colliding. The game includes animations, sound effects, score tracking, and collision detection, providing a complete gaming experience.

This project demonstrates how Python can be used to develop **2D arcade-style games** with real-time graphics, physics simulation, and interactive gameplay.

---

## 🎯 Project Objective

The main goal of this project is to design a **playable 2D game** that helps understand:

* Game loops
* Event handling
* Sprite animation
* Physics (gravity & velocity)
* Collision detection
* Score tracking

This project is ideal for learning **game development fundamentals using Python**.

---

## 🛠 Technologies Used

* **Python 3**
* **Pygame Library**
* **Game assets (sprites, sounds, background)**

---

## 📂 Project Structure

```
Flappy-Bird-Game
│
├── 4. flappy bird.py
├── gallery/
│   ├── sprites/
│   └── audio/
└── README.md
```

---

## 🕹 Game Features

* Smooth bird movement and gravity
* Randomly generated pipes
* Collision detection with pipes and ground
* Score counting system
* Sound effects (wing, hit, point, die)
* Welcome screen
* Game over and restart
* Background and animated sprites

---

## ⚙ How the Game Works

1. When the game starts, the **welcome screen** is displayed.
2. Pressing the **space bar or up arrow** begins the game.
3. The bird moves downward due to gravity.
4. Each key press makes the bird **flap upward**.
5. Pipes move from right to left across the screen.
6. The player must pass through the gap between pipes.
7. Every successful pass increases the score.
8. If the bird hits a pipe or the ground, the game ends.

---

## 🧠 Game Logic

### Bird Movement

The bird’s vertical movement is controlled by gravity and flapping velocity. Gravity pulls the bird downward, while pressing a key applies upward force.

### Pipe Generation

Pipes are generated randomly using:

```python
getRandomPipe()
```

This creates unpredictable gaps, making the game challenging.

### Collision Detection

The function `isCollide()` checks:

* Bird hitting pipes
* Bird touching the ground
* Bird going out of bounds

If a collision occurs, the game ends.

### Score System

When the bird passes the center of a pipe, the score increases by 1 and a sound effect plays.

---

## 🔊 Sound Effects

The game includes multiple sounds:

* Wing flap
* Point earned
* Collision
* Death

These make the gameplay more engaging and realistic.

---

## ▶ How to Run the Game

1. Install pygame:

```
pip install pygame
```

2. Make sure all files (gallery folder and python file) are in the same directory.

3. Run:

```
python "4. flappy bird.py"
```

---

## 🎓 Skills Demonstrated

* Python programming
* Game development
* Pygame framework
* Physics and motion
* Event handling
* Collision detection
* UI & UX design for games

---

## 🔮 Future Improvements

* High score saving
* Mobile version
* Difficulty levels
* Power-ups
* Multiplayer mode

---

## 📌 Conclusion

This Flappy Bird project shows how Python and Pygame can be used to create **real-time interactive games**. It reflects strong understanding of **game logic, animation, physics, and user interaction**, making it a great addition to any **programming or game development portfolio**.
<img width="800" height="533" alt="image" src="https://github.com/user-attachments/assets/643bd4a7-30fd-4e95-989c-7086348af223" />

---
