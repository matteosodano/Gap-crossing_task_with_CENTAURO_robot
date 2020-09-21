## Cartesian Trajectories
This module generates the trajectories for the end effectors of CENTAURO (in particular, its feet). In particular, commands for rolls, spins and steps are given. The `yaml` file reports the priority of tasks to be enforced in the formulation of the Hierarchical Inverse Kinematics problem for the whole-body motion generation. The problem is then formalized by the front-end solver and solved by the back-end one.
A plan from the OMPL planner is reported. Also a folder with CoM movement to be done during step phases is present.
