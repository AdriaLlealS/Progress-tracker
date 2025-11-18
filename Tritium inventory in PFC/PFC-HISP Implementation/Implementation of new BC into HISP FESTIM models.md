·  **Instead of simulating the implantation flux inside the materials, we want to implement the new Dirichlet BCs in which we fix the surface concentration of mobile species based on the analytical formula from the gaussian implantation approximation**

o   Progress: Ongoing. Now I need to implement the latest version of festim-fenicsx together with dolfinx v0.10.0 into PFC-T-T/HISP and relax tolerances / maximum timestep caps in order to further speed simulations. 

o   Comments: The new BC has already been implemented modifying the festim models on HISP. After that, the capability test scenario was run for all bins with the old and the new models, and these are some useful analysis on the different runtimes:

Overall maximum runtime:

  Job:       bin_15_shadowed_695205
  
  Bin/Mode:  16 / shadowed
  
  Material:  B, Thickness: 1mum, BC: Old
  
  Runtime:   191402 s  (2 days, 5:10:02)
  

Maximum runtime with Old BC:

  Job:       bin_15_shadowed_695205
  
  Bin/Mode:  16 / shadowed
  
  Material:  B, Thickness: 1mum, BC: Old
  
  Runtime:   191402 s  (2 days, 5:10:02)
  

Maximum runtime with New BC:

  Job:       bin_15_shadowed_696753
  
  Bin/Mode:  16 / shadowed
  
  Material:  B, Thickness: 1mum, BC: New
  
  Runtime:   66771 s  (18:32:51)
  

Maximum runtime for W:

  Job:       bin_7_low_wetted_695184
  
  Bin/Mode:  8 / low_wetted
  
  Material:  W, Thickness: 12mm, BC: Old
  
  Runtime:   34566 s  (9:36:06)
  

Maximum runtime for B:

  Job:       bin_15_shadowed_695205
  
  Bin/Mode:  16 / shadowed
  
  Material:  B, Thickness: 1mum, BC: Old
  
  Runtime:   191402 s  (2 days, 5:10:02)
  

Maximum runtime W, New BC:

  Job:       bin_5_low_wetted_696726
  
  Bin/Mode:  6 / low_wetted
  
  Material:  W, Thickness: 12mm, BC: New
  
  Runtime:   20899 s  (5:48:19)
  

Maximum runtime W, Old BC:

  Job:       bin_7_low_wetted_695184
  
  Bin/Mode:  8 / low_wetted
  
  Material:  W, Thickness: 12mm, BC: Old
  
  Runtime:   34566 s  (9:36:06)
  

Maximum runtime B, New BC:

  Job:       bin_15_shadowed_696753
  
  Bin/Mode:  16 / shadowed
  
  Material:  B, Thickness: 1mum, BC: New
  
  Runtime:   66771 s  (18:32:51)
  

Maximum runtime B, Old BC:

  Job:       bin_15_shadowed_695205
  
  Bin/Mode:  16 / shadowed
  
  Material:  B, Thickness: 1mum, BC: Old
  
  Runtime:   191402 s  (2 days, 5:10:02)
  

Averages:

  W, New BC: 17047.85 s (4:44:08)
  
  W, Old BC: 24811.10 s (6:53:31)
  
  B, New BC: 18620.91 s (5:10:21)
  
  B, Old BC: 46068.36 s (12:47:48)
  