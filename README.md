
# ♟️ Chess Game – Interactive Web Chessboard

This project is a fully interactive web-based chess game built with **HTML**, **CSS**, **JavaScript**, and **jQuery**. It replicates standard chessboard behavior with animated visual feedback, move options, and turn-based logic for white and black players.

---

## 🧩 Project Structure

```
📦 chess-game/
├── index.html       # HTML structure for the board
├── style.css        # Board and animation styles
├── script.js        # Chess logic and interactions
├── dark.css         # Optional dark theme
└── light.css        # Optional light theme
```

---

## 🎮 Features

- Full 8x8 **interactive chessboard**
- **All major chess piece movements** (king, queen, bishop, rook, knight, pawn)
- **Castling logic** for both white and black
- **Turn-based mechanics**
- Visual indicators for **valid moves** using animations
- **Dark and Light themes** (easily swappable)
- **Smooth animations** and neon effects for selected moves

---

## 🧠 JavaScript Concepts Used

| Concept | Description |
|--------|-------------|
| DOM Manipulation | Adding/removing pieces, highlighting moves |
| Objects | Used to store all chess pieces with metadata |
| jQuery | Simplified DOM selection and event handling |
| Event Listeners | Click handling for moves and captures |
| Game State | Turn tracking, piece positions, captured status |
| Animation & Effects | CSS transitions, keyframes, and hover states |

---

## 💡 How It Works

### ♙ Board Setup
The chessboard is built manually using 64 divs, with IDs like `1_1`, `8_8`, etc. representing cell coordinates. Initial piece positions are stored in an object with Unicode chess symbols.

### 🧮 Game Logic
- Each piece type has custom movement rules.
- The game checks for valid moves and captures.
- Turn alternation is managed with a flag (`w` or `b`).
- Special moves like castling are handled with checks on movement flags.

### 🎨 Styling
- Neon text effects (`.neongreen_txt`) and shaking animations (`.shake-little`) for selected/highlighted moves.
- Light and Dark mode styles available via external CSS files (`dark.css`, `light.css`).

---

## 🖥️ How to Run

1. Clone or download the project.
2. Open `index.html` in your browser.
3. Click pieces to see valid moves and perform actions.

---

## 📁 Sample Usage

- Click on a white pawn → Highlights its valid forward moves.
- Click a highlighted tile → The piece moves and the turn switches.
- If a king and rook haven't moved → Castling becomes possible.

---

## 🚀 Possible Enhancements

- Add AI for single-player mode
- Validate full check/checkmate logic
- Implement drag-and-drop functionality
- Add support for saving game state (e.g., `localStorage`)
- Add undo/redo functionality

---

## 👨‍💻 Author

Crafted with precision and a love for chess and code.































![image](https://github.com/user-attachments/assets/af3bc5e5-a1d3-4a03-a634-da4deed2e057)
