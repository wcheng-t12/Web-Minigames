# ⚔️ Word Warrior

**Subject:** English (typing, vocabulary, spelling)
**File:** `typing-game.html`

## 🌐 Play Online
```
https://wcheng-t12.github.io/word-warrior/
```

## 📖 About
A typing-based combat game. Words appear on screen — just start typing to fight! Completing a word correctly makes your stickman attack a mob. Gold "bonus words" reward you with extra time when typed correctly, while mistakes cost you precious seconds.

## 🎮 How to Play
1. A word appears on screen — start typing it (no clicking required).
2. Correctly typed letters turn green as you go.
3. Completing a word correctly → your stickman attacks the mob, dealing damage.
4. A wrong keystroke shakes the word and costs 1 second from the timer.
5. **Gold/highlighted words are BONUS WORDS** — completing them adds +5 seconds to the clock.
6. Defeat mobs to earn points and face progressively tougher enemies.
7. Survive as long as possible before the 60-second timer runs out!

## ✅ Features
- Start screen + instructions screen
- Score tracking
- 60-second timer with bonus-word time extensions
- Mob difficulty increases as more mobs are defeated (HP increases, enemy variety cycles)
- Sound effects + looping rhythmic background music (Web Audio API, no external files)
- End-game screen with star rating (⭐ 1–3) based on final score
- Play Again button
- Mute/unmute toggle
- Works on desktop (keyboard) and mobile (tap to bring up on-screen keyboard)

## 🛠️ Customization
Key constants near the top of the `<script>` section:
- `GAME_TIME` — total game duration in seconds (default: 60)
- `WRONG_KEY_PENALTY` — seconds lost per incorrect keystroke (default: 1)
- `BONUS_TIME_GAIN` — seconds gained for completing a bonus word (default: 5)
- `BONUS_WORD_CHANCE` — probability the next word is a bonus word (default: 0.18)
- `regularWords` / `bonusWords` arrays — customize the word lists (e.g. spelling lists, vocabulary themes)
- `MOB_BASE_HP` — starting mob health (difficulty scaling)

## 💻 Running Locally
Just open `typing-game.html` in any modern browser — no installation or build steps required. For live-reload while editing, use the VS Code "Live Server" extension.
