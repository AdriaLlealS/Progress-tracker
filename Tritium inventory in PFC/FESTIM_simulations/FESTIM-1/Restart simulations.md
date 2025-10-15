·  **Define a restart function that takes the last values of a simulation as initial condition and runs a new FESTIM simulation**

o   Progress: Done

o   Comments: Instead of exporting xdmf files and reading .h5 files, we read the last profiles of a specific simulation from a .txt output and load them as initial conditions.