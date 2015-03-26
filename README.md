##Installation:
Make sure Pygame is installed in your machine.
Run this command under a command prompt:
```python
	python pong.py
```

##Goal of the game:
The goal of the game is to not let the ball touch your side of the "court."
To accomplish this, you must move your platform so the ball can bounce off of it and move direction. The ball will progressively get faster overtime a player hits it.

In two player mode, you will simply play against each other in an effort to	have the other player lose.

In one player mode, you will strive to get the highest score possible. 
Through out the game a boss will appear as your score gets higher. He will eventually start shooting fireballs at you and if any of them touch you then the game ends.

##Controls:
###One player mode:
Player 1:

	Move up: Up key

	Move down: Down key

###Two Player mode:
For Player 1 (Left):

	Move Up: W

	Move Down: S

For Player 2 (Right):

	Move Up: Up key

	Move Down: Down key

##Methods:
The ball object isn't allowed to move outside the working window. It will change directions whenever it collides with either the floor or ceiling, or one of the players. Every time it hits something it will play a sound. The ball has an incrementing left and right speed that will keep incrementing every time it collides with a player. The up down speed will be determined by where it collides with the player. The farther to the edges, the faster the up/down speed will be making it harder for the opposing player to bounce the ball back.

For one player mode, the boss created becomes alive whenever the score reaches a certain threshold. The highscore is pickled in order to save the highest previous score. The fireballs that the boss fires are fired randomly and get fired more frequently as your score goes up.

##Copyright:
All sounds and images were created by Erick Franco.