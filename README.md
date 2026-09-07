# 🌈 Rainbow Tic-Tac-Toe

A single-file, no-dependencies Tic-Tac-Toe game with a colorful design, a genuinely unbeatable AI, and — because why not — a real cryptographic blockchain that logs every move you make.

**[▶ Play it live](#)** &nbsp;·&nbsp; Built with plain HTML, CSS, and JavaScript. No frameworks, no build step, no installs.

## Features

- 🎨 Vibrant, hand-tuned UI with animated marks, confetti, and a rainbow win-line
- 🤖 Play vs a friend or vs the computer, with **Easy / Medium / Hard** difficulty (Hard uses minimax — it cannot lose)
- 🏆 **Match mode** — Best of 3 / 5 / 7, with a champion celebration
- ⏱️ **Move timer** — optional Blitz (5s), Fast (8s), or Relaxed (12s) countdown per turn
- ↩️ Undo, move history log, custom player names, sound effects, win-streak tracking
- ⛓️ **Blockchain ledger** — every move is mined into a real SHA-256 block (via the Web Crypto API) that links to the one before it. A "Verify chain" and "Tamper block" button let you see tamper-detection in action, live.

## Run it

Just open `tic-tac-toe.html` in any modern browser. That's it — no server, no npm install.

## Tech

Vanilla JS, CSS custom properties, and the browser's native `crypto.subtle` API for the blockchain hashing — no external libraries.

## License

MIT
