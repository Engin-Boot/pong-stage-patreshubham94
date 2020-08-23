# Players Setting

## Feature

- Single Player or Two Game or Demo Game.

## Acceptance Criteria

### Scenario: Mode 1 of game

  Given: On start display 1 Player or 2 player and Demo mode is present.

  When: User clicks on 1 Player option.

  Then: Enter to single player mode of game.

### Scenario: Mode 2 of game

  Given: On start display 1 Player or 2 player and Demo mode is present.

  When: User clicks on 2 Player option.

  Then: Enter to 2 player mode of game.
  
### Scenario: Initial modes of game

  Given: On start display 1 Player or 2 player and Demo mode is present.

  When: User does not clicks on 1 Player or 2 option till 10 sec.
  Or when user clicks on demo mode.

  Then: Show the demo of pong game.
