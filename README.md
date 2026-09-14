# 🎮 Clicker Game

A fun, fast-paced web-based clicker game with dynamic sound effects, multiple difficulty levels, and a persistent leaderboard!

## Features

✨ **Core Features:**
- 🖱️ Fast-paced clicking gameplay
- 🔊 Real-time sound effects using Web Audio API
- ⏱️ Three difficulty levels (Easy: 45s, Medium: 30s, Hard: 15s)
- 📊 CPS (Clicks Per Second) counter
- 🏆 Persistent leaderboard with top 10 scores
- 📱 Fully responsive design (desktop, tablet, mobile)
- 🎨 Beautiful gradient UI with smooth animations

## How to Play

1. **Select Difficulty**: Choose between Easy (45 seconds), Medium (30 seconds), or Hard (15 seconds)
2. **Click to Start**: Click the "Click Me!" button to begin the game
3. **Click Fast**: Click as many times as possible before time runs out
4. **Track Progress**: Monitor your score and clicks-per-second in real-time
5. **View Results**: After the game ends, your score is saved and displayed on the leaderboard

## Gameplay Mechanics

- **Score**: Increases by 1 with each click
- **CPS (Clicks Per Second)**: Shows your clicking speed updated every second
- **Timer**: Counts down based on selected difficulty
- **Leaderboard**: Displays your top 10 scores with difficulty level and date

## Technical Details

### Technologies Used
- **HTML5**: Structure and semantic markup
- **CSS3**: Modern styling with gradients and animations
- **JavaScript (ES6+)**: Game logic and Web Audio API

### Sound Generation
The game uses the **Web Audio API** to generate dynamic sound effects:
- **Click Sound**: High frequency sine wave (800Hz → 400Hz sweep)
- **Game Over Sound**: Lower frequency square wave (400Hz → 200Hz sweep)

### Storage
- Scores are saved to browser's **LocalStorage**
- Top 10 scores are automatically ranked and displayed
- No server required - fully client-side

## Browser Compatibility

✅ Chrome/Edge
✅ Firefox
✅ Safari
✅ Opera
✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Installation

Simply open `index.html` in your web browser - no installation needed!

Or deploy to GitHub Pages:
1. Go to repository Settings
2. Navigate to Pages section
3. Select "Deploy from a branch"
4. Choose `main` branch and `/root` folder
5. Your game will be live at `https://yourusername.github.io/clicker-game/`

## Play Online

🎮 **[Play the game on GitHub Pages](https://atifkhanmohammadismail-coder.github.io/clicker-game/)**

## Future Enhancements

- 🎯 Power-ups and multipliers
- 🌍 Global leaderboard (with backend)
- 🎖️ Achievement system
- 🌙 Dark mode toggle
- 🎵 Custom sound themes
- 📈 Statistics dashboard

## License

MIT License - Feel free to fork, modify, and share!

## Author

Created by [@atifkhanmohammadismail-coder](https://github.com/atifkhanmohammadismail-coder)

---

**Have fun clicking! 🚀**
