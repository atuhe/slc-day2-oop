# memory_game
# In terminal, run(python3 memory_game.py)
#Windows OS run this command (python memory_game.py)

The memory game generates a 2D array of alphabets randomly in form of a (6*6) matrix. 
A user is required to memorise figures in the alphabet matrix  and pick similar alphabet letters e.g AAA, EE etc.
In the grid((6*6 arrray of randomly generated numbers) and print out their positions in form of co-ordinates

Examlple.
Look through the grid and check for any letter, lets say A, and find its match.
You are required to memorise the positions of all letter A's inorder to accumulate more points.
A(4,5)__in form of a row by column.
A(5,3)
A(6,5)
************************
EXample for E.
------------------On this co-ordinate you will find Letter E---------------------------------------
E(1,6)
E(6,6)
**********************
Note: do not include the brackets when you are inputting the co-ordinate values
DO NOT E(1,6)
DO 1,6 for 
*********************************
1 | M  N  U  O  P  E | 1
2 | U  J  S  A  H  C | 2
3 | B  R  J  I  T  L | 3
4 | E  H  M  C  K  N | 4
5 | S  Q  A  F  M  R | 5
6 | D  B  M  O  A  E | 6
********************************************
Then, after some time the above grid dissappears and you are required to memorise the position of the matching  
alphabet letters.
************************************************
*********This grid helps you to memorise************
1 | ****** | 1
2 | ****** | 2
3 | ****** | 3
4 | ****** | 4
5 | ****** | 5
6 | ****** | 6
***************************************************
First co-ordinate e.g  as the first Option and
Second co-ordinate of the very letter as the second option
******************This is the score for letter E's*********************

Enter Coordinate Values (First Option): 1,6
Enter Coordinate Values (Second Match): 6,6
You have accumulated: (4) points and unlocked: (4) keys.

**************************This is the score for letter A's*************************************

Enter Coordinate Values (First Option): 5,3
Enter Coordinate Values (Second Match): 6,5
You have accumulated: (2) points and unlocked: (2) keys.

Enter Coordinate Values (First Option): 4,1
Enter Coordinate Values (Second Match): 6,6
You have accumulated: (6) points and unlocked: (6) keys.

Enter Coordinate Values (First Option): 4,1
Enter Coordinate Values (Second Match): 1,6
You have accumulated: (8) points and unlocked: (8) keys.

Enter Coordinate Values (First Option): 4,5
Enter Coordinate Values (Second Match): 6,6
You have accumulated: (10) points and unlocked: (10) keys.

Enter Coordinate Values (First Option): 1,6
Enter Coordinate Values (Second Match): 6,6
You have accumulated: (12) points and unlocked: (12) keys.
