
**Corrected version of Concentration BCs for slow recombination. Single and multi-isotopes.** 
The simulation script I was using had a scaling factor of 0.7 in the implantation flux, I was not aware of it and it lead to artificial $q$ values close to 0.7 indeed. Here is the final corrected version: 
[Progress-tracker/Tritium inventory in PFC/Theory, models/Concentration BCs for slow recombination and multi-isotopes - Corrected version.md at main · AdriaLlealS/Progress-tracker](https://github.com/AdriaLlealS/Progress-tracker/blob/main/Tritium%20inventory%20in%20PFC/Theory%2C%20models/Concentration%20BCs%20for%20slow%20recombination%20and%20multi-isotopes%20-%20Corrected%20version.md)

I have kept the old version in which I briefly discuss where the error was and the impact it had on the results:
[Progress-tracker/Tritium inventory in PFC/Theory, models/OLD - Concentration BCs for slow recombination. Single and multi-isotopes - Old, mistake in simulation script.md at main · AdriaLlealS/Progress-tracker](https://github.com/AdriaLlealS/Progress-tracker/blob/main/Tritium%20inventory%20in%20PFC/Theory%2C%20models/OLD%20-%20Concentration%20BCs%20for%20slow%20recombination.%20Single%20and%20multi-isotopes%20-%20Old%2C%20mistake%20in%20simulation%20script.md)

**Implementation of new BC in SS316L:**
After finishing with the analytical equations for the surface and maximum mobile concentrations for slow recombination and multiple isotopes, I implemented them in our simulations and compared results with the original simulations (using a recombination flux boundary condition).
[Progress-tracker/Tritium inventory in PFC/FESTIM_simulations/FESTIM-2/Implementation of mobile concentration Dirichlet BC in SS316L.md at main · AdriaLlealS/Progress-tracker](https://github.com/AdriaLlealS/Progress-tracker/blob/main/Tritium%20inventory%20in%20PFC/FESTIM_simulations/FESTIM-2/Implementation%20of%20mobile%20concentration%20Dirichlet%20BC%20in%20SS316L.md)











