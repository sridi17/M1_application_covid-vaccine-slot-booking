# M1_game_snake game project

# REQUIREMENTS #

# INTRODUCTION #
This Mini Project in C Snake Game is a simple console application without graphics. In this project, you can play the popular “Snake Game” just like you played it elsewhere. You have to use the up, down, right or left arrows to move the snake. Foods are provided at the several co-ordinates of the screen for the snake to eat. Every time the snake eats the food, its length will by increased by one element along with the score. The source code for Snake Game in C is complete and totally error-free. It is compiled in Code::blocks using the gcc compiler. The code is about 550 lines; so I haven’t displayed the source code here. You can directly download the source code plus application file from the link below.


# . Folder Structure #
# . Folder Description #
# 1 - Requirements Documents detailing requirements and research. #
# 2 - Design Documents specifying design details. #
# 3 - Implementation All code and documentation. #
# 4 - Test_plan Documents with test plans and procedures. #

# SWOT ANALYSIS 3
# STRENGTH #
- it is fun type game the aim of it is snake should hunt the food
- it helps the player to relieve stress.
- the game helps to improve concentrating skills.
# WEAKNESS #
- the game is addictive
# OPPORTUNITY #
- it can be accesed in offline
# THREAT #
- game can be crashed due to technical error
# 4 W'S and 1H #
# WHO #
- anyone can play this snake game

# WHAT #
- it is a game played by single player

# WHEN #
- whenever the player wants to play to increase their fun.

# HOW #
- this project is implemented by using loops,function call and other functionalities of c.

# TOOLS #
- VS code with some c/c++ extensions


# FUNCTIONALITIES OF SNAKE GAME #
-	snake is represented with a 0(zero) symbol.
-	The fruit is represented with an *(asterisk) symbol.
-	The The snake can move in any direction according to the user with the help of the keyboard (W, A, S, D keys).
-	When the snake eats a fruit the score will increase by 10 points.
-	The fruit will generate automatically within the boundaries.
-	Whenever the snake will touch the boundary the game is over.

# STEPS TO CREATE SNAKE GAME #
-	There will be four user-defined functions.
-	Build a boundary within which the game will be played.
-	The fruits are generated randomly.
-	Then increase the score whenever the snake eats a fruit.
# The user-defined functions created in this program are given below: #
-	Draw(): This function creates the boundary in which the game will be played.
-	Setup(): This function will set the position of the fruit within the boundary.
-	Input(): This function will take the input from the keyboard.
-	Logic(): This function will set the movement of the snake.
# Built-in functions used: #
-	kbhit(): This function in C is used to determine if a key has been pressed or not. To use this function in a program include the header file conio.h. If a key has been pressed, then it returns a non-zero value otherwise it returns zero.
-	rand(): The rand() function is declared in stdlib.h. It returns a random integer value every time it is called.
Header files and variables:
-	The header files and variables used in this program are:


![]![● #include _conio h_ • Untitled-1 - Visual Studio Code 23-11-2021 16_32_34 (2)](https://user-images.githubusercontent.com/94300992/143013342-5931b9d2-e5e2-42b9-95dc-a16fcc072a77.png)


-	Here include the <unistd.h> header file for the sleep() function.
- Draw(): This function is responsible to build the boundary within which the game will be played.
Below is the C program to build the outline boundary using draw():
- setup():nThisbfunction is used to write the code to generate the fruit within the boundary using rand() function.
- Using rand()%20 because the size of the boundary is length = 20 and width = 20 so the fruit will generate within the boundary
 
 
 
 ![● #include _conio h_ • Untitled-1 - Visual Studio Code 23-11-2021 16_43_10 (2)](https://user-images.githubusercontent.com/94300992/143014734-e7f258da-bba9-4cc0-b2e0-de7ec7fbe060.png)



![]

- Input(): In this function, the programmer writes the code to take the input from the keyboard (W, A, S, D, X keys).





![]![● #include _conio h_ • Untitled-1 - Visual Studio Code 23-11-2021 16_49_59 (2)](https://user-images.githubusercontent.com/94300992/143015572-3ce0c671-46f5-43e5-aec7-a26171725c06.png)


- logic(): Here, write all the logic for this program like for the movement of the snake, for increasing the score, when the snake will touch the boundary the game will be over, to exit the game and the random generation of the fruit once the snake will eat the fruit.





![]![● Untitled-1 - Visual Studio Code 23-11-2021 16_55_08 (2)](https://user-images.githubusercontent.com/94300992/143016419-899a0b46-ade9-4d62-b9ae-4514cfe9fdb0.png)









- sleep(): This function in C is a function that delays the program execution for the given number of seconds. In this code sleep() is used to slow down the movement of the snake so it will be easy for the user to play.
- main(): From the main() function the execution of the program starts. It calls all the functions.




![]![● Untitled-1 - Visual Studio Code 23-11-2021 17_00_51 (2)](https://user-images.githubusercontent.com/94300992/143017046-b7f62195-8d40-4971-b681-7c2cd8eabba5.png)







# DESIGN #
# BEHAVIOUR DIAGRAM
# STRUCTURAL DIAGRAM


![]![BEHAVIOUR FLOW](https://user-images.githubusercontent.com/94300992/143017435-89db5cf9-8825-432c-a5e2-9dd5a95e8b44.png)




























![]![DIVYA ](https://user-images.githubusercontent.com/94300992/143017509-f0a99f16-99fd-4676-a86c-c4a3a1e7dacd.png)
