# Advanced-Data-Structures-lab_2

Files
-----
  RBNode.h   - Red-Black Tree implementation (header-only)
  main.cpp   - Interactive demo
  README.txt - This file

Requirements
------------
  MinGW-w64 (g++ for Windows)
  Download from: https://www.mingw-w64.org/

Compile
-------
  Open Command Prompt in the folder containing the files, then run:

    g++ -std=c++17 -Wall -o rbtree.exe main.cpp

Run
---
  rbtree.exe

Menu options
------------
  1 - Insert a value
  2 - Delete a value
  3 - Search for a value
  4 - Find minimum
  5 - Find maximum
  6 - Display tree + inorder + depth + black-height + maxBlackKey + maxRedKey
  0 - Exit

Node format:  key:b = black node,  key:r = red node
