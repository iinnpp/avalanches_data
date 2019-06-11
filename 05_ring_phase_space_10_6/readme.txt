Dataset for a phase space and avalanche size probability distribution in ring network.

U threshold = 1
delta_u (external input) = 0.022
eps (reset parameter) = 1
alpha = 0.2929
number of elements in the network = 2
k("neighbour" distance in the ring) = 1
number of avalanches = 10^6


Data is stored in a structure ring_phase_sp.mat, structure includes following fields:
alpha: coupling parameter (0.2929)
states_eq: equilibrium states
prob: computed avalanche size probabilities (in rows - different L, in cols - (:,1) num, (:,2) analyt)
