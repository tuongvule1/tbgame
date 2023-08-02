# tbgame
A simple survival game. Try it at [tuongvule1.github.io/tbgame](https://tuongvule1.github.io/tbgame/). 

You are the red square. The black squares are zombies. Avoid them, moving using the four up, down, left, right buttons. If you run into them, or they run into you, you die and the game ends.  
Don't worry, you also have some weapons to fight the zombies - see Weapon sections. Becareful of the table edge - if you go out of the table, you die.  
When you die, you will know how long you've survived, in seconds. This is your score.
# Zombies
Every second, the zombies move. A new zombie is also spawn every second.  
Newly spawn zombie are blue and can't hurt you, but once they moved, they turn black and can hurt you.  
Every $45$ seconds, a zombie wave occurs. The number of zombies on the screen double, meaning $n$ zombies would be spawn simutanenuously where $n$ is the number of current zombie. Note that the current number of zombies is displayed on the top.
# Weapons
* Bomb
  * Press Enter to activate. This will kills all zombies in the $5\times5$ square in which you are the center.
  * You need to wait $18$ seconds before you can use the bomb again - the cooldown time remaining can be seen on the top left corner.
* Gun
  * Press Ctrl to activate. This will kills all zombies in the same row and column with you.
  * You need to wait $20$ seconds before you can use the gun again - the cooldown time remaining can be seen on the top left corner.
* Fireshield
  * Press Space to activate. This will gives a shield - which last for $10$ seconds - that allows you to kill zombies when you hit them (as opposed to you being killed by them without the shield).
  * When activated, your color will change to yellow. You can see how many seconds you have left before the shield ends on the top left corner.
  * After the shield ends, you need to wait $22$ seconds before you can use the gun again - the cooldown time remaining can be seen on the top left corner.
* Hiremen
  * Every time a zombie dies, you gain a coin. The number of coins you have is displayed on the top
  * Press Shift hire a zombie killer for $15$ coins. They are in green. Note that they usually kill zombies - but sometime they could be killed by zombies.
