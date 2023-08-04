# Tic-Tac-Toe
Tic Tac Toe - Computer vs human

**INTRODUCTION**

This is a tic tac toe game which has the two users as - Computer and Human

**Flow Diagram**

```mermaid
    graph TD;
      Do you want to start or computer-->Fill positions;
      Fill positions-->Filled;
      Fill positions-->Empty;
      Fill positions-->All Filled;
      Filled-->Try other position;
      Try other position-->Fill positions;
      Empty-->Fill positions;
      All filled-->Win/Draw/Lose;
      Win/Draw/Lose-->Do you want to play again?;
      Do you want to play again?-->Yes;
      Do you want to play again?-->No;
      Yes-->Do you want to start or computer;
      No-->Exit;



```
