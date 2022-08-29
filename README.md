# TicTacToe-on-LAN

The code implements a two-player tic-tac-toe game using the traditional client-server architecture.

In tic-tac-toe, there are totally two players and a 3×3 empty board so that if player 1 chooses a symbol ‘X’ and then player 2 chooses ‘O’. If any column or any row or any diagonal gets filled with the same symbol then the player corresponding to that symbol will win. The players will act as clients and the server should handle those two clients.

The design supports multiple games simultaneously. When there are an odd number of players, the one who joined last will wait for some player to join in. If a certain player takes more than 15 seconds to make a move, the game will be automatically quitted, the player and his partner will be asked whether they want to replay.

Server maintains and updates all game related statistics in a log file. For example, time of the game, how long the game lasted, which player won and the sequence of moves given by the players
