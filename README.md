
# Partial boids simulation in UE4 Blueprints

This is a blueprint-based boid simulation. So far it is a partial implementation; it only has birds fly toward the center of the closest group;
it does not attempt to avoid collisions nor try to fly in the same general direction as the other nearby birds.

It does computations on two levels; every tick, the high-level planner chooses a new target location for some of the birds. Every tick, all birds steer toward their targets.

Boids reference: http://www.red3d.com/cwr/boids/
