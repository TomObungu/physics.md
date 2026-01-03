There are some important equations and ideas to consider when analysing circuits
# Important Mathematical Equations
$$
\begin{gather*}
I = \frac{\Delta Q}{\Delta t} \\ \\
V = \frac{W}{Q} \\ \\
P = VI \qquad P=IR^{2} \qquad P = \frac{V^{2}}{R} \\ \\
V = IR 
\end{gather*}
$$
## Ideas
###  Series Circuit
- The the total p.d across the circuit is the sum of the individual p.d.s of components: $V = V_{1} + V_{2} + V_{3}\dots$ (Kirchhoff's second law)
- The current $I$ in each component is the same
- The total resistance $R$ of the combination is given by $R = R_{1} + R_{2} + R_{3}$

### Parallel circuit
- The p.d across each branch and resistor is the same
- The current is the sum of the individual currents: $I = I_{1} + I_{2} + I_{3}\dots$ (Kirchhoff's first law)
- The total resistance $R$ is given by $\frac{1}{R}= \frac{1}{R_{1}} + \frac{1}{R_{2}}+\frac{1}{R_{3}\dots}$

# Worked Example 
![[Pasted image 20260103193758.png]]
![[Pasted image 20260103193750.png]]
1. Calculate the total resistance of the resistors in parallel:
$$
R = (12^{-1} + 18^{-1})^{-1} = 7.2
$$
2. Calculate the total resistance of the circuit:.
$$
R = R_{1} + R_{2} = 10 + 7.2 = 17.2
$$
Use Kirchhoff's first and second law to determine the current in the circuit:
(Kirchhoff's second law - $\sum \varepsilon=\sum V$) and (Kirchhoff's first law current -  current is equal in a series circuit )
$$
\begin{gather*}
1.5 + 1.5 = V  \\ 
\implies 3 = I(17.2) \\ \\
I = 0.174
\end{gather*}
$$
3. Using $V=IR$ to calculate the p.d across the resistor:. 
$$
V = 10(0.174)) = 1.7V (2 s.f)
$$

 