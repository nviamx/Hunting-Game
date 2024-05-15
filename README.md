# Hunting-Game

Hunting Game

Screen1:

It offers the player at least two options to choose a main character.
You can have two buttons with images on them showing the characters.
When the player clicks one of the buttons, Screen2 is called and you should send the chosen character as a start value. ( You can send 1 for character1 and 2 for character2) 
Feel free to make your own design. 

![image](https://github.com/nviamx/Hunting-Game/assets/119315159/e67a999d-3ca7-4f7e-ac46-6db6f5ea1de8)





Screen2:

This screen design is like the one you did in the previous phases of the huntingGame interface.
Score Labels, Canvas, imageSprites, balls, buttons for movement, and Clocks.

Your game should have the player as an imageSprite and another 2 moving objects (balls or image sprites as you want). One of these objects adds to your score, and the other lowers the score.
**This screen has two clocks, one for the time limit, and one for the random motion of the balls/imageSprites.**

When screen 2 is initialized:
-	Set the picture of your imageSprite player to the one chosen by the user. (hint: you will need to put an if/else here to compare the start value received)
-	Store the start value in a variable called character.
-	Reset the score. 
-	Limit the player with 20 seconds.

Build the movement blocks as in the previous phase. 
Build the random movement of the balls/imageSprite as in phase2. Make the timerInterval for their clock be 3 seconds.

Collisions:
Example:
If your player hits an apple, the score is incremented by one. 
If your player hits a spider, the score is decremented by one.
To code this, you need to use such code blocks:

![image](https://github.com/nviamx/Hunting-Game/assets/119315159/8d46cbe3-0811-4d5c-9939-1091c452c074)

When the time limit finishes, i.e after 20 seconds, you must check the score. 
If score is >=10 for example, open Screen4 and set the start value to the character variable you saved before.
Else, open Screen3 and send a start value of “repeat”.


![image](https://github.com/nviamx/Hunting-Game/assets/119315159/d19aa90b-63e5-46f2-ba9c-dde8a7103f68)





Screen3:

It should contain at least a label and a button.
The button text will be “Play Again”

When screen3 is initialized, 
-	Check the start value.
-	If start value = “repeat”
-	Display a hard luck message. 
-	If start value = “end”
-	Display a congratulations message. (end of game)

When the button is clicked,
-	If transfers the player to Screen1.


![image](https://github.com/nviamx/Hunting-Game/assets/119315159/557e970c-3320-44c6-9ac3-3381622716e3)




Screen4:

This screen is like screen2, however it is harder. 
It has two imageSprites/balls which decrements the score and one imageSprite/ball which increments the score. 

When the time limit finishes, i.e after 20 seconds, you must check the score. 
If score is >=10 for example, open Screen3 and send a start value of “end”.
Else, open Screen3 and send a start value of “repeat”.


![image](https://github.com/nviamx/Hunting-Game/assets/119315159/5351e5d6-1e74-4951-ad9f-1d4e855d8cb5)


