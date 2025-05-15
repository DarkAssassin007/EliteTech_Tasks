Project: Optimization Model - Product Mix Problem

Description:
This notebook solves a business optimization problem using Linear Programming with the PuLP library. The goal is to determine the optimal product mix to maximize profit given resource constraints.

Problem Statement:
A company produces two products:
- Product A:
  - Profit = ₹40 per unit
  - Uses 2 hours of labor and 3 material units
- Product B:
  - Profit = ₹30 per unit
  - Uses 1 hour of labor and 4 material units

Available Resources:
- 100 hours of labor
- 120 units of material

Steps Followed:
1. Define decision variables for quantities of each product.
2. Construct an objective function to maximize total profit.
3. Add constraints for labor and material.
4. Solve the linear programming model using PuLP.
5. Visualize constraints and feasible region using matplotlib.

Tools Used:
- PuLP (for optimization modeling)
- Matplotlib and NumPy (for visualization)

Output:
- Optimal units of Product A and B to produce
- Maximum achievable profit
- A graph showing the feasible region defined by constraints

This project demonstrates how to model and solve real-world resource allocation problems using Python.
