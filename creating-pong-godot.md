# Creating Pong in Godot 

#gamedev #godot

This is a part of my [20 Games Challenge](20-games-challenge.md).

### Goals:

- [x] Create an arena with two walls and a divider.
- [x] Add a paddle on either end of the play field. Use player inputs to move the paddles up and down.
- [x] Add a ball that moves around the playfield and bounces off of the paddles and walls.
- [x] Detect when the ball leaves the play-field. Assign a point to the player who scored.
- [x] Track and display the score for each player.

### Stretch goals:

- [ ] Write an AI script that can follow the ball so you can play with only one player.  
	- Hint: Following the ball with a paddle is easy, but it makes the opponent impossible to beat. You might want to make the AI less than perfect somehow.
- [ ] Add a menu.
	- [ ] Start Game
	- [ ] Options
		- [ ] Audio settings
		- [ ] Speed modifier
- [x] Add some basic sounds. Play a sound every time the ball collides with something, and every time a player scores.
- [ ] Mobile support
	- [ ] Touch input support

### Lessons learned

- [Bouncing Objects](bouncing-object-godot.md)
- [Viewport Scaling](viewport-scaling-godot.md)
- [Touch Input](touch-input-godot.md)
- [Web Build CI](godot-4-web-build-github-actions.md)