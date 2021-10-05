# SIR-Model-Simulation

Introduction: SIR Model
The population(N) is divided into three disjoint groups denoted as compartments:
a) The susceptible individuals are denoted by S.
b) The infected and infectious individuals are denoted by I.
c) The recovered or removed individuals are denoted by R.
Then, in the course of the epidemic, there is a transition of the individuals first from 
the compartment for S to that for I and then from there to the compartment for R.
This transition is governed by a number of parameters which is characteristic to 
the virus modeled.

Here parameter identification is acheived using PINN, along with simulating the SIR Model.
Done in 3 steps:
1) Constant parameter throughtout the course of simulation.
2) Piecewise constant throughtout the course of simulation.
3) Variable throughtout the course of simulation.
