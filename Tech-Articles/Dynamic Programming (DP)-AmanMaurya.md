
=======================================================

Article Title: Dynamic Programming (DP)
Author Name: Aman Maurya
Author Profile: https://github.com/Amanmaurya-2012
Date: 17/10/2021

=======================================================

Dynamic Programming (DP) is an algorithmic technique for solving an optimization problem by breaking it down into simpler subproblems and utilizing the fact that the optimal solution to the overall problem depends upon the optimal solution to its subproblems.

Dynamic programming approach is similar to divide and conquer in breaking down the problem into smaller and yet smaller possible sub-problems. But unlike, divide and conquer, these sub-problems are not solved independently. Rather, results of these smaller sub-problems are remembered and used for similar or overlapping sub-problems.

Dynamic programming is used where we have problems, which can be divided into similar sub-problems, so that their results can be re-used. Mostly, these algorithms are used for optimization. Before solving the in-hand sub-problem, dynamic algorithm will try to examine the results of the previously solved sub-problems. The solutions of sub-problems are combined in order to achieve the best solution.

So we can say that −

1.The problem should be able to be divided into smaller overlapping sub-problem.

2.An optimum solution can be achieved by using an optimum solution of smaller sub-problems.

3.Dynamic algorithms use Memoization.

Comparison-
In contrast to greedy algorithms, where local optimization is addressed, dynamic algorithms are motivated for an overall optimization of the problem.

In contrast to divide and conquer algorithms, where solutions are combined to achieve an overall solution, dynamic algorithms use the output of a smaller sub-problem and then try to optimize a bigger sub-problem. Dynamic algorithms use Memoization to remember the output of already solved sub-problems.

Example-
The following computer problems can be solved using dynamic programming approach −

1.Fibonacci number series
2.Knapsack problem
3.Tower of Hanoi
4.All pair shortest path by Floyd-Warshall
5.Shortest path by Dijkstra
6.Project scheduling
Dynamic programming can be used in both top-down and bottom-up manner. And of course, most of the times, referring to the previous solution output is cheaper than recomputing in terms of CPU cycles.


