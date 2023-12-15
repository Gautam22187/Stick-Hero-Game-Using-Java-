Stick Hero Game
This is a simple implementation of the Stick Hero game using Java and JavaFX. The game
consists of a stick figure hero who must cross platforms of varying lengths. The player can
control the length of the stick to bridge the gap between platforms and earn points. The game
includes features such as sound effects and a dynamic background.
Game Controls
Mouse Click: Start/stop increasing the length of the stick.
Mouse Release: Release the stick and attempt to cross the gap between platforms.
Mouse Click (on Game Over): Restart the game.
Features
Dynamic Background: The game features a changing background that transitions between
different images.
Sound Effects: Sound effects are included for actions such as eating fruit and game over.
Implementation Details
The game is divided into several packages:
gameController: Manages the game logic, user input, and overall flow of the game.
gameEngine: Represents the core game engine responsible for handling game mechanics.
gamePanel: Contains classes for different game panels, such as the start panel, play panel,
and game over panel.
Background: A separate class representing a background panel with a changing background.
Images and Sounds
The game includes various images and sounds stored in the "images" and "Sounds" directories.
Make sure the file paths in the code are correct or update them as needed.
