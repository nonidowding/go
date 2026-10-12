# How to Play/Part 2

It is no longer the rule that first capture wins the game. The new objective is to surround territory. A point of territory is an open intersection of the board surrounded by a single color of stones. 

### Life and Death

What do stones need to be unconditionally alive? In order to stay alive stones need open space. If they are surrounded and have no unoccupied intersections, they are captured. One space is not enough to stay alive. The white group can be surrounded around the outside and captured at "A". 

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/1171a853-7373-42a0-a302-f284e6f2aa46" />
</p>

What about two spaces? Well, there's a problem there too. If black tries to capture white by placing a stone in the space, if either white or black play at "B" white is still captured. If Black plays at "B" white is immediately captured. If white plays at "B", black is immediately captured, but white is reduced to one space again and can be captured back. 

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/1bde1ecd-b7de-4403-8a38-baa3d8cfcc58" />
</p>

<details>
  <summary>Black plays at "B"</summary>
  White is captured. 

  <p align="center">
    <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/a9c10723-ae9d-42a0-989d-705a01bcd2dc" />
  </p>
  
</details>

<details>
  <summary>White plays at "B"</summary>
  Black is captured. White can now be captured back if black plays at "A".
  
  <p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/1128dae5-8c43-4607-ae49-d835e4cc1d7c" />
  </p>
  
</details>



