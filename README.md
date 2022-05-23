# Connect-4

To create a Connect 4 game with basic AI move choosing using the random() function. Choose yellow or red discs, and then take turns dropping coloured discs into a seven-column grid. When you get four discs in a row in two players, you win. When the computer selects what move to make next, it evaluates all of its available positions, but to simplify things, it utilises a random() function to select the column. To enhance this version, the minmax algorithm can be applied to ensure that the system wins with the best odds.

Algorithm:
1. Start
2. Request the selection of the second player. Either a computer or a person.
3. If the computer is chosen, it chooses a random place from 1 to 7 to drop the coin.
4. If Human is chosen, choose a position from 1 to 7 to drop the coin.
5. The check(int, int) function determines whether there is a horizontal, vertical, right diagonal, or left diagonal match.
6. If check(int, int) returns 1, the player in question wins.
7. Otherwise, the match is repeated until the check(int, int) function returns 1.
8. If all columns are filled, the match is a tie.
9. Finally, the winning player is shown.
10. End
