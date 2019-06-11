Datasets for 4 regimes (subcritical, critical, supracrtical, multipeaked) in fully coupled network.

U threshold = 1
delta_u (external input) = 0.022
eps (reset parameter) = 1
number of elements in the network = 1000
number of avalanches = 10^7
alpha_sub = 0.7
alpha_crit = 0.9684
alpha_supra = 0.99
alpha_multi = 0.9995

Data is stored in structures, one struct per regime. Each structure includes fields:
avalanches: 10^7:2 matrix with avalanche size and duration 
alpha: alpha value
n: number of elements in the network

av_sub_struct.mat subcritical regime
av_crit_struct.mat critical regime
av_supra_struct.mat supercritical regime
av_mpeak_struct.mat multipeaked regime

