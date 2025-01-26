Features:

1. Popups before and after the game: The program displays a popup message to provide instructions before starting the game and a congratulatory message when the player completes the puzzle. (Used tkinter for macOS compatibility)

1-1. Game completion summary: Upon finishing the puzzle, the program displays the total time played and the number of moves taken in a popup window.

2. Background image insertion: Before the game begins, the first window is initialized with a background image.

3. Optimization every 30 moves: To prevent the graphical stack from growing excessively and impacting performance, all images in the window are deleted to optimize performance.

4. Background changes every 60 moves: For refreshing

5. Real-time logs in the command line: A log system outputs real-time updates in the command line, allowing players to monitor the game's status and actions.

6. GraphicError handled: If the user closes the window by clicking the X button on top-right during the game, no error messages will appear in the command line.
