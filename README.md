# 🃏 Blackjack Game (Python)

A simple command-line Blackjack game built using Python. This project simulates a classic Blackjack experience where a player competes against a dealer using standard casino rules.

---

## 📌 Overview

This project demonstrates object-oriented programming (OOP) concepts in Python by modeling a deck of cards, player hands, and game logic. It includes core Blackjack mechanics such as dealing cards, calculating hand values, and determining winners.

---

## 🎮 Features

* 🃏 Standard 52-card deck
* 🔀 Deck shuffling
* 👤 Player vs 🤖 Dealer gameplay
* ➕ Hit or Stand options
* 🧠 Automatic dealer logic (draws until 17)
* 💥 Bust detection (over 21)
* 🃏 Blackjack detection
* 🤝 Tie (push) handling
* 🎯 Multiple rounds support
* 💻 Clean and interactive command-line interface

---

## 🧱 Project Structure

```
blackjack.py
```

### Main Components:

* **Card Class**
  Represents a single playing card with suit and rank.

* **Deck Class**
  Creates and manages a full deck of 52 cards, including shuffling and dealing.

* **Hand Class**
  Stores cards for player or dealer and calculates total value (handles Ace logic).

* **Game Class**
  Controls game flow, user input, and winner determination.

---

## ⚙️ How It Works

1. The deck is created and shuffled.
2. Both player and dealer receive 2 cards.
3. Player chooses:

   * `Hit` → take another card
   * `Stand` → end turn
4. Dealer automatically draws until reaching at least 17.
5. Winner is determined based on:

   * Closest to 21
   * Blackjack (21 with 2 cards)
   * Bust (over 21)

---

## 🚀 How to Run

### Requirements

* Python 3.x

### Run the game

```bash
python blackjack.py
```

---

## 🖥️ Example Gameplay

```
==============================
🎮 Game 1 of 3
==============================

Your Hand:
  - 10 of hearts
  - 7 of clubs
👉 Value: 17

Dealer Hand:
  - 🂠 Hidden Card
  - 9 of spades

👉 Hit or Stand? (h/s):
```

---

## 📚 Concepts Used

* Object-Oriented Programming (OOP)
* Classes and Objects
* Lists and Loops
* Conditional Logic
* User Input Handling
* Randomization

---

## 🔧 Future Improvements

* 🔁 Replay without restarting the program
* 🎨 Graphical User Interface (GUI)
* 🌐 Web-based version
* 🤖 Advanced dealer strategy

---

## 👨‍💻 Author

Created by **Aria**
Beginner AI Developer

---

## ⭐ Contributing

Contributions, suggestions, and improvements are welcome!
Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.
