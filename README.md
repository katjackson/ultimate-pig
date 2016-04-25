### Pig Solitaire Simulation

In my class Player I created a die-rolling method, a turn-taking method, and a method to decide whether to roll again. The default method for the class Player is to only roll once every turn. Hans Solo is the player that plays as an instance of this class.

##### Safe Sam
Safe Sam is a player in the class Safe, which inherits from the Player class. Sam holds if his score on that turn is greater than 4. He doesn't ever finish a game with a score of zero, but 10,000 games, his highest score is never over 50.

##### Risky Chick
Risky Chick is a player in the class Risky, which inherits from the Player class. Chick does not hold until she gets 35 points on a single turn. While she achieves the highest scores of any player, her game end in a zero about 22.5% of the time.

##### Tony
Tony is a player in the class RollsFourTimes, which inherits from the Player class. Tony always attempts to roll the die 4 times. He does pretty well.

##### Tammy
Tammy is a player in the class RollsToTwenty, which inherits from the Player class. Tammy doesn't hold unless she has achieved 20 points in a turn. She is the best player I have, but I'm not sure if she's really all that good.

##### Tommi
Tommi is a player in the class TheThinker, which inherits from the Player class. Tommi uses the strategies of Tony and Tammy. She holds when either condition is met. She does pretty well.

Use [this link](https://github.com/katjackson/ultimate-pig/blob/master/ultimate_pig.ipynb) to view the jupyter notebook and inline plots.
