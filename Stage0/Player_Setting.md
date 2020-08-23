# Players Setting

## Feature

- Single Player or Multi Player Game or Demo Game.

## Acceptance Criteria

### Scenario: Mode 1 of game

  Given: On start display single Player, Multi player and Demo mode is present.

  When: User clicks on 1 Player option.

  Then: Enter into single player mode of game.

### Scenario: Mode 2 of game

  Given: On start display 1 Player or Multi player and Demo mode is present.

  When: User clicks on 2 Player option.

  Then: Enter into 2 player mode of game.
  
### Scenario: Multi mode of game

  Given: On start display 1 Player or Multi player and Demo mode is present.

  When: User clicks on multi Player option (4 Player).

  Then: Enter into 4 player mode of game.
  
### Scenario: Initial modes of game

  Given: On start display 1 Player or 2 player and Demo mode is present.

  When: User does not clicks on 1 Player or 2 option till 10 sec.
  Or when user clicks on demo mode.

  Then: Show the demo of pong game.
