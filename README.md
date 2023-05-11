# BreakOut-Ball


This code is a Java program that creates a simple game called BreakOut Ball. It uses the Java Swing package to create a graphical user interface (GUI) and to render graphics. The game consists of a ball that bounces around the screen and breaks bricks when it hits them. The player controls a paddle at the bottom of the screen and must prevent the ball from falling off the bottom of the screen by bouncing it back up towards the bricks.

The program consists of two classes: `breakOutBall` and `GamePlay`. The `breakOutBall` class contains the main method, which creates an instance of the JFrame class and sets its properties. It also creates an instance of the `GamePlay` class and adds it to the JFrame.

The `GamePlay` class extends the `JPanel` class and implements the `ActionListener` and `KeyListener` interfaces. It contains all the game logic and rendering code. The `paint` method is used to draw the game objects on the screen, including the paddle, ball, bricks, score, and game over and win messages.

The `GamePlay` class also contains several instance variables that are used to keep track of the game state, such as the position and direction of the ball, the position of the paddle, the number of bricks remaining, and the score. It also contains a `javax.swing.Timer` object that controls the timing of the game and updates the screen at regular intervals.

Overall, this code provides a good starting point for creating a simple game using Java Swing.
