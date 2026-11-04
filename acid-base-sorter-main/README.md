# 🧪 Acid-Base Sorter

**Subject:** Science (Chemistry — acids, bases, and pH)
**File:** `science-game.html`

## 🌐 Play Online
https://wcheng-t12.github.io/acid-base-sorter/

## 📖 About
A real-time sorting game. Common substances — from lemon juice to bleach — fall from the top of the screen, each showing its name and approximate pH. Three bins sit at the bottom: **Acid**, **Neutral**, and **Base**. Switch your active bin and click each substance to sort it correctly before it reaches the bottom.

## 🎮 How to Play
1. Switch the **active bin** using:
   - Arrow keys (← →)
   - A / D keys
   - Tapping a bin directly
2. Click a falling substance to sort it into the currently active bin.
3. Correct sorting = +10 points.
4. Incorrect sorting, or letting an item fall to the bottom unsorted, costs 1 life (❤️).
5. Sort as many substances as possible before the 60-second timer runs out!

## ✅ Features
- Start screen + instructions screen
- Score tracking
- 3 lives (❤️)
- Single continuous 60-second timer
- 33 real-world substances across acid / neutral / base categories
- Sound effects + looping background music (Web Audio API, no external files)
- End-game screen with star rating (⭐ 1–3) based on final score
- Play Again button
- Mute/unmute toggle

## 🛠️ Customization
Key constants near the top of the `<script>` section:
- `GAME_TIME` — total game duration in seconds (default: 60)
- `STARTING_LIVES` — number of lives (default: 3)
- `substances` array — add, remove, or edit substances and their acid/neutral/base classification
- Spawn interval (`setInterval(spawnItem, 1300)`) — controls how frequently substances fall

## 💻 Running Locally
Just open `science-game.html` in any modern browser — no installation or build steps required. For live-reload while editing, use the VS Code "Live Server" extension.
