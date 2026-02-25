The activity, $A$, of a source is given by the equation $A = \lambda N$, where $\lambda$ is the decay constant of the isotope and $N$ is number of the undecayed nuclei of the isotope in the source. 

We can use the approach of iterative modelling that you have used for discharging capacitors. 

## Procedure
1. Start with a given number $N_{0}$ of undecayed nuclei in the sample
2. Choose a very small interval of time $\Delta t$.The value of $\Delta t$, must be very small compared to the half-life, $t_{\frac{1}{2}}$ of the isotope, so that you can assume that the activity of the source does not change significantly in this interval.
3. Calculate the number of nuclei decaying, $\Delta N$, within the source during the time interval $\Delta t$, using the equation:
$$
\Delta N = \lambda(\Delta t)N
$$
4. Calculate the number $N$ of undecayed nuclei in the source at the end of the period $\Delta t$, by subtracting $\Delta N$ from the previous value for $N$.
5. Repeat step 4 for the subsequent multiples of this time interval $\Delta t$. 

Consider this example:
- $N_{0}=1000$
- $t_{\frac{1}{2}} =  1s$
- $\lambda = 0.693 s ^{-1}$
- $\Delta t = 0.1s$

The equation for modelling the number of nuclei decaying in each time interval $\Delta t = 0.1s$ is:
$$
\Delta N = (0.693)(0.1)N = 0.0693N
$$

This means that number of number of nuclei decaying in 0.1s will be 6.93% of the initial number of nuclei, so after each period of $0.1s$, the number of undecayed nuclei in the source must be $93.07\%$ of the previous number of nuclei. The number of nuclei will therefore decrease exponentially with time.

Below is a spreadsheet showing the umber of undecayed nuclei using the iterative modelling method. The third column is the actual number of undecayed nuclei calculated using the equation $N=N_{0}e^{-\lambda t}$. 

![[Pasted image 20260225082253.png]]