# Tic-Tac-Toe
Tic Tac Toe - Computer vs human

**INTRODUCTION**

This is a tic tac toe game which has the two users as - Computer and Human

**Flow Diagram**
```mermaid
  graph TD;
      Do you want to start or computer -->Fill positions;
      Fill positions-->If already filled, mark at other position;
      Fill positions-->Mark at position;
      Mark at position-->All positions filled;
      Mark at position-->Positions left;
      Positions left --> Fill positions;
      All positions filled--> Win or Draw;
      Win or Draw --> Do you want to play again?;
      Do you want to play again?---> Yes;
      Do you want to play again?---> No;
      Yes --> Do you want to start or computer;
      No-->Exit;
```
