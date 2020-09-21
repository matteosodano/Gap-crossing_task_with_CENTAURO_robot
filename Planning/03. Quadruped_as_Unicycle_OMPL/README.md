## Quadruped as Unicyle
This is the code actually used for CENTAURO. It can perform three kinds of movements:
1. roll with the wheels (forward, backward, right, left);
2. spin around the center of the support polygon (clockwise, counter-clockwise);
3. step forward with a leg (this is not present in the folder labeled `no step`).

An obstacle and a gap are present in the environment. If the gap is traversable but infinitely-long, steps are necessary to overcome it; on the other hand, if it is traversable but finite, the robot may also circumvent it.
