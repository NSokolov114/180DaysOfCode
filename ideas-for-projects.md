# Ideas for projects

### Tic-Tac-Toe Unbound
Classic Tic-Tac-Toe has no balance, it's short and boring. But it becomes a fun game if the following limitations are removed:
- 3x3 grid -> grid is limitless (~100x100 so that it fits the screen w/o scrolling)
- 1 point to win -> the game ends when a player get ~25 points or makes ~250 moves
- 3 Xs or Os in a row -> 5 in a row for 1 point
It's obviously way more complex to code

### Chess
The problem is that I've no idea how to write a bot with 1k ELO. 3rd party?

### Habit app
An app where you can track how much time did you spend each day on different stuff.  
Maybe with a rulebook and links to extra info.  
A heat map of progress (like on GitHub, but 1 line for tracking 1 habit).  
It's not convenient to track the time of activities on the go on web, so either make it very mobile friendly, on focus on the rulebook aspect.  

### Excel <---> XML converter
Mockup version of the tool that would be really useful at work, but there's always something more important. I can build a draft and test some ideas on my own time.  
The tool should parse an Excel multipage spreadsheet (all files are based on the same template, number of elements can change, some data can be missing), validate the data, correct the data if possible, clean the data, create XML string (based on the same template) and save it in a new file.  
The tool should allow to perform the reverse operation, the only difference is that the XML data is clean (always present, and formatted correctly).  
Also in the real application XML document is never edited directly, it's converted to a class. Should I do it in the same way or should I parse it?

### Visualisation for sorting algorithms
C# backend + React frontend?  
But there's no much logic to justify the backend. Without web front it's going to look ugly.  
Maybe do it with text-based graphics?.. Not sure.

### Sudoku Solver
It would be interesting to write a sudoku solver that uses different algorithms and shows on one screen the progress for the same number of iterations (or maybe it should use a different metric, like amount of resources spent).

## Contents
* [Log](log.md)
* [Resources](resources-programming.md)
* [Ideas for Projects](ideas-for-projects.md)
