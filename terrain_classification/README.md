This is a test to generate a simple decision surface using the Naive Bayes algorithm.  This is a simple exercise to analyze
the drivability of various terrains, considering just two attributes: gradient and roughness. Obviously, the rougher and steeper a particular
terrain, the slower one must drive accross it. 

This algorithm takes in training data. Each data point contains measures for roughness and steepness of the terrain.
Each data point has an associated label, or category: 

    Category 1: Safe to drive fast. 
    Category 2: Unsafe to drive fast.

The output is a png graphic which shows the test points, along with the decision surface.
