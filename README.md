Updated comment 2.0 = code updates:

-In this new updated code, I followed the teacher suggestion and the project requirement by adding the feature to Save and Load the game.
-Added a feature where the user is asked if he wants to proceed or end the game after each round of play. Previously the user would play until his balance had to reach 0€.
-Reduced the amount of symbols to higher the chances of win conditions.
-Considering that win conditions = 3 same symbols, removed the possibility for the user to place a bet only on 1 column.
-When the user balance reaches 0, added the possibility for the user to chose if he wants to quit playing, or play again and be redirected to the deposit screen.




UPDATED - Own comment:

- I had already sent the exercise and after following the comment of the teacher, I reviewed and updated the code:

a) I removed the global variable, which in 99% of the cases I learned could result in a problem. 

b) Fixed my code where when the player would decide to review his choices (step 4) his balance would be reduced to 0.

c) Cleaned overall my code and tried to make it look much nicer to the eye.

d) Fixed my mistake where I had previously confused rows and columns, making the whole code look much more confusing than it actually was.





Project Description: 

For this task, I decided to create a game.
This idea originated immediatly after our first exercise where we had to create a rock-paper-scissor game. To me this was a fairly simple but at the same time complete project.
I believe I put to good use the lessons and new things that I learned throughout the course.

The game itself is a simple betting game:


1- The user is first asked for instructions to input the amount of money they would like to deposit. In the code, I made sure that the max amount is 100 € and the minimum is more than 0€.

2- After inputing the deposit, the user is asked the amount of columns in which he wants to place his bet. In the code, the amount of columns is a variable and can be easily changed from the very begining.

3- After deciding in how many columns will the bet be placed, the user is asked how much from his previously placed deposit he wants to bet. He can only bet from what he has deposited.
If the amount is 0, the user is asked again a number. If the amount is bigger than the deposit, the user is given the difference missing to what he wants to bet.

4- In the fourth stage the user is showed his previous choices, the amount of money at his disposition and requested to confirm. 
The game continues if the user decides to press Yes, otherwise the user is redirected to the first choice screen.

5- In the fifth stage, the program choses for each column, a different fruit symbols (symbols which were previously written in a list). If the user has at least three of the same symbols, then the user wins and the amount is added to the user’s total balance.
Otherwise, the amount is substracted.

6- The loop continues until the player’s balance ends.


-I am aware of different things that can be improved in the code. Acording to my math, the potential percentage that the player wins should be around 2-3%.
I am not familiar with slot machines so I am not aware if this percentage should be much lower or much higher. To me it was important that the code behind it worked as it should.


In this project I wanted to avoid using external help and only do it by using what I learned in this course. I am excited to hear your feedback about things that could still be changed and/or improved.

Thank you!
