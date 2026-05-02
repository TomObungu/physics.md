The equation $\frac{\Delta Q}{\Delta t} = -\frac{Q}{CR}$ can be used to model the decay of $Q$ on the capacitor.

1. Start with a known value for the initial charge $Q_{0}$ and a known value for the time constant $CR$. The readings can be taking from a circuit consisting of a switch, ammeter with a capacitor, resistor and voltmeter in parallel:
	1. ![[Pasted image 20260502103420.png]]
2. Choose a time interval $\Delta t$ which is small compared to the time constant. This is to ensure the capacitor does not discharge faster than you can take readings. This is also to keep the value of $\Delta Q$, precise. 
3. 
	1. Using the readings from the ammeter, the known value for capacitance and the known value for resistance, calculate the instantaneous charge $Q$, using $Q = CIR$. 
	2. Calculate the charge leaving the capacitor $\Delta Q$, in time interval $\Delta t$, using. 
$$
\Delta Q = \frac{\Delta t}{CR} \times Q
$$
4. Calculate the charge $Q$ left on the capacitor at the end of the period $\Delta t$ by subtracting $\Delta Q$ from the previous value of $Q$. On the first interval, the previous reading of $Q$ is $Q_{0}$. 
5. Repeat the process for multiple time intervals. 
An example table of the processes:
![[Pasted image 20251127234241.png]]
Using example values of time constant $RC = 2.0s$ and time interval $\Delta t = 0.1s$. We can show the constant time ratio of exponential decay in $\Delta Q$
$$
\Delta Q = \frac{0.1}{2}Q = 0.05Q
$$
After every $\Delta t = 0.1s$, the charge is $95\%$ of the previous value of $Q$.  This constant time-ratio property is characteristic of exponential decay. 

Once finished taking value for the iterative model. The value of Q from the table can be compared with the known mathematical model of $Q$:
$$
Q = Q_{0}e^{\frac{-t}{RC}}
$$
to test the accuracy of the model. Furthermore exponential decay can be shown by observing that value of $\Delta Q$ on each time interval is approximately constant. 