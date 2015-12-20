How to Execute ?

Double click on the index.html and the game will be opened in a browser.

The game is slow as I have included logic for random movements of creatures when the qbert character is static as well. If you want to make it fast, then please comment 558 line code in index.html

Description:
This Game is similar to Qbert game where Yellow colored cube represents the qbert character and blue cube represents the creature1, green cube represents creature2 and red cube represents creature2.

Creature1 comes in only after 3 seconds of the game is started, creature2 comes in after five seconds of game is started and creature3 comes in after seven seconds of game is started.

Whenever Qbert character(Yellow colored cube) collides with any of the creatures(blue,green or red) or 
if Qbert character is in the left most line and if left arrow key is pressed or 
if the Qbert character is Right most line and upward arrow is pressed or 
if Qbert character is in Bottow level and if bottom key is pressed or 
if Qbert character is at the top position and if upward key is pressed or
if Qbert character is at the bottom right corner and if upward or right key is pressed or
if Qbert character is at the bottom left corner and if downward key or leftward key is pressed then Qbert character life will be reduced by 1 and it starts from Top position of gameboard.

Top face of the cubes in a gameboard color changes to yellow as the qbert moves across the cubes.

If the qbert character tuches topfaces of all cubes in a gameboard then game will be over and player is won.

If the lives become 0 in the middle of the game then game will be over.



Youtube screencast Link:
https://www.youtube.com/watch?v=61LIpPJ16x0


Extra Credit:

I have included Multiple lives part
I have also included scores display part

Citations:

Below are the sources from which I used the code for this assignment

Lesson4 and lesson 6 in : https://github.com/gpjt/webgl-lessons

For handling Transformation logic: http://stackoverflow.com/questions/5597060/detecting-arrow-key-presses-in-javascript

For handling Heyup and Keydown events : http://stackoverflow.com/questions/15258584/jquery-call-event-on-keydown-or-keyup

I have referred logics for Keypress events from Amritanshu Agarwal.

