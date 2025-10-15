· **Look at how the adaptative time step is actually implemented in the FESTIM source code**

o   Progress: Done

o   Comments: If the solver converges slowly (for instance with $n_{it} > 5$), result is kept and the next stepsize is $dt = \frac{dt}{r_c}$. If the solver does not converge under $n_{max}$, it retries finding the solution with the new $dt = \frac{dt}{r_c}$ until solver converges or $dt_{min}$ is reached (and program terminated with error). If convergence is fast $dt$ keeps increasing as $dt = dt\cdot r_c$ until $dt_{max}$ is reached.