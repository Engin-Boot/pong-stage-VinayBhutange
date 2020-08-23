# New game

## Feature

Start a new game

## Acceptance Criteria

### Scenario: The player is freshly downloaded the game

  Given -The game is in working condition

  When -The user wants to play a new game as
  a new player.

  Then -Starts the fresh edition.

### Scenario: The player wants to close the loaded game

Given -The user must log in, so data can be update.

When -The user wants to start the fresh edition of game.

Then -get a confirmation from the user to reset and
start the game.
