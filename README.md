Download Link: https://assignmentchef.com/product/solved-introduction-to-programming-languages-cecs130-lab-10
<br>
<strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Programming assignment (100 pts):</strong><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;"> In the C++ programming language write a program capable of playing </span><strong style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">3D</strong><span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;"> Tic-Tac-Toe against the user. Your program should use OOP concepts in its design. Use Inheritance to create a derived class from your Lab #9 Tic-Tac-Toe class. You can use ASCII art to generate and display the 3x3x3 playing board. The program should randomly decide who goes first computer or user. Your program should know and inform the user if an illegal move was made (cell already occupied). The program should also keep the score and announce if one of the players wins or if a draw is achieved. While it is desirable for your program to play a strong game, this is not an Artificial Intelligence course so if your program does not play at a world champion level you will not be penalized for it.</span>




The object of a 3D-TTT is to get as many 3-in-a-row as possible. You win just like in traditional TTT, except you can also win by getting 3-in-a-raw down each board. Imagine the boards as placed on top of each other.




Blank Board:

___|___|___

___|___|___

|     |

___|___|___

___|___|___

|     |

___|___|___

___|___|___

|     |




Game in Progress:




_x_|_0_|_0_

_x_|_x_|_x_

0 | 0  | x

_0_|___|___

___|_x_|___

|     |

___|___|___

___|_0_|_0__

|  x  |