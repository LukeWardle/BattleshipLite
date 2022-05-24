BattleshipLite

Battleship Lite Application
Basic Requirements
To build a small, 2 player console game that has it roots in the game Battleship from Mattel. There will be a 25-spot grid ranging from A1 -E5.
Each player will place 5 pegs on the board to represent their 5 ships. Players will then take it in turns firing at their opponents’ ships. The first person to sink all 5 ships wins.

General Flow
2 users open the console
Ask user 1 for where to place their ships.
Ask user 2 for where to place their ships.
Ask user 1 for a shot
	Determine hit or miss.
	Determine if the games is over.
Ask user 2 for a shot
	Determine hit or miss
	Determine if the game is over
Repeat until someone wins
Identify who the winner is
Exit the application




Additional Questions/Requirements
1.	Is it the Same console or 2 different consoles working together? Same console
2.	Does the other player get one last chance after being sunk? No
3.	Do we want to capture/display statistics such as hit/miss ratio etc? Just how many shots it took to win
4.	Only one ship per spot?
5.	Do we allow a player to shoot the same spot twice? No
6.	Do we show a visual of the grid? Yes
7.	Do we store games data such as how many times a person has one or loss? No
8.	Are we ever going to change the number of players? May be
9.	Will we add a computer player? Maybe






Full Requirements
•	2 player game
•	25 spot grids (A1-E5)
•	Each player gets 5 ships.
•	Each ship takes up one spot.
•	Players take turn firing.
•	First person to sink all 5 wins.
•	One console for everyone.
•	No completing the round after 5 sunk ships.
•	Show the visual of the grid with hit and misses.
•	Do not allow the user to shoot the same spot twice.










UI Design
1.	Welcome message.
2.	Ask user 1 for their name.
3.	Ask the user for their 5 ship placements.
3.1.	Ask for placement.
3.2.	Determine if it was valid.
3.3.	Store.
3.4.	Clear.
4.	Ask user 2 for their name.
5.	Ask user 2 for their ship placements.
5.1.	Ask for placement.
5.2.	Determine if it was valid.
5.3.	Store.
5.4.	Clear.
6.	Display grid of where user 1 has fired.
7.	Ask user 1: Where would you like to fire on?
7.1.	Verify a valid spot.
7.2.	Check results.
7.3.	Store shot.
7.4.	Clear.
8.	Display the score (user1:2 ships left, user 2: 4 ships left)
9.	Repeat with user 2.
10.	Loop until someone wins.
11.	Print winners name and number of shots taken.
12.	Wait for user to say they are done.



UI Design Cont...

A1	A2	A3	A4	A5
B1	B2	B3	B4	B5
C1	C2	C3	C4	C5
D1	D2	D3	D4	D5
E1	E2	E3	E4	E5


A1	A2	A3	X	A5
O	B2	B3	O	B5
O	X	C3	C4	X
D1	D2	D3	D4	O
O	O	D3	D4	D5


GridSpot
SpotLetter - string
SpotNumber - int
Status – string (possible Enum)



Logic Design
•	Clear Display
•	Method: Asking for name.
•	Method: Get ship placement.
•	Method: Determine if valid spot for ship.
o	Storing ship information: List per user?
o	Storing shot information: List per user?

•	Method: Create the grid for the user.
•	Method: Print out grid.
•	Method: Fire on Opponent.
•	Method: Determine if a shot can be taken & outcome.
•	Method: Display score.
•	Method: Print winner and shots taken.

Data Design
•	User’s name – string.
•	User’s ship locations – List<GridSpot>
•	User’s shot grid – List<GridSpot>

[Battleship Lite Application Plannign Notes.docx](https://github.com/Codenforcer/BattleshipLite/files/8748663/Battleship.Lite.Application.Plannign.Notes.docx)
