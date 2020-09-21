## Planning with NLP
A quadruped is modeled as two bipeds interconnected via a mass-less prismatic joint. A goal is assigned in terms of the CoMs of the two bipeds. This is just an abstraction, since the robot CoM is not represented by any of those CoMs, but it can be computed with a weighted sum (provided that the mass of the bipeds are chosen carefully).

A set of constraints are imposed: centroidal statics, friction cones, constraints on the kinematic structure of the model (distance between feet, distance between CoM and related pair of feet, etc), and others (e.g. one step at a time has to be taken).
