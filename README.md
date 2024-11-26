# -CSC-333-01-Linear-Programming-Solutions


Assignment Overview

Linear programming is a mathematical approach used to find the best possible outcome in a given scenario, such as maximizing profits or minimizing costs, subject to certain constraints. This assignment focuses on solving LP problems graphically and computationally.

### Key Objectives:
1. **Manually Solving the LP Problem:**
   - Identify and plot the constraints on a graph.
   - Determine the feasible region, where all constraints overlap.
   - Find the corner points of the feasible region.
   - Use the objective function to identify the optimal solution.

2. **Solving the LP Problem Programmatically:**
   - Use Python libraries like `numpy`, `matplotlib`, and `scipy` to plot constraints and solve the problem.
   - Validate the manual solution by comparing it with Python’s computational output.

---

Contents of the Repository

This repository contains the following files:
- **Hand-Solved Solution:** A PDF or image showing the manual graphical solution.
- **Python Code:** A Python script and Jupyter Notebook that solve the LP problem programmatically and include visualizations.
- **README:** A document explaining the assignment and how the solutions were approached.

---

How the Problem Was Solved

1. **Manual Solution:**
   - Each constraint was plotted to create a graph.
   - The feasible region was marked by finding the intersection of constraints.
   - The optimal solution was found by substituting corner points of the feasible region into the objective function.

2. **Python Solution:**
   - Python was used to automate the solution process.
   - The `scipy.optimize.linprog` method helped calculate the optimal solution.
   - A graph was generated to visualize the constraints and the feasible region.
   - The optimal solution was highlighted on the graph.
