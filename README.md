Unbeatable Tic-Tac-Toe Using Minimax AI
I wanted to build an AI that genuinely cannot lose. Not one that plays randomly or makes occasional mistakes — one that plays perfectly every single time, no matter what you do. That's what this is.
How it works

The AI uses the Minimax algorithm with recursive depth-first search. Before making any move, it builds the entire game tree — every possible sequence of moves from the current position to every possible outcome. It then backpropagates the scores and always picks the move that guarantees the best result.
The result is an AI that will never lose. Beat it if you can  you won't.
What's actually happening under the hood

Every possible game state is evaluated recursively
Terminal states (win, lose, draw) are assigned scores
The AI maximizes its own score while minimizing yours
The optimal move is selected every turn without exception

What I learned

Implementing Minimax from scratch without any AI libraries
Recursive tree traversal and backpropagation
State space search and zero-sum game theory
How game theory translates directly into code

play here: https://hadialafyouni.github.io/unbeatable-tic-tac-toe/

Built with
HTML · CSS · JavaScript
