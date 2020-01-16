# Program for Table 4 Replication in Abadie, Athey, Imbens & Wooldridge (2019)

The file that reproduces the Simulation Table 4 on p.39 is called "main_jan2020.m". 
This program reproduces the Simulation Table 4 on p.39
The rows that appear in the table are the first 3 rows and the last 20 rows of "gtabel" 

The functions that are called are:

1) gen_population.m
Generates population of size n

2) gen_sample.m
Generates sample of expected size (rho*N) for each simulation

3) se_calc.m
Calculates estimates for different standard error estimators 

4) se_boots_calc.m
Calculates improved bootstrapped standard erorrs 

5) gtable.m
Creates table
