Physical quantities that decrease by the same factor in equal time interval have a constant-ratio pattern us called exponential decay. The p.d across a capacitor decreases exponentially over time.

Exponential functions are governed by Euler's constant $e$, which has a value of $2.718\dots$

When a capacitor has capacitance $C$, the resistance in the resistor is $R$ and the p.d across the capacitor and the resistor is $V_{0}$
- The p.d V across the capacitor or the resistor $=V_{0}$
- The current in the resistor is $I=\frac{V_{0}}{R}$
- The charge in the capacitor $Q=V_{0}C$
![[Pasted image 20251127211530.png]]

When the capacitor discharges through the resistor, the charge stored by the capacitor decreases with time and hence the p.d across it also decreases accordingly due to $V = \frac{Q}{C}$. Eventually, the p.d and the charge stored by the capacitor, and the current $I$ in the resistor are all zero.

Below are $V-t$, $I-t$ and $Q-t$ graphs. These graphs all show exponential decay over time after the switch is opened
![[Pasted image 20251127212105.png]]

The equations for these quantities are:
$$
V = V_{0}e^{\frac{1}{CR}} \qquad I = I_{0}e^{\frac{1}{CR}} \qquad Q=Q_{0}^{\frac{1}{CR}}
$$
Where $V_{0},I_{0}$ and $Q_{0}$ are the initial values for voltage, charge and current of the capacitor before being discharged and $RC$ is the time constant with value resistance multiplied by capacitance.
# Constant-ratio property of exponential decay
 From the graph of p.d against t shows that $\frac{V_{1}}{V_{0}}\approx \frac{V_{2}}{V_{3}} \approx \frac{V_{3}}{V_{4}}$ which obeys the law voltage being the same for capacitors in series
 ![[Pasted image 20251127231748.png]]

## Time constant
The time constant of a capacitor resistor circuit is equal to to the capacitance and resistance. In general the time constant $\tau$ is the time taken for the p.d or current to decrease to a value of $e^{-1}$
# Modelling exponential decay
As charge can be show that $I =\frac{V}{R}$ and $Q=VC$. Thus current may be written as:
$$
I = \frac{V}{R} = \frac{VC}{CR} = \frac{Q}{CR}
$$
As well as that we know that current is the rate of change of charge, thus $I=\frac{\Delta Q}{\Delta t}$. As the charge in a capacitor's decreases exponentially, the charge is $I=-\frac{\Delta Q}{\Delta t}$ thus:
$$
\frac{\Delta Q}{\Delta t} = -\frac{Q}{CR}
$$
The equation for exponential decay of charge is an solution to this equation. 

# Iterative modelling
The equation $\frac{\Delta Q}{\Delta t} = -\frac{Q}{CR}$ can be used for model the decay of $Q$ on the capacitor