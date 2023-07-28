# Simplified_TTT

This TIC_TAC_TOE game is made on LogiSim Software.

You can install Logisim from https://sourceforge.net/projects/circuit/ (latest version is recommended)

Preview:
<img width="1440" alt="Screenshot 2023-07-28 at 19 12 39" src="https://github.com/akash26khanra/Simplified_TTT/assets/73026641/258d0a40-f0f9-40c1-86b6-820b29298fc4">

To understand the implementation, refer the FSM_States 

State 0 - Idle

State 1 - P1

State 2 - P2

State 3 - Game Over


A player wins the game when successfully placing three similar (01-Xs) or (10-Os) values in the following row pairs: (1,2,3); (4,5,6);(7,8,9); (1,4,7); (2,5,8);(3,6,9); (1,5,9);(3,5,7).
The winner detecting circuit is designed to find the winner when the above winning rule is matched. 

To detect an illegal move, a comparator is needed to check if the current position was already played by either the computer or player. 
Moreover, “No space” detector is to check if all the positions are played and no winner is found.
