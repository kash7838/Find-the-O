🎮 Find the Sequence — Web Game
Find the Sequence is a fast, fun, pattern‑recognition web game built entirely with HTML, CSS, and JavaScript.
Players must identify the correct sequence of symbols (X and O) from three options.
The game supports both Single Player and Multiplayer modes, with scoring, turn‑tracking, and a final scorecard.

This project is designed to be lightweight, mobile‑friendly, and easy to deploy on any static hosting platform.

🚀 Features
🧍 Single Player Mode
Enter your name to begin.

Play 5 rounds.

Earn 10 points for every correct answer.

Live counters for:

Correct answers

Wrong answers

Current turn

Final Score Card displayed at the end.

👥 Multiplayer Mode
Supports up to 3 players.

Each player must have a unique name.

Players take turns automatically.

Each player gets 5 rounds.

After all players finish:

A ranked scoreboard is displayed.

Scores are sorted from highest to lowest.

Clean, centered scorecard layout.

🎨 UI & Design Highlights
Fully centered home screen (title + mode selection) on both desktop and mobile.

Tetris‑style background for a retro‑game feel.

Pink name‑entry boxes with black borders.

Large, bright yellow sequence boxes with red X/O symbols.

Left‑side stats panel showing:

Correct

Wrong

Turn

Clean, centered Score Card with bold typography.

Responsive layout across devices.

🧠 Gameplay Logic
Each round randomly selects one of three sequences:

A: [X, X, O]

B: [O, X, X]

C: [X, O, X]

The displayed sequence changes every round.

Players choose from three labeled options.

Correct answers add 10 points.

No pop‑ups for correctness — everything updates live on screen.

🛠 Tech Stack
HTML5 — structure

CSS3 — layout, styling, animations

JavaScript (Vanilla) — game logic, state management

No frameworks. No dependencies.
Just clean, readable, maintainable code.

📦 How to Run
Clone the repository:

bash
git clone <your-repo-url>
Open index.html in any modern browser.

No build steps. No server required.

📁 Project Structure
Code
/project-root
│── index.html        # Main game file
│── README.md         # Project documentation
└── (optional assets)
🧩 Future Enhancements (Optional Ideas)
Sound effects for correct/wrong answers.

Animations for sequence reveal.

Difficulty levels (more boxes, faster rounds).

Leaderboard with local storage.

PWA support for mobile installation.

👨‍💻 Author
Kaushal  
A passionate builder focused on clean UI, smooth UX, and polished game mechanics.
