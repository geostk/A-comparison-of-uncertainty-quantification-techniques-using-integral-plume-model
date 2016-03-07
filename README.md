# A-comparison-of-uncertainty-quantification-techniques-using-integral-plume-model

Model data used for a comparison of uncertainty quantification techniques, including polynomial chaos and gaussian process regression.  This data set consists of ensemble generated using Texas A&M oil calculator(TAMOC, version 0.1.5, https://github.com/socolofs). Five inputs parameters are perturbed in this experiment, including entrainment coefficient, entrainment ratio, gas to oil ratio, droplet size distribution d95 and droplet size distribution spreading ratio. Only plume trap height and peel height are included. Details of each ensemble are as follows:  

1) A 5 dimensional 50,000 member reference ensemble. (mc_50000.mat)

2) A 5 dimensional 100 member latin hypercube ensemble. (lhs_100.mat)

3) A 5 dimensional 903 member ensemble generated for polynomial chaos projection technique. (pc_projection.mat)

4) Five 1 dimension 201 member equal space enesemble for comparison. 
(simulation_1d_para1.mat; simulation_1d_para2.mat; simulation_1d_para3.mat; simulation_1d_para4.mat; simulation_1d_para5.mat)










