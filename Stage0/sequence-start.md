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

Then: display feature change pannel.
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

-describe-how-modules-interact-to-make-the-ball-move

## One score

-describe-how-the-modules-interact-to-record-scores
