The NBA Roster Quiz is a browser-based game where users test their basketball knowledge by guessing players from a randomly selected NBA team.
The goal is to correctly name as many players from the team’s current roster as possible before time runs out (timer feature still in progress).

This project uses HTML, CSS, and JavaScript with the balldontlie API to dynamically load NBA team and player data.


How it works so far: 

When the user clicks “Start Game,” the app:
- Fetches all NBA teams from the API
- Chooses one team at random
- Fetches that team’s current players
- The chosen team’s name appears on the screen.
- The player types names into the input box.

When the player presses Enter:
- If the name matches a player on the team’s roster, it’s added to the “guessed” list.
- The score increases by 1 point.
- The user continues guessing until they stop or the next features (timer/game over) are added.


Features Still in Progress:
- Timer countdown for each round
- “Game Over” or “Round Complete” message
- Handling API errors
- Reset button for new rounds
- Better visual feedback (color changes for correct/incorrect guesses)
- Mobile-friendly layout
