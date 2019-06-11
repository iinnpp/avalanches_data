Datasets for a fully coupled network.

U threshold = 1
delta_u (external input) = 0.022
eps (reset parameter) = 1
number of avalanches = 10^6
alpha values [0.9 0.92 0.93 0.935 0.94 0.945 0.95 0.955 0.96 0.965 0.97 0.98 0.99]
N (number of elements in the network) [250 500 750 1000]

Data is stored in structure, which includes following fields:
n: number of elements in the network
alpha: alpha values
data: 4D matrix, (:,:,alpha_i,n_i) contains avalanche size and duration data for alpha_i alpha value and n_i N value.


file name fc_avalanches.mat 


