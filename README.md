# NBA Roster Quiz

A web-based quiz game where users guess NBA players from the current roster of randomly selected teams. Players have 60 seconds to guess as many names as possible. The game tracks scores and high scores across sessions.

---

## Features

- Randomly selects an NBA team for each game.  
- Tracks guesses and prevents duplicate entries.  
- Displays a live timer counting down from 60 seconds.  
- Shows current score and all-time high score (stored in local storage).  
- Reveals full team roster after the game ends.  
- Allows players to reset game or play again.  

---

## Technologies Used

- **HTML5** – semantic markup for structure.  
- **CSS3** – modern styling, flexbox layout, responsive design.  
- **JavaScript (ES6)** – DOM manipulation, event handling, JSON data fetching.  

---

## Installation

1. Clone the repository in your terminal:  
- git clone https://github.com/yourusername/nba-roster-quiz.git
2. Open index.html in a web browser.
- No additional dependencies are required; the app runs purely in the browser.

---

## Usage

- Click Start Game to begin.
- Type player names in the input box and press Enter or click Guess.
-  The game tracks your score in real time.
- When the timer reaches 0, the full roster of the selected team is displayed.
- Click Play Again to start a new round or Reset Game to return to the main screen.

Notes:
- Player names are case-insensitive and can be guessed by first name, last name, or full name.
- High scores persist across browser sessions using local storage.
