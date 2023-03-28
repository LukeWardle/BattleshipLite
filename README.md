<h1>BattleshipLite Project</h1>
This is a console-based 2-player game that is based on the popular board game Battleship from Mattel. The game involves a 25-spot grid ranging from A1 - E5, where each player will place 5 pegs on the board to represent their 5 ships. Players will take turns firing at their opponents’ ships, and the first person to sink all 5 ships wins.

<h2>How to Play</h2>
<ol>
  <li>1.Two players open the console.
  <li>2.Ask user 1 for where to place their ships.
  <li>3.Ask user 2 for where to place their ships.
  <li>4.Ask user 1 for a shot.
  <li>5.Determine hit or miss.
  <li>6.Determine if the games is over.
  <li>7.Ask user 2 for a shot.
  <li>8.Determine hit or miss.
  <li>9.Determine if the game is over.
  <li>10.Repeat until someone wins.
  <li>11.Identify who the winner is.
  <li>12.Exit the application.
 </ol>

<h2>Additional Requirements</h2>
The game is played on the same console.
The other player does not get one last chance after being sunk.
Only one ship can be placed per spot.
A player cannot shoot the same spot twice.
A visual of the grid is shown.
The game data is not stored.
The number of players may be changed in the future.
A computer player may be added in the future.

<h2>UI Design</h2>
Display a welcome message.
Ask user 1 for their name.
Ask user 1 for their 5 ship placements.
Ask for placement.
Determine if it was valid.
Store.
Clear.
Ask user 2 for their name.
Ask user 2 for their ship placements.
Ask for placement.
Determine if it was valid.
Store.
Clear.
Display grid of where user 1 has fired.
Ask user 1: Where would you like to fire on?
Verify a valid spot.
Check results.
Store shot.
Clear.
Display the score (user1:2 ships left, user 2: 4 ships left).
Repeat with user 2.
Loop until someone wins.
Print winners name and number of shots taken.
Wait for user to say they are done.

<h2>Logic Design</h2>
Clear Display
Method: Asking for name.
Method: Get ship placement.
Method: Determine if valid spot for ship.
Storing ship information: List per user?
Storing shot information: List per user?
Method: Create the grid for the user.
Method: Print out grid.
Method: Fire on Opponent.
Method: Determine if a shot can be taken & outcome.
Method: Display score.
Method: Print winner and shots taken.
Data Design
User’s name – string.
User’s ship locations – List.
User’s shot grid – List.

<h2>Authors</h2>
Luke Wardle - l.wardle@live.co.uk

[Battleship Lite Application Plannign Notes.docx](https://github.com/Codenforcer/BattleshipLite/files/8748663/Battleship.Lite.Application.Plannign.Notes.docx)
