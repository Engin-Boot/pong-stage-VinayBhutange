# Account

## Feature

Players' account for tracking performance.

## Acceptance Criteria

### Scenario: User has already account

Given -Player has logged in.

When -Player enters into the account section.

Then -Show his account details.

### Scenario: User does not have account

Given -Game is working fine.

When -User never logged into the game, he is a new player.

Then -Ask user to SignUp.

### Scenario: User has account but currently the user has logged out

Given -Working internet connection.

When -user wants to get access to his/her account.

Then -allow user to login to his/her account.
