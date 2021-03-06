A mock-up of the classic [Minesweeper](http://en.wikipedia.org/wiki/Minesweeper_(video_game\)).

After selecting the size of the square board (bigger is more difficult), and the number of mines (more is more difficult), the player _reveals_ or _flags_ the hidden cells of the board one at a time. 

If a bomb is _revealed_, the game ends. If a cell adjacent to a bomb is _revealed_, a number is displayed that indicates how many bombs are adjacent to that cell. If a _revealed_ cell is not adjacent to any bomb, all its adjacent cells are revealed; this proceeds iteratively, until all _revealed_ cells are either surrounded by _revealed_ cells, or have an adjacent bomb. Then, control is passed back to the player.

Unrevealed cells can be flagged as containing a bomb. The player wins when all bombs are flagged, and all other cells are revealed.

The game state can be saved or loaded as a text file. It is, unfortunately, fairly easy to cheat by examining the save file.

