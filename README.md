# 🃏 Blackjack Game (Python Console Version)

This is a simple **console-based Blackjack game** built in Python. The game allows a user to play against the computer in a classic version of Blackjack with some simplified rules.

---

## 🎮 How to Play

- Each player is dealt **two cards**.
- The goal is to **get as close to 21 as possible** without going over.
- The Ace (`11`) automatically switches to `1` if your total goes over 21.
- A score of **21 with two cards** is considered **Blackjack**.

---

## 🧠 Game Features

- User and computer are dealt cards randomly.
- Dynamic score calculation (with Ace adjustment).
- Real-time decision: Hit or Pass.
- Computer plays automatically and draws until reaching 17 or higher.
- Clear win/lose/draw messages.

---

## 🗂️ File Structure

- `blackjack.py`: Main game logic.
- `art.py`: Contains ASCII logo for better UI (optional, if used).
- `README.md`: Project description and instructions.

---

## ▶️ How to Run

1. Make sure Python is installed:
   ```bash
   python --version
   ```

2. Clone the repo or download the script:
   ```bash
   git clone https://github.com/yourusername/blackjack-game.git
   cd blackjack-game
   ```

3. Run the game:
   ```bash
   python blackjack.py
   ```

---

## 📌 Requirements

- Python 3.x
- No external libraries needed (uses built-in `random` module)

---

## 📷 Screenshot

```text
Your cards: [8, 10], current score: 18
Computer's first card: 6
Type 'y' to get another card, type 'n' to pass: n

Your final hand: [8, 10], final score: 18
Computer's final hand: [6, 10, 4], final score: 20
You lose 😤
```

---

## 📁 Optional Enhancements

- Add a graphical user interface (GUI) using `tkinter` or `streamlit`.
- Implement betting and balance.
- Track high scores.
- Multiplayer mode.
- Store logs using a database.

---

## 💡 Inspiration

This project is a beginner-friendly implementation of Blackjack and was created as a part of hands-on learning in Python and logic-building.

---

## 🔗 License

MIT License

---

### 🎉 Enjoy the game & feel free to contribute!
