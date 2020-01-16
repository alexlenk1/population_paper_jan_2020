# Program for Table 4 Replication in Abadie, Athey, Imbens & Wooldridge (2019)

This repository contains MATLAB code to reproduce the simulation results summarized in Table 4, p. 39.  
The main file to run is called **main_jan2020.m**. It contains detailed commments on each of the applied steps. This file produces a LaTeX exportable table called *gtabel*. The rows that appear in the Table 4 are the first 3 rows and the last 20 rows of *gtabel*. 

The functions that are called within the main program are:

1) **gen_population.m**
Generates population of size n

2) **gen_sample.m**
Generates sample of expected size (rho*N) for each simulation

3) **se_calc.m**
Calculates estimates for different standard error estimators 

4) **se_boots_calc.m**
Calculates improved bootstrapped standard erorrs 

5) **gtable.m**
Creates LaTex exportable table

The additional file **Simulation_Comments.pdf** contains more information on how each population is generated and how simulation samples are constructed. 
