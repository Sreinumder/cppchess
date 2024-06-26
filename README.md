﻿# Cppchess
 A very basic two player c++ TUI chess game implementation.
 
## Screenshot
![game](assets/game.png)
 
## Controls
- Use numpad for directions with 5 as enter or select square
<pre>
7 8 9  ↖ ↑ ↗ 
4 5 6  ← ⏎ → 
1 2 3  ↙ ↓ ↘ 
</pre>
- Alternatively for player 2, t for toggle two control mode
<pre>
q w e    ↖ ↑ ↗
a s d f  ← ↓ → ⏎
z   c    ↙   ↘
</pre>
- u and i to undo and redo the moves
- h for help
- r for redraw or reload

## Features
- supports all the basic rules like castling, en-passant etc properly.
- move log implementation with the ability to undo and redo and prune move tree
- two player keyboard support

## To-Do
- [ ] PVE support with different difficulty level
- [ ] save and load games on standard file format
- [ ] local leaderboard
- [ ] Train AI chess-bots with recursive move searches

## Requirements
[Visual Studio 2022 community version](https://visualstudio.microsoft.com/vs/community/) with g++ and MSVC compiler.

## Installation
### On Windows
Please use! [Windows Terminal](https://github.com/microsoft/terminal) for proper Text rendering.
Then, You can Download the [Latest Release](https://github.com/Sreinumder/cppchess/releases/latest) and test it.

### On Linux or MacOs
Not supported yet :(

## Sidenote
ik this project is kinda mess ngl. I wrote it on whim for college side project within 2-3 days. I will probably rewrite this in more cross-platform friendly environment. I might try rust idk. Anyway I did had blast coming up with the strategies for generating possible moves for given piece at any given scenario and realizing a [hilarious bug](https://youtu.be/U4ogK0MIzqk?si=SlulO90-RZho1PLv&t=664).
