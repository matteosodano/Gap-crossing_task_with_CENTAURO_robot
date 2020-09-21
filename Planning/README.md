## Planning

Two planning strategies have been chosen:
- Sampling-based method using motion primitives: the robot can execute only certain movements (rolling with the wheels, spinning on the spot, stepping). With these, it must move in a fully known environment in which an obstacle to be avoided and a gap to be overcome are present. The code is implemented using the OMPL library for C++.
- Nonlinear Programming (NLP): an optimization procedure is set up to minimize the displacement between the robot actual position and the desired one. A certain number of constraints (e.g. centroidal statics, friction cones, etc) are also considered. The code is implemented using the CasADi framework for Python.
