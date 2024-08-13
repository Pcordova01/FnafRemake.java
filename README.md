# Fnaf_Remake
This project is my simplified, and altered version of the popular survival horror game, Five Nights at Freddys. In my simplified command-line version, the game begins by telling the player that the animitronic (Freddy) is behind a set of doors. The game begins at 12AM and each guess the player attempts will make time pass by one hour, as such, the player only has until 6AM to find Freddy or else Freddy will come out the door, attack the player, and end the game. Additionally, the night begins with giving the player 100% power; when the player uses a guess, a random amount of power is drained. If the player ever loses all their power, all the doors open, and Freddy ends the game. The number of doors, as well as the range of numbers to which how much power is drained from the player after each guess, is dependent upon which mode they are playing. Easy mode gives the player 5 doors, and drains between 15% and 30% power, while hard mode gives the player 8 doors and drains between 20% and 35% power. 

## Takeaways
Creating this game helped to understand the importance of making a challenging, yet approachable game design; as the player is given useful information that helps them assertain what their next choice should be based on their current circumstances. Additionally, I enjoyed practicing the skill of using random number generators to give a game a sense of opposition- the random numbers in this program make the player feel as if they are are competing against another thinking player. 

## Features
- Two Difficulty Modes: Easy mode and Hard mode
- Randomized ai moves
- Simple and clear gameplay
- Main menu functionality


## Winning Example
12 A.M.<br>
Power left: 100<br>
Enter a door number to check for Freddy (1-5): 2<br>

Freddy was not behind door 2.<br>

1 A.M.<br>
Power left: 85<br>
Enter a door number to check for Freddy (1-5): 4<br>

Freddy was not behind door 4.<br>

2 A.M.<br>
Power left: 70<br>
Enter a door number to check for Freddy (1-5): 1<br>

Freddy was not behind door 1.<br>

3 A.M.<br>
Power left: 55<br>
Enter a door number to check for Freddy (1-5): 5<br>

Freddy was not behind door 5.<br>

4 A.M.<br>
Power left: 40<br>
Enter a door number to check for Freddy (1-5): 3<br>

You found Freddy!! He was behind door 3. You survived!<br>
Congratulations! You've made it through the night.<br>
Entering main menu...<br>


## Losing Example
12 A.M.<br>
Power left: 100<br>
Enter a door number to check for Freddy (1-5): 1<br>

Freddy was not behind door 1.<br>

1 A.M.<br>
Power left: 85<br>
Enter a door number to check for Freddy (1-5): 2<br>

Freddy was not behind door 2.<br>

2 A.M.<br>
Power left: 70<br>
Enter a door number to check for Freddy (1-5): 3<br>

Freddy was not behind door 3.<br>

3 A.M.<br>
Power left: 55<br>
Enter a door number to check for Freddy (1-5): 4<br>

Freddy was not behind door 4.<br>

4 A.M.<br>
Power left: 40<br>
Enter a door number to check for Freddy (1-5): 5<br>

Freddy was not behind door 5.<br>

5 A.M.<br>
Power left: 25<br>
Enter a door number to check for Freddy (1-5): 1<br>

Freddy was not behind door 1.<br>

5 A.M.<br>
Power left: 10<br>
Enter a door number to check for Freddy (1-5): 2<br>

You've run out of power!! Freddy has come out door 3 and killed you. Better luck next time! :)<br>
Entering main menu...<br>

