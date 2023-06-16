# Snake-Game-In-Assembly-Language
Introduction:
Snake game is one of the most popular computer games and has been around since the earlier days of computing. In addition, this game is revived in recent times through mobile phone applications. This simple yet interesting games drives the interest of the user through, asking the name of the snake, and then using that as the snake’s body.

Abstract:
The games ask the name of the snake and then the desired level, on which the user wants to play. The snake moves between walls, and some food and bomb randomly pop up. When contacting with the food, the score and length increases, and when the snake touches the bomb, or a wall, or its body it dies. Then it asks if the user wants to try again or exit. After exiting, the name and score are then saves in a file.

Methodology:
First the display screen comes which asks the snake’s name, this name is then used as the body of the snake. Then the level is asked, Level 1 is slow, Level 2 is medium, Level 3 is fast. In the next screen, snake name, level, and score are displayed on top, a few co-ordinates down the snake moves between 4 walls. The snakes moves with W, A, S, D keys and P is a cheat code to pause the game. The snakes body moves forward while deleting the previous parts of its body, so it doesn’t drag the snake, like a pen writing something. A special feature is that the snake can move overwrite itself. Which means if it’s going forward, it can move back as well, without turning left or right. Food is randomly generated, using randomize function, inside the co-ordinates of the wall.  Similarly, bomb is also created. When the snake’s body touches the food, the score updates, and the next character in the string of snake’s names adds to the snake’s body. When the snake touches the bomb, YouDied function is called which kills the snake, as it does when it touches any wall, or its body. When the user dies, it asks to enter 1, if the user wants to try again or press 0 to exit the game. Pressing 1 reiterates the whole game. Pressing 0 exits the program.

RESULTS:
Green diamond -> Food
Oval character -> Bomb

![image](https://github.com/HairamNaseem/Snake-Game-In-Assembly-Language/assets/123382738/049a5fbd-c524-4071-9500-2a2a61ff554e)

![image](https://github.com/HairamNaseem/Snake-Game-In-Assembly-Language/assets/123382738/6bed1d3f-d557-4c05-ba76-ebac535930a2)

![image](https://github.com/HairamNaseem/Snake-Game-In-Assembly-Language/assets/123382738/cc8187e4-05a7-45cc-95ca-17bcf64813c1)

Conclusion:
The snake game can be very fun to play. This game was created using many user-defined procedures, labels. 
