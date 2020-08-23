# Interaction Sequences

## Startup Sequence

### Scenario: At the start of game

Given: player mode.

When: Game starts display player selection mode.

Then: select single player mode or multi player mode.

When: single player.

Then: display game mode.

When: Beginner mode selects.

Then: by displaying instructions of single player from player control.
Starts the game.

When: expert mode selects.

Then: display feature change panel.
And change the features. And save the updated features.
And starts the game in expert mode.

When: Multi player mode.

Then: display game mode panel.

When: selects beginner mode.

Then: by displaying instructions of multi player from player control.
Starts the game.

When: expert mode selects.

Then: display feature change panel.
And change the features. And save the updated features.
And starts the game in expert mode.

## Movement Initiation

### Scenario: Single player game

Given: At start from middle ball moves towrds right. (Player 1).

When: ball touches to player 1's paddle.

Then: ball will bounce back towards the computer's paddle.

When: Player 1 misses the ball.

Then: opponent (computer) will get 1 point. 
And from next turn, ball moves towards left side first.

When: computer misses ball.

Then: player 1 will get 1 point. 
And from next turn, ball moves towards right side first.

When: ball touches to computer's paddle.

Then: ball bounce back towards opponent.

### Scenario: Multiplayer game

Given: At starts ball moves towards right.

When: ball touches to rights side player's paddle.

Then: it will bounce back towards left side.

When: ball misses right side player's paddle.

Then: All other opponent will get 1 point.

When: left side player misses the ball.

Then: all other player, except the one who misses ball.
Will get 1 point.

## One score

### Scenario: Scoring the point

Given: 10 points require for __WINING__ the game.

When: any of the player scores 10 points first.

Then: that player will be our winner of __PONG GAME__.
