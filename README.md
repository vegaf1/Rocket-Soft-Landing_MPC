# Rocket-Soft-Landing_MPC

This project solves the non convex soft landing problem by transforming it into a linear convex optimal control problem using loseless convexification. 

Requirements: 
- Install Julia 1.6.5 https://julialang.org/downloads/
- Install the following packages: ECOS, Convex, LinearAlgebra, SatelliteDynamics, COSMO, Mosek, MosekTools

The rocket_problem-convexification-wmass-mpc file solves the landing error minimization problem and the rocket_problem-convexification-wmass-2prob-mpc file solves the fuel optimization problem.

The rocket dynamics file is work in progress on implementing the soft landing problem in ALTRO. 

The report that is included provides details on how the code was developed. 
