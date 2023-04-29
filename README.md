# Lab-Assignment-4
#Abstract
In this project, the primary objective was to improve
the performance of the Mini-max algorithm by implementing
alpha beta pruning in the game of noughts and crosses. The aim
was to demonstrate that by using this technique, the algorithm
can make more efficient decisions and reduce the search space,
resulting in faster game play. Furthermore, the project aimed to
prove the minimax value backup argument on the game tree for
the game of Nim. The result showed that player 2 will always
emerge victorious regardless of the moves made by player 1.
This is because the minimax value backup argument shows that
player 2 can always choose a move that forces player 1 into a
losing position. The study provides insights into the application of
the Mini-max algorithm with alpha beta pruning to improve the
performance of game-playing agents in games with large search
spaces. It also highlights the importance of understanding the
minimax value backup argument in analyzing game trees and
making optimal decisions in games such as Nim.

#Problem Statement
Implement MINIMAX and alpha-beta pruning
agents. Report on number of evaluated nodes for Noughts
and Crosses game tree

#Conclusion
The following are the findings:
1. We found that the game tree for Nim has a size of almost
one million, indicating the complexity of the game even for a
small number of piles and objects.
2. We determined that the outcome of the game of Nim can be
predicted by calculating the nimsum and the winning strategy
involves making the nimsum xor zero. If the initial state has an
xor value of zero, player 2 will always win, otherwise, player
1 will always win, assuming optimal play from both players.
3. We compared the performance of the Minimax algorithm
and Alpha Beta Pruning by evaluating the number of nodes
traversed by each algorithm. We found that the number of
nodes evaluated with Alpha Beta Pruning was significantly
lower than that of the Minimax algorithm, resulting in a faster
execution time.
4. We analyzed the time complexity of both algorithms. The
time complexity of the Minimax algorithm is O(b
m), while
the time complexity of Alpha Beta Pruning is O(b
m/2
). This
means that Alpha Beta Pruning can significantly reduce the
number of nodes evaluated, resulting in a faster execution time
for larger game trees.
