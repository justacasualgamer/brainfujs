# brainfujs
A Brainf**k IDE.
# How to use
There are 6 memory cells. When you run the code, it starts in the first cell.

+: Adds 1 to the current cell.

-: Minuses 1 from the current cell.

\>: Moves the current cell by 1. If used at the 6th square, it will go back to the 1st square.

<: ditto, but reverse.

.: Outputs stuff in the current cell.

,: Prompts for an input.

[: Starts repeating commands inside until the selected cell is 0. If the current cell is 0, skips the command(s) inside.
\]: If value is 0, stop the repeat.

Bracket/S (i meant P/S but brackets lol): If the values never touch 0, it will run forever and possibly crash the site.
