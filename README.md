JS-Team-Work--Quiz-game-
========================
Team Banana :
1.  Asia Todorova – atodorova
2.	Ventsislav Staykov – v.staykov
3.	Ivailo Ivanov – Jarolim
4.	Ivan Ivanov – ivivanov
5.	Ivan Petrov – Ivanski1024

Project information: 
The project purpose is creating a simple online quiz game. The player will compete with specially implemented AI bot on a variety of topics. The idea of the game flow is:
1.	The player enters the game’s website where an initial welcome message shows up. Here the player should enter his/her name and press the “play” button. If the player do not enter his/her initials – a default value is send to the game engine – “John Doe”;
2.	When the “play” button is pressed the main interface of the game is rendered on the page. It includes:
a.	A game field that contains the main menu buttons and the flags with all questions;
b.	A hidden field where the score board will be printed on demand;
c.	A message field which contains the main instructions and information for the player;
d.	A question field where each question will be printed;
e.	Two fields which keep the information for the two players – their names and points. The name of the player’s opponent is chosen from an array of cartoon characters’ names.
3.	After rendering the initial game “skeleton” the player starts a new game with pressing the „start game” button”. Then 10 flags are loaded in the game field. When clicked each flag loads a question in the question field;
4.	When a question is loaded the player has 10 sec to answer it or a random answer is selected. After that the opponent gives his answer two and they are both checked with the questions real answer;
5.	 If only the player or only the opponent answers correct – 10 points are added to their current points amount. If the two players give correct answer – another question of type “short answer question” is asked. Who is closer to the correct answer of the question gets the points;
6.	When all of the 10 questions are answered – the winners name and points are saved in the score list using local storage.
Menu buttons:
•	START GAME – starts a new game; 
•	END GAME – ends the current game; clears the players’ scores;
•	HELP – shows some useful information about the game and how to play;
•	TOP SCORES – shows/hides the score board;
There is also an implemented functionality for sharing the game using the most popular social networks.
