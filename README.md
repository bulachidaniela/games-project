To run the program, first, ensure Python is installed on your system. Then, open your
terminal or command prompt and run pip install simplegui to install the required library.
Also, download all the necessary images for the game.
Use a code editor like PyCharm or VSCode (instead of CodeSkulptor, which makes
importing images inconvenient). These editors make it easier to work with sprite sheets
(.png) and animations, improving the look of the game.After setting up the code in your editor, run the game by typing python3 game.py in the
terminal or clicking the "Run" button. A window will appear, and the game will start!![PHOTO-2025-03-29-20-41-21](https://github.com/user-attachments/assets/04f764af-7149-42be-8fe0-fd19b546d845) You’re first presented with a welcome screen, where you will see three buttons. The
first button, "Start," will begin the game. The second button, "Help," provides
instructions and information about how to play the game. Lastly, the "Exit" button
allows you to stop the game and close the window.Your player controls a red ship,
which can be moved up, down, left, and right. Enemies, represented by violet ships of
three different sizes, will appear on the screen. Depending on their size, the enemies
may shoot and move at varying speeds—small ships are slower, while larger ones are
faster and more aggressive.
In the game, power-ups offer the player various advantages. The Fire Rate power-up
(light blue) increases shooting speed by reducing the time between shots for a period of
360 frames (approximately 360 seconds). The Shield power-up (blue accent) provides
temporary protection, preventing health loss from enemy bullets for 360 frames until it
expires. The Health power-up (red) increases the player's lives by one. Each power-up
appears in its respective color, and when collected, it activates the corresponding
effect, helping the player progress and survive longer in the game.In the top left corner of the screen, you will see a lives bar, which starts at 3, a score
counter starting at 0, and the level indicator starting at 1. The score increases by one for
each small enemy defeated, by two for each medium enemy and by three for big
enemy.
To control your player, use the arrow keys to move the red ship in the direction of the
pressed key. To defeat enemies, press the "space" key to shoot. If you run out of lives,
meaning you were shot by an enemy, collided with them, or allowed them to cross the
screen, the game will end, and you will be presented with the game over screen.
