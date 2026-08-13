# 🎴 Memory Card Game

A fun and interactive **Memory Card Matching Game** built using **HTML, CSS, and JavaScript**.
Test your memory, find all matching pairs, and try to complete the game in the fewest moves! 🧠🔥

---

## 🎮 Live Preview

> 🕹️ **Play the Memory Game and challenge your memory!**

**Game Type:** Browser-based Memory Card Game
**Players:** 1 Player
**Difficulty:** Easy / Fun
**Cards:** 16 Cards – 8 Matching Pairs

---

## ✨ Features

* 🎴 **16 interactive cards**
* 🍎 **8 different emoji pairs**
* 🔄 **Card flip animation**
* 🎯 **Move counter**
* ✅ **Automatic pair matching**
* ❌ **Wrong-pair detection**
* 🏆 **Win detection**
* 🎉 **Winning animation**
* 🔄 **New Game / Reset button**
* 📱 **Responsive design**
* 🌈 **Modern gradient UI**
* ⚡ **Pure JavaScript gameplay**
* 🚫 **No database required**

---

## 🛠️ Technologies Used

| Technology   | Purpose                                 |
| ------------ | --------------------------------------- |
| 🌐 HTML5     | Game structure                          |
| 🎨 CSS3      | Styling, animations & responsive design |
| ⚡ JavaScript | Game logic & interactions               |
| 😀 Emoji     | Card symbols                            |

---

## 🧠 How to Play

1. Click on any card to reveal it.
2. Click on another card.
3. If both cards match, the pair stays revealed.
4. If they don't match, the cards flip back.
5. Continue until you find all **8 pairs**.
6. Try to win using the **fewest possible moves**! 🎯

---

## 🎯 Game Logic

The game creates **8 pairs of cards**, shuffles them randomly, and displays them on a 4 × 4 grid.

When two cards are selected:

```text
Two Cards Selected
        ↓
   Compare Cards
      ↙      ↘
   Match    No Match
     ↓          ↓
 Keep Open   Flip Back
     ↓
 Check Win
     ↓
   🎉 WIN
```

---

## 🎴 Card Collection

The game currently uses these emoji:

🍎 Apple
🍌 Banana
🍇 Grapes
🍉 Watermelon
🍓 Strawberry
🍒 Cherry
🍑 Peach
🍍 Pineapple

Each emoji appears **twice**, creating 8 matching pairs.

---

## 📊 Game Features

### 🎯 Move Counter

Every time two cards are selected, the **Moves** counter increases.

### 🔍 Matching System

The JavaScript compares the IDs of the selected cards to determine whether they are a matching pair.

### 🔄 Reset Game

Click **New Game** to completely reset the board and generate a new shuffled deck.

### 🏆 Win System

When all 8 pairs are matched, the game displays:

> 🎉🎉 YOU WIN! 🎉🎉

and activates a glowing win animation.

---

## 📱 Responsive Design

The game is designed to work on different screen sizes.

On smaller devices:

* Smaller cards
* Reduced spacing
* Smaller fonts
* Responsive game container
* Flexible statistics section

---

## 📂 Project Structure

```text
Memory-Card-Game/
│
├── index.html
└── README.md
```

The complete game is contained in a single **HTML file**, including the CSS styling and JavaScript game logic.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Memory-Card-Game.git
```

### 2. Open the project

Go to the project folder:

```bash
cd Memory-Card-Game
```

### 3. Run the game

Simply open:

```text
index.html
```

in your web browser.

No server or database is required. 🚀

---

## 💡 Future Improvements

Some features that could be added in future versions:

* ⏱️ Game timer
* 🏅 Best score system
* 🎚️ Difficulty levels
* 🔊 Sound effects
* 🌙 Theme switcher
* 🥇 Leaderboard
* 📈 Game statistics
* ❤️ Lives system
* 🎨 Multiple card themes

---

## 📸 Screenshots

Add your game screenshots here:

```markdown
![Memory Card Game Screenshot](screenshot.png)
```

---

## 🤝 Contributing

Contributions are welcome! ❤️

If you have an idea to improve the game:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push to your branch
6. Create a Pull Request

---

## 👨‍💻 Developer

**Your Name**

🎓 HNDIT Student
💻 Aspiring Software Developer

### Skills Used

`HTML5` `CSS3` `JavaScript` `Responsive Design` `DOM Manipulation`

---

## ⭐ Support

If you like this project, please consider giving the repository a **⭐ Star** on GitHub!

It really helps and motivates me to build more projects. ❤️

---

## 📄 License

This project is open-source and available for learning and educational purposes.

---

### 🎴 Remember the cards. Match the pairs. Beat your score! 🧠🔥
