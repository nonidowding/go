# How to Play/Part 2

It is no longer the rule that first capture wins the game. The new objective is to surround territory. A point of territory is an open intersection of the board surrounded by a single color of stones. 

### Life and Death

What do stones need to be unconditionally alive? In order to stay alive stones need open space. If they are surrounded and have no unoccupied intersections, they are captured. One space is not enough to stay alive. The white group can be surrounded around the outside and captured at "A". 

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/1171a853-7373-42a0-a302-f284e6f2aa46" />
</p>

What about two spaces? Well, there's a problem there too. If white plays in their own space, they are reduced to one space and can be captured. If black tries to capture white by placing a stone in the space, in either case of white or black playing at "B" white is still captured. If Black plays at "B" white is immediately captured. If white plays at "B", black is immediately captured, but white is reduced to one space again and can be captured back. 

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

So then try three spaces. With three spaces it matters who plays first. Starting with if white goes first...If white plays "A" or "C" they are reducing themselves to two spaces. We know how two spaces goes. What happens if White plays at B?

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/0cb74357-70db-47da-b60c-2bfdc1b1366c" />
</p>

<details>
  <summary>Answer</summary>
  If white plays at "B" there are two separate spaces in which black cannot play. The group is invincible. White no longer wants to play in their own area. Doing so would reduce white to one space and they would again be capturable.  

  <p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/1fa1d5ad-ed57-4ace-a047-c3496624e862" />
  </p>

</details>

What if black goes first? If black plays at "A" or "C", white plays at "B" capturing the black stone and the result is the same as if white had played first at "B". If black plays at "B" though, white is dead.

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/132bd048-c2ad-4e00-9007-abbecece8503" />
  </p>

White does not want to play "A" or "C", those moves reduce white to two spaces with a black stone already in one space. 

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/52956fd3-aa8d-4964-9da7-be86b9f3bfcd" />
  </p>

If black follows up on "B" with "A" or "C", either black plays next and immediately captures white, or white plays and captures black but is reduced to two spaces.

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/90632431-23c4-4006-9476-5fc7a1e1c370" />
</p>
