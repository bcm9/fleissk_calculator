# fleissk_calculator
Fleiss' kappa MATLAB function for interrater agreement of categorical ratings

fleissk_calculator Fleiss' kappa calculation for interrater agreement of categorical ratings

Arguments: fleissk_calculator(n,N,k)
   
   n = raters
   
   N = subjects
   
   k = categories
   
   k_table = N x k matrix

example from https://en.wikipedia.org/wiki/Fleiss%27_kappa:
 
k_table=[0 0 0 0 14;0 2 6 4 2; 0 0 3 5 6; 0 3 9 2 0; 2 2 8 1 1;7 7 0 0 0; 3 2 6 3 0; 2 5 3 2 2; 6 5 2 1 0 ;0 2 2 3 7;];
 
fleissk_calculator(14,10,5,k_table)
