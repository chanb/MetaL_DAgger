# Meta Learning DAgger (MetaL DAgger)
This work was motivated by the question of whether the DAgger algorithm can be learned. DAgger is a query expensive algorithm that requires querying the expert at every timestep.
Furthermore, this querying needs to be done on every unseen environment where the physical properties could be different (e.g. road conditions, car size, etc.)
To mitigate this cost, we wish to develop an algorithm such that we only need to gather expert data for a handful of environments to train an adept agent in unseen environment.
More specifically, we investigate whether there exists a transformation in parameter space such that an unlearned agent can be transformed into an agent with better performance.

Course project done in the graduate course Imitation Learning (CSC2621), Winter 2019.
