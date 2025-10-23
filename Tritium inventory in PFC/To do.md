1. Keep working on the BC for slow recombination, understand better the results and try to check/understand how do our $q_D$ and $q_T$ change with time. Also instead of finding these values so that our analytic expression matches the simulation, try to deduce them beforehand.
2. Manage to finally run high-heat loads simulations in FESTIM-2. To do so, maybe try to cap the maximum Tungsten temperature at around 1500 K.
3. Study 'simpler' maximum concentration functions with less steep gradients (can improve code efficiency). Study how these less realistic functions affect the results (maybe they are good enough to model implantation and bulk diffusion).
4. Start getting familiar with IMAS data, loading heat and particle fluxes and inputting them in our own FESTIM-2 simulations.
5. 






Cap maximum Tungsten Temperature:
[Progress-tracker/Tritium inventory in PFC/FESTIM_simulations/FESTIM-2/Cap maximum Tungsten temperature at around 1500 K.md at main · AdriaLlealS/Progress-tracker](https://github.com/AdriaLlealS/Progress-tracker/blob/main/Tritium%20inventory%20in%20PFC/FESTIM_simulations/FESTIM-2/Cap%20maximum%20Tungsten%20temperature%20at%20around%201500%20K.md)

Think of an 'easier' surface concentration function, with smaller derivatives. Try implementing it to run high heat loads cases and validate the results.
