# How to Play/Part 2

It is no longer the rule that first capture wins the game. In a full game of go the objective is to surround territory, more territory than your opponent. A point of territory is an open intersection of the board surrounded by a single color of stones. Here is a simple finished game. Black has 5 more points of territory than white. 

<p align="center">
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/dcd006d3-9d05-48b2-90a4-43ed6bc88304" />
</p>

But how do we know this game is finished? Couldn't white or black still be captured? Or could white build territory inside what appears to be black's space? To answer these questions it is important to understand how a group of stones is unconditionally alive.
  
### Life and Death

In order to stay alive stones need open space. If they are surrounded and have no unoccupied intersections, they are captured. One space is not enough to stay alive. The white group can be surrounded around the outside and captured at "A". 

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
  If white plays at "B" there are two separate spaces in which black cannot play. The group is invincible. White no longer wants to play in their own area. Doing so would reduce white to one space and they would again be capturable. As is, white has secured two points of territory.

  <p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/1fa1d5ad-ed57-4ace-a047-c3496624e862" />
  </p>

</details>

What if black goes first? If black plays at "A" or "C", white plays at "B" capturing the black stone and the result is the same as if white had played first at "B". If black plays at "B" though, white is dead.

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/132bd048-c2ad-4e00-9007-abbecece8503" />
  </p>

You can prove it to yourself because white does not want to play "A" or "C", those moves reduce white to two spaces with a black stone already in one space. 

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/52956fd3-aa8d-4964-9da7-be86b9f3bfcd" />
  </p>

If black follows up on "B" with "A" or "C", either black plays next and immediately captures white, or white plays and captures black but is reduced to two spaces.

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/90632431-23c4-4006-9476-5fc7a1e1c370" />
</p>

So we have found a number of spaces that offers *conditional* life. Let's keep going. 

Turns out, four spaces is the magic number. I'm not going to go over every case of black or white playing in each point "A"-"D". I leave that to the reader to investigate for themselves. The interesting points are "B" and "C". If white plays first in either of these points, they have two separate spaces connected to their group and it cannot be captured by black. The larger space can be reduced by black to 1 point. But That's ok, then white has two separate spaces in which it is illegal for black to play. 

<p align="center">
  <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/58771e8b-bf14-4b29-a726-960caabaf9c2" />
</p>

If black plays at "B" or "C", white simply plays the other point and it becomes the same senerio. It's OK for white to play second in the case of 4 spaces to secure life. In this way 4 spaces is unconditional life for white and can be left alone as open space without needing to explicitly play a stone to make two separate spaces. 

Technically, it is still conditional life though because white must respond if black plays in the space. If white doesn't respond they can be reduced and captured. This topic will be revisited in [How to Play/Part 3:Ko](text/how-to-play/part-3.md). 

Take note that these examples cover spaces *in a row*. In go, shape matters. Other formations of 4 spaces behave differently. 

<details>
  <summary>Extras</summary>
  Black to live. Where does black play to secure life in the corner? --- Answers purposely not provided. Puzzle over the possibilities!

  <p align="center">
    <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/0e0c44ea-f385-4161-9a5f-c6a929f32ae5" />
  </p>

  White to live. (1 move)
  
  <p align="center">
    <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/ce87b1d9-9400-4e3b-b840-e25477de85eb" />
  </p>

  Is black alive or dead? 

  <p align="center">
    <img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/e70c8426-6c3d-4391-8d71-a852dbf5397a" />
  </p>
  
</details>



