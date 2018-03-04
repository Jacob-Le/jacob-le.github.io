# CMPM163 HW3

Assignment B:
------------
* 2 sets of shapes of different sized cubes and spheres.  The color of the diffuse is tied to time elapsed.
    * Shape 1: difference(sphere, cube)
    * Shape 2: difference(bigger cube, bigger sphere)
    * FinalShape: union(Shape2, Shape1)   

Assignment C:
------------
* Part 1 Topic: Caustics
We could use noise to place points across a plane to create a voronoi diagram.  We can then animate that diagram by moving the placed points.  The plane we draw on will be the blue water background, and the lines along the voronoi diagram will be colored in white.  We can use a signed distance function along each line of the voronoi diagram to get a softer and more natural blend for the caustic lines. 

* Part 2:
Team members: Andrew Gwinner and Nick Ho