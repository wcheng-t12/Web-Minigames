# 🔢 Target Number Catcher

**Subject:** Mathematics (factors, multiples, primes, perfect squares, comparisons)
**File:** `math-game.html`

## 🌐 Play Online
https://wcheng-t12.github.io/target-number-catcher/


## 📖 About
A fast-paced number-catching game. Each round displays a rule — e.g. *"Catch multiples of 3"*, *"Catch PRIME numbers"*, or *"Catch numbers GREATER than 12"*. Numbered balls fall from the top of the screen; move your basket to catch the numbers that match the rule and avoid the ones that don't.

## 🎮 How to Play
1. Read the rule shown at the top of the screen for the current round.
2. Move the basket left/right using:
   - Arrow keys (← →)
   - A / D keys
   - Dragging on touch screens
3. Catch numbers that match the rule (+10 points).
4. Catching a number that does **not** match the rule costs 1 life (❤️).
5. Survive all 10 rounds before time and lives run out!

## ✅ Features
- Start screen + instructions screen
- Score tracking
- 3 lives (❤️)
- 20-second timer per round
- 10 randomized rounds (rules are randomly generated each round)
- Sound effects + looping background music (Web Audio API, no external files)
- End-game screen with star rating (⭐ 1–3) based on final score
- Play Again button
- Mute/unmute toggle

## 🛠️ Customization
Key constants near the top of the `<script>` section:
- `TOTAL_ROUNDS` — number of rounds (default: 10)
- `STARTING_LIVES` — number of lives (default: 3)
- `ROUND_TIME` — seconds per round (default: 20)
- `makeRule()` — add or edit the pool of math rules used each round
- Spawn interval (`setInterval(spawnItem, 900)`) — controls how frequently numbers fall

## 💻 Running Locally
Just open `math-game.html` in any modern browser — no installation or build steps required. For live-reload while editing, use the VS Code "Live Server" extension.
