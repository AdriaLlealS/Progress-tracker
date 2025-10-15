·    **Check that FESTIM is actually running the simulations with the parameters that we want (Temperature profile and evolution, implantation flux…) **

o   Progress: Done

o   Comments: Temperature exported from FESTIM matches the input function $T(x,t)$. Corrected a bug in the plotting script, there were repeated time indexes in the exported files (due to small timesteps) and this was causing problems. Results now make sense, and we observe the expected behaviors. Managed to export fluxes and inventory calculated from FESTIM directly. Light discrepancies in the implantation flux (still to be checked deeper) but values match our calculated variables expected behaviors.