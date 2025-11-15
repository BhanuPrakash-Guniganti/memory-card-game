# 🎮 Memory Card Game

A simple, interactive **Memory Matching Game** built using **HTML, CSS, and JavaScript**. Choose a difficulty level, flip cards, match pairs, and restart anytime.

---

## 🚀 Features

- **3 Difficulty Levels:** Easy (2×2), Normal (3×4), Expert (4×4)
- Smooth 3D flip animation
- Shake animation for wrong matches
- Rubber-band animation for correct matches
- Dynamic card generation and random shuffle
- Restart button
- Clean UI with Font Awesome icons


## 🧠 How the Game Works

1. Select a difficulty level (Easy / Normal / Expert)  
2. Click **Start Game**  
3. Cards are generated dynamically based on rows & columns  
4. Flip two cards:  
   - If they match → they stay open  
   - If not → they shake and flip back  
5. When all matches are found → a congratulations alert appears  
6. Press the **⟳ Restart icon** to play again

---

## 🧩 Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Layout & basic structure |
| **CSS3** | Styling, 3D flip animations, effects |
| **JavaScript (ES6)** | Game logic, DOM manipulation |
| **Font Awesome** | Icons for card faces |

---

## 🛠️ JavaScript Logic Overview

- `shuffleArray()` → Random card shuffle (Fisher–Yates)
- `createCards()` → Selects icons based on level and prepares pairs
- `shuffleCards()` → Creates card HTML and inserts into grid
- `flipCard()` → Controls flipping and locking card selections
- `matchCards()` → Compares two cards, applies animations, updates score

---

### 1️⃣ Clone the repository
```
git clone https://github.com/YOUR_USERNAME/memory-card-game.git
```

### 2️⃣ Open folder
```
cd memory-card-game
```

### 3️⃣ Run the game  
Open **index.html** in your browser.  
No build steps required.

---

## 💙 Author

**BhanuPrakash-Guniganti**  
A beginner-friendly frontend project made using pure HTML, CSS, and JavaScript.

