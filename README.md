# COMP55-Fork
groupproject-team-6-alphapro created by GitHub Classroom

The new feature I am adding will be functions that detect all the legal moves, count the total moves, 
ramdom generate a number within that range, then do the picked move. 

pseudocode:
create globle variable that count the total moves and set it to zero.

Need a findMoves functiuon that able to figure out all the legal moves.
legal moves means:
  -moving a piece that don't violates the movement rules for each piece
  -moving a piece that woundn't make the king into a checking situation
  -moving pieces that must stop a check when the king is in a checking situation
  -when moving a king that may not move into any space right besides the oppoent king
  -only castle when:
    -there is no piece between the king and the rook
    -king and the rook never moved before
    -king is not in a checking situation
    -king will not be check after castle

A function that increase the globle variable by 1 per each moves when running the findMove funciton.

Random number generater a number from 1 to the total moves

A selected move function taht runs the findMove function and return the detemine random number move and reset the globle variable back to 0.


Added new code to the main file. I can not test it out but what should be happen is having a new signle player mode. 
Oppoent will do moves after player moved. This was very stressful because I am not very good at Java and all the pieces funciton are coded by my teammates. 
If the project for this assignemnt is not COMP55 project, I think I can actually do a great job. 
