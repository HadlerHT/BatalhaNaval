# Battleships in C

## Context
This code was developed as a project to the programing introduction discipline on the electric engineering course by USP (Universidade de São Paulo) thought 2 months. Suggest by the Dr. Jó Ueyama, who had been teaching C language coding to his class, as a challenge andfinal test to his students, the implementation should be made only using the language standard libraries and should run on the OS terminal. Throughout the code, almost every resource available in the language was at least once used to accomplish the final required result: a fully functional Battleships game.

## Trivia	
The Battleships game was vastly played around the World War I in France, even though some different versions of it were seen around 1890 in Russia being used by military officers. This one was one of the earliest games to receive a computer version, being released in 1979, therefore becoming traditionally a task to be done by beginners on the programming branch as practice and familiarization with the language syntaxes and resources, code algorithm and problem solving.
 
## Objective of the Game
Battleship is a two players game is which the objective is destroy all the enemy fleet. The gameplay is based on turns and both fleets are randomized across the field. So players starts shooting alternately on hidden enemy ships, the first one to hit all wins.

## Implementation
run game:
Game functions: On the game menu, type “iniciar” to start the game or “ajuda” to get some info.
Inside the game there are some functionalities, such as: 
acaso: Changes fleet position, but conserves score.
ajuda:	Shows game info for the players.
carregar: Open a saved game.
desistir: Gives a current player a chance to surrender.
gravar: Saves the game in this format tabuleiro-yyyy.mm.dd_hhmmss.txt
pow: Shoots on a determined position, like “pow 2H”.
revelar: Reveal fleets or hide them.
sair: Leave the game.
win: Makes the current player instantly win the match, but it needs a password.


		
	
	

