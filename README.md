# HCI-575-Project
Tracking of Human microscopic parasites in Matlab 
Algorithm: Mass-Spring System
 
Schistosoma move by expanding and contracting their bodies, making a fixed-mesh system
difficult to use for tracking. Instead, this algorithm uses a modified mass-spring system to
automatically match the changing dimensions of the parasite's body. After calculation of edge
points on the image of the schistosome, the mass-spring system moves existing edge nodes to
these points and calculates appropriate locations of the rest of the skeleton.

A mass-spring system is generally defined as two nodes connected by an elastic spring. Each node
has mass, position, velocity, acceleration, and force, and each spring has stiffness, natural resting
length, and a damping value. Hooke's Law is used to calculate the force applied to each node
based on these variables, and new positions are calculated. In this system, each node correlates
with a point on the parasite, with mesh lines matching the springs connecting each node in a grid
array. 

