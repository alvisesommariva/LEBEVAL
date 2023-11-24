# LEBEVAL
LEBEVAL: Matlab codes for Lebesgue constant evaluation on interval, square, disk, cube, simplex and ball.

The main folder contains several subfolders that lead to the wanted domain. In particular we examine the Lebesgue constants for some interpolation sets in the
- interval,
- simplex,
- square,
- disk,
- cube,
- ball,
as well as we analyse the Lebesgue constant for Least-Squares on
- square,
- disk.
  
Each folder contains:
- "demo_basic.m" that is a basic demo for understanding how the Lebesgue costant estimator "lebconst_eval_*.m" works;
- "demo_leb_*.m" makes all the experiments cited in the paper below.
- the folder "_DATA" contains the plots of the papers, a file "numerical_experiments.txt" with the statistics of the experiments, and if it is useful, the files "set_AFP_*", "set_DLP_*" 
containing respectively Approximate Fekete Points and Discrete Leja Points for mild degrees.


Reference paper:
Leokadia Bialas-Ciez, Dimitri Jordan Kenne, Alvise Sommariva, Marco Vianello, Evaluating Lebesgue constants by Chebyshev polynomial meshes on cube, simplex and ball.
