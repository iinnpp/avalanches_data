Dataset for a ring network.

U threshold = 1
delta_u (external input) = 0.022
eps (reset parameter) = 1
number of elements in the network = 250
K ("neighbour" distance in the ring) [1 5 10 25 50 60 70 80 90 100 125 150]
alpha (coupling parameter) [0.7 0.8 0.9 0.94 0.95 0.96 0.97 0.99 0.995]
number of avalanches = 10^6

avalanches_ring.mat 
4D matrix, contains avalanche size and distance
:,:,:,k - data for all alpha values for a given k 


