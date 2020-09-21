## Whole-Body Motion generation and control
This part accounts for the generation of the whole-body motions of the CENTAURO robot, in order to execute the plan generated before:
- Cartesian trajectories have to be generated in order to formalize a hierarchical inverse kinematics problem that is solved through the OpenSoT framework.
- When steps have to be taken, the robot should move its CoM in order to not fall down. This is done in an optimal control framework through Direct Multiple Shooting. Examples of plans (coming from OMPL) are also reported.

### References
A. Rocchi, E. M. Hoffman, D. G. Caldwell, and N. G. Tsagarakis, “OpenSoT:A whole-body control library for the compliant humanoid robot coman,” in *2015 IEEE International Conference on Robotics and Automation (ICRA)*, IEEE, 2015, pp. 6248–6253

A. Laurenzi, E. M. Hoffman, L. Muratore, and N. G. Tsagarakis, “Carte-sI/O: A ROS based real-time capable cartesian control framework,” in *2019 International Conference on Robotics and Automation (ICRA)*, IEEE, 2019,pp. 591–596.
