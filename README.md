# 2-player-Carrom
/****** Version V1.0 Basic 2player Carrom game ******/

//to play game execute command 'make ; ./carrom' from bash

Controls::

1:) Keyboard

    a)Up and down arrow keys are used to decrease or increase the power of strike;
    b)Left and right arrow keys are used to move the striker left and right direction;
    c)'a' and 'c' arrow keys are use to change the direction of strike a--> anticlockwise c--> clockwise;
    d)Spacebar to strike the striker;

2:) Mouse
	
    a)Hold the scroll botton(mouse middle button) and move mouse up and down to change the power of strike;
    b)Hold the right key and move mouse left and right to move the Striker;
    c)Left click on desired position to strike the striker;

3:) Scoring

    a)Scoreboard of both the player starts with 100(so as make scores more realistic) on initialising the game;
    b)Every second elapsed by the player to strike decrement the score by one;
    c)Black arrow is displayed for player who is aiming to pot black coins and white arrow is displayed for one with white;
    d)A coin pocketed by player of his color will fetch him 10pts and of opposite color will cost -5pts;
    e)Queen will fetch 20pts for any player who pockets it first;
    f)Player with higher score at the end will win the game;

    
thats it!! let the gaming glBegin() :p
