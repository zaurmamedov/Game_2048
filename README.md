# 2048 Game

A browser-based implementation of the classic 2048 puzzle game. Combine tiles with the same value, grow your score, and reach the `2048` tile to win.

## Live Preview

- [Demo Link](https://zaurmamedov.github.io/Game_2048/)

## Design Reference

- [reference](https://play2048.co/)

## Technologies Used

- HTML5
- SCSS
- JavaScript (ES6+)
- Parcel
- ESLint
- Stylelint

## Features

- Classic **4x4 2048 gameplay**
- Keyboard controls (Arrow keys)
- Random tile generation (2 or 4) after each move
- Real-time score tracking
- Win condition (2048 tile reached)
- Lose condition (no available moves)
- Start and restart functionality
- Responsive layout (mobile / tablet / desktop)

## 🧠 Key Challenges

- **Game Logic Implementation**
  Handling tile movement, merging rules, and preventing double merges in one move.

- **State Management**
  Keeping track of the board, score, and game status (win/lose).

- **Responsive Layout**
  Ensuring the game scales correctly across different screen sizes.

- **Smooth Interactions**
  Making transitions and UI updates feel natural and responsive.

## Getting Started

### Clone the repository

```bash
git clone https://github.com/zaurmamedov/Game_2048.git
cd Game_2048
```

### Install dependencies

```bash
npm install
# or
yarn install
```

### Run the project locally

```bash
npm start
# or
yarn start
```

