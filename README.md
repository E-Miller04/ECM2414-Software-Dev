# Software-Development-Java
2nd Year Java Project. Multi-threaded card playing simulation.
packfile is played with 4 players.

Takes 2 inputs - player amount and a text file.
Text file contains cards which are then distributed to the hands (need 4 cards) and then the decks.
To win a player needs a hand of 4 identical valued cards.
Can win straight away with distribution or when players start running.
When each player runs, they draw and discard until they have won, and they let the other players know, or they are interrupted.

Player 1 draws from deck 1 (top) and discards to deck 2 (bottom), player 1 draws from deck 2 and discards to deck 3, and so on.
