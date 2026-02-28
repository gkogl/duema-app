# デュエマ調整アプリ PRO

A deck-building and game simulation tool for Duel Masters card game.

## Features

- 📝 **Deck Input**: Input cards in the format `カード名|コスト|文明` (Card Name | Cost | Civilization)
- 🎮 **Game Simulation**: Play through turns and see your deck's performance
- 🤖 **AI Auto-Play**: Automatically play out 10 turns
- 📊 **Statistical Analysis**: Run 10,000 simulations to calculate initial success rates
- 📱 **PWA Support**: Works offline with Service Worker caching

## How to Use

1. Enter your deck list in the textarea with format:
   ```
   カード名|コスト|文明
   フェアリー・ライフ|2|自然
   ボルシャック・ドラゴン|6|火
   ```

2. Click one of the buttons:
   - **ゲーム開始** (Start Game): Begin a single game
   - **AI回し** (Auto Play): Automatically play 10 turns
   - **1万回シミュ** (10K Simulations): Run 10,000 simulations

## Live Demo

Visit: https://gkogl.github.io/duema-app/

## Installation

This is a web app that works in any modern browser. For offline support, the app registers a Service Worker automatically.

## Files

- `index.html` - Main HTML structure
- `style.css` - Styling (dark theme)
- `app.js` - Game logic and simulation
- `service-worker.js` - PWA offline support
- `manifest.json` - PWA metadata