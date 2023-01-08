# TwoRaisedTo

TwoRaisedTo is a command line game written in *C* Programming language to test how fast and for how long can you compute higher orders of *two*.

This game is designed for computer programmers who are obsessed with _binary_.

There are 10 modes to choose from -
1. Race Against Time
2. Challenger Mode

---------


### 1. Race Against Time
You are given 20 seconds to reach the highest levels.
The game ends if you enter the wrong answer, or run out of time.

[![asciicast](https://asciinema.org/a/IV3SeuK0AGIb8qg3xLq1qAeM3.svg)](https://asciinema.org/a/IV3SeuK0AGIb8qg3xLq1qAeM3)

&nbsp;

### 2. Challenger Mode
There is no timelimit, however the orders are random and gets difficult with each level.
The game ends if you enter the wrong answer.

[![asciicast](https://asciinema.org/a/4un9MmzDRdhk4DYpMgrKznR8I.svg)](https://asciinema.org/a/4un9MmzDRdhk4DYpMgrKznR8I)

&nbsp;

Bonus points if you input answer in <3 seconds.

---------

&nbsp;

## Usage

#### Recommended command to compile : 
```
gcc TwoRaisedTo.c -o TwoRaisedTo -O2 -lm
```
###### This will prevent the "undefined reference to 'pow'" error

Learn more about [this issue](https://www.includehelp.com/c-programming-questions/compiling-program-with-math-library-linux.aspx) and usage of [flags (like -O2)](https://developers.redhat.com/blog/2018/03/21/compiler-and-linker-flags-gcc).

&nbsp;

### Please leave a review after you play the game.


###### Made for fun under an two hours as a excuse to learn time related functions and debug on edge cases.
