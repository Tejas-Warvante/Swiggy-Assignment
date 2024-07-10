# Swiggy-Assignment

## Classes

### Player

The `Player` class represents a player in the game with the following attributes:
- `health`: The health points of the player.
- `strength`: The defensive strength of the player.
- `attack`: The attack strength of the player.

Methods:
- `attack()`: Rolls a die to determine the attack roll.
- `defend()`: Rolls a die to determine the defense roll.
- `isAlive()`: Checks if the player is still alive.

### MagicalArena

The `MagicalArena` class handles the fighting logic between two players.

Methods:
- `rollDie()`: Simulates a dice roll.
- `fight()`: Executes the fight between the two players.
- `fightRound(Player attacker, Player defender)`: Handles a single round of fighting between two players.

## How to Run

1. Compile the Java files.
2. Run the `Main` class to see the fighting simulation.
3. Run the `MagicalArenaTest` class to execute the JUnit test.

## Testing

The project includes a JUnit test to verify the fight functionality. The test ensures that after a fight, at least one player is no longer alive.

To run the test, use your preferred IDE or command line tool to execute the `MagicalArenaTest` class.

## License

This project is open-source and free to use.
