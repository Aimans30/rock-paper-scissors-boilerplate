# Rock Paper Scissors Game Development

## Step-by-Step Plan for Hour 2

### 1. Game Logic: Deciding the Winner

- Compare the player's choice and the computer's random choice using `if-else` statements or a switch-case.
- Rock beats Scissors.
- Scissors beat Paper.
- Paper beats Rock.
- If the choices are the same, it results in a tie.

### 2. Scorekeeping: Tracking Progress

- Add variables to track scores for the player and the computer (`playerScore` and `computerScore`).
- Update and display these scores after every round.

### 3. User Interface Updates

- Display the player's choice, computer's choice, and the result (win, lose, or tie) in the UI.
- Show the current score directly on the screen.

### 4. Adding a Reset or Play Again Button

- Provide a "Play Again" or "Reset" button to restart the game or continue playing multiple rounds.
- Reset the score when the "Reset" button is clicked.

### 5. Enhancements for User Experience

- Add animations or visual effects, such as:
  - Highlighting the winning choice.
  - Displaying messages like "You Win!" or "Computer Wins!".
- Use tooltips or labels to guide the user on how to play.

### 6. Error Handling and Edge Cases

- Ensure only valid inputs (Rock, Paper, or Scissors) are processed.
- Add a default case for unexpected inputs.
