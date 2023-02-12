# AI-Robot-Bull-Game
bull is running loose in the above square corral. The robotic rodeo bullfighter is meant to pen the bull, by getting
it to chase them, and leading it to the square x so that it can be closed in. The rules are these:
•The bull can only move up/down/left/right (limited by the walls/obstacles).
•The robot can move in any of the eight immediate neighboring directions (limited by the walls/obstacles).
•Each round, the robot moves, then the bull moves.
•If the robot is outside the 5x5 square surrounding the bull, the bull moves uniformly at random in its available
directions.
•If the robot is within the 5x5 square surrounding the bull, the bull will charge with equal probability in any
direction that doesn’t take it farther (manhattan distance) from the robot.
•The bull cannot enter the same square as the robot, and vice versa. The bull will skip moving if it has to. (Shy
bull.)
•The game is over when the bull walks onto the x.
