·    **Find/calculate a value for the SS recombination coefficient and study its impact in the flux implantation approximation**

o   Progress: Ongoing

o   Comments: I found reliable values for Eurofer97 recombination and dissociation rates:

![](figures/Pasted%20image%2020251016100615.png)

[Permeation and trapping of hydrogen in Eurofer97 - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2352179121001290)

These coefficients are ~10-12 orders of magnitude lower than for tungsten, therefore they should be taking into account in the flux implantation, since the assumption $K \to \infty$ will probably not be valid anymore. Right now I am setting up simple hydrogen transport simulations in steel in order to compare maximum near-surface mobile concentrations with those predicted by the implantation flux approximation (ignoring recombination and taking it into account.) 

