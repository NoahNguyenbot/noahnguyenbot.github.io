---
layout: project
type: project
image: img/tictactoe/tictac.webp
title: "Tic-Tac-Toe"
date: 2024
published: true
labels:
  - Java
summary: "A Tic-Tac-Toe game I made using java"
---

<div class="text-center p-4">
  <img width="500px" src="/img/tictactoe/Tictactoe2.webp" class="img-thumbnail" alt="tic tac toe screenshot">
</div>

During my first year of college, I decided to create a tic-tac-toe game using Java. For anyone who’s played tic-tac-toe before, the objective of the game should be pretty obvious. But for anyone who hasn’t, it’s simple. The game is played on a 3x3 grid. Two players take turns, one uses X and the other uses O. The goal is to be the first to get your symbol in a straight line, either vertically, horizontally, or diagonally.

When I made this game, I had just started learning Java through my ICS 111 course. At the time, this project helped me learn how static methods worked through the various helper functions I implemented. It also taught me how arrays worked, especially through array indexing.

Here is an example of array indexing being used in the win conditions. This snippet specifically checks for rows:

  {% highlight java %}
for (int i = 0; i < 3; i++) {                  
    if (board[i][0] == player &&               
        board[i][1] == player &&               
        board[i][2] == player) {               
        return true;
    }
}
{% endhighlight %}
  

