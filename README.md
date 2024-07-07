# pop
A timing game similar to those found in some arcades

7-6-2024
I went to an arcade with a friend recently and I played a game there where the goal is simply to press a button at the correct time.

The game consists of a little bar that spins around a large circle, and you press the button when the bar overlaps with a little circular target.
After you press the button and hit the target, the target jumps positions and the direction of the spinning bar is reversed. 
The goal is to correctly chain multiple hits in a row, to get a high score.
It gets more difficult as you play. The bar moves faster and faster, and the target moves incrementally shorter distances away each hit, giving you less time to react.

If you press the button when the bar isn't overlapping the target, you lose. Or you lose if you fail to press the button by the time an overlap with the target ends.

I saw this game, and I thought it would be really fun to program this game in Javascript.

Progress Updates:
7-6-2024
I started on it this evening, and I have the core concept of the game down.

It's all on one HTML file currentlt.
I'll split them into a separate files later on, so github properly recognizes this as a mostly JavaScript project.

So far:
Implemented styling structure for the game,
Added rotation to the main bar,
Added Collision detection between the bar and target,


Next to add:
Button press to hit the target, both on PC and mobile,
Reversing directions and speed / distance modifiers,
Score keeping,
Losing if you hit the button on a non-collide or if you pass the target,
Reset Game button / Game-Over Screen

High Score Leaderboard in local storage and/or possible SQL Database


-Wesley King, Wesleyking98@hotmail.com
