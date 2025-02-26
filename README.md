This project focuses on optimizing the locations of coffee shops in Chicago, with the goal of minimizing the total distance to public libraries. The main aim is to determine the most efficient coffee shop placements to provide easy access for customers, considering proximity to libraries.

Process Breakdown:
1. Geospatial Data Collection: Using Geopy, the geographic coordinates (latitude and longitude) of coffee shops and libraries within Chicago were gathered.
2. Distance Calculation: The distance between potential coffee shop locations and public libraries was calculated.
Optimization Model:
3. Variables: The decision variables represented whether a coffee shop should be placed at a particular location and how libraries are assigned to coffee shops.
4. Objective Function: Minimize the total distance between coffee shops and libraries.
5. Constraints: Constraints could include limits on the number of coffee shops, coverage requirements for libraries, or budget constraints.
6. Solution: IBM CPLEX, combined with Docplex, was used to solve the MILP model and find the optimal locations for the coffee shops.
Visualization: Folium was used to visualize the solution on an interactive map, showing coffee shop locations and their proximity to libraries.
