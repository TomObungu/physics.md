For a circuit with large current, a power source with small internal resistance is recommended. Car batteries have very low internal resistance so that they can provide the large current need to turn on the start motor in the car.

A source e.m.f has internal resistance. For example, a solar cell has internal resistance because the charge have to pass through the material of the cell.

# Terminal p.d and lost volts
A source of p.d can be represented by an $e.m.f$ in series with its internal resistance $r$. Figure $1$ shows a source of $e.m.f$ providing current $I$ to an external resistor, of resistance $R$:
![[Pasted image 20260103195422.png]]

The current is the same in both resistors. Using Kirchhoff's second law we have:
$$
\varepsilon = IR + Ir
$$
which can be rearranged to:
$$
\begin{gather*}
\varepsilon = I(R+r) \\ \\
\varepsilon = V + Ir
\end{gather*}
$$
where $V$ is the terminal p.d or simply the p.d across the external resistor and $Ir$ is the p.d across the internal resistor which is also known as the lost volts.


## Connecting cells
Connecting cells in series increases the available e.m.f but also increases the internal resistance. This limits the current the combination can produce. 
![[Pasted image 20260103200239.png]]

The same two cells connected in parallel produce the same e.m.f as one cell, but have a much smaller internal resistance, so produce a greater current.
![[Pasted image 20260103200508.png]]

# Determining e.m.f and internal resistance
You can determine the internal resistance of a cell using a potentiometer  to vary the values of $I$  and $V$  by varying the value of $R$. 
![[Pasted image 20260103202528.png]]
Since $\varepsilon=V+Ir$ and the equation of a straight line graph is $y=mx+c$. We can rearrange the equation for:
$$
V = -Ir + \varepsilon
$$
 Sketching a graph of V against I will give a straight line with

- gradient $-r$ 
- y-intercept $\varepsilon$

![[Pasted image 20260103202540.png]]

Thus the internal resistance can be found by multiplying the gradient by $-1$.

# Graphs of $V$ against $I$:
Increasing the e.m.f will yield the y-intercepting doubling, however the gradient will remain the same signifying the internal resistance is the same. This matches the scenario of putting cells in series
![[Pasted image 20260103202743.png]]

Decreasing the internal results in the same y-intercept but half the gradient. This matches the scenario of putting cells in parallel:
![[Pasted image 20260103202843.png]]

## High or low internal resistance
Many applies such as car batteries, phones and laptops have low internal resistance to allow them to be recharged using higher currents without overheating or wasting a lot of energy, so that recharging is fast. 

In contrast, high voltage power supplies used in classrooms have a very high internal resistance. This acts as a safety feature, preventing the power supply from delivering a fatal electric current. 