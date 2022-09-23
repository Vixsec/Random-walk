# Random-walk
Using a 'Monte Carlo Simulation' to calculate the average travelled distance for a random walk


# QUESTION?

	What is the longest random walk you can take
	where on average you will be less then N steps
	away from your starting position?


# Description

	This program is a simple simulation for the question above.
	It runs a random walk of N-steps, N-times per step length and marks wheather
	or not, on average, it's left withen N-steps from the the point of origin.

	It then increases the number of steps it needs to take per cycle by 1, and starts 
	the simulation again with the new value. If the result of the new N-steps cycle
	yeilds a 50% chance or greater to be withen N-steps of the origin, it 
	will store this new value as the greater then average result.

