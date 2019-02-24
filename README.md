# Snakes_Ladders_problem
Feature1

As I wasn't asked to implement any graphical user inerface, I only implemented simple code behind, which would be executed if there was any interface.

The implementation has few points to be considered:

- Where is the token when the game will start?
In this scenario as I only implemented feature1, int n can represent square 1 in this situation.

-Rolling the dice.
Simple random faunction would generate random number between 1 and 6 to represent player rolling the dice.

-Token needs to move based on dice result, so random number would be added to current square and token would move accordingly.

-Check if player won.
Simple loop can check if dice value added to square would make it 100 or greater. If current square value equals 100, then the player would be winner, if he's the first player who reaches 100th square. Or if value is greater than 100, the value stays the same, leaving player in the same square Instead if loop switch statement could be possibly used.

For future implemention with GUI, these functions would run OnButtonClickEvent. Also squares with snakes and ladders should be considered for future, these should be pointing to squares where snakes or ladders points the player. Also some variable could represent players, who finishes the game. When 100th square would be reached, the variables value would increase by logging that the player finished the game and if it's the first time when it increases, means the player won.
