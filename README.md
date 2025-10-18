# Dice Game Site

Welcome to the Dice Game Site — a simple browser-based 2-player dice game built with JavaScript, HTML and CSS.

Description
-----------
This small game lets two players take turns rolling a die. The goal is to reach a target score (default: 100) before the other player. Players can roll the die to accumulate points for the current turn, or hold to add the turn's points to their total. Rolling a 1 forfeits the current turn's points and passes the turn to the other player.

Demo
----
Open `index.html` in your browser to play locally. (No server required.)

Features
--------
- Two-player turn-based dice game
- Roll and Hold mechanics
- Track current and total scores
- Simple, responsive UI using HTML/CSS/JavaScript

How to Play
-----------
1. Player 1 starts and may click "Roll" to roll the die.
2. If the die shows 2–6: the value is added to the current turn score.
3. If the die shows 1: the current turn score is lost and the turn passes to the other player.
4. The player can click "Hold" to add the current turn score to their total score and pass the turn.
5. First player to reach the target score (default 100) wins.
6. Click "New Game" to reset scores and start again.

Installation (run locally)
--------------------------
- Option A (quick): Download the repository and open `index.html` in your browser.
- Option B (with Git):

```bash
git clone https://github.com/KamaleshAshokkumarKowsalya/Dice-game-site.git
cd Dice-game-site
# open index.html in your browser (double-click or use a local server)
```

Working with a local server (optional):
```bash
# using Python 3
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Project structure
-----------------
- index.html         — main HTML file and entry point
- css/               — stylesheet(s)
- js/                — JavaScript game logic
- assets/            — images (die faces), icons, etc.
- README.md          — this file

Technologies
------------
- JavaScript
- HTML5
- CSS3

Customization
-------------
- Change the target winning score in the JavaScript file if you want a shorter or longer game.
- Swap or style die-face images in the assets folder to change visuals.
- Add sound effects by playing audio files on roll/hold/win events.

Contributing
------------
Contributions are welcome. If you'd like to:
1. Fork the repo
2. Create a feature branch
3. Open a pull request describing your changes

Please keep changes small and focused. If you're proposing a larger feature, open an issue first to discuss.

Issues & Support
----------------
If you find a bug or have a feature request, please open an issue in the repository: https://github.com/KamaleshAshokkumarKowsalya/Dice-game-site/issues

Author
------
Kamalesh Ashokkumar Kowsalya

Acknowledgements
----------------
- Small project created for learning and demonstration purposes.

Have fun playing — roll well!
