+Electronic devices take in alternating voltage and convert them into smooth direct voltage of about $5V$. This smoothing of voltage is achieved with a network of components including capacitors.

A battery provides constant e.m.f, $V_{0}$ , the capacitor has capacitance $C$ and the resistance has resistance $R$. When the switch closes, charge in the capacitor increases. Due to Kirchhoff's law, the p.d $V_{R}$ across the resistor and the p.d $V_{C}$ across the capacitor must add up to $V_{0}$.  So $V_{R}$ must decrease as $V_{C}$ increases with time. After some time, the capacitor will be fully charged with a p.d of $V_{0}$ and $V_{R}$ will be zero. When this happens $I$ in the circuit will be $0$.
![[Pasted image 20251127234939.png]]
# Important equations
The current $I$ in the circuit decreases exponentially and is given by:
$$
I = I_{0}e^{-\frac{-t}{CR}}
$$
Where $I_{0}$ is the initial current before the capacitor was charged at $t=0$. As well as that, the p.d across the resistor also decreases exponentially to time and hence:
$$
V_{R} = V_{0}e^{-\frac{-t}{CR}}
$$
At any time $t$, $V_{0}=V_{R}+V_{c}$:
![[Pasted image 20251127235747.png]]
Thus:
$$
V_{C} = V_{0}-V_{0}^{\frac{-t}{CR}} \qquad V_{C} = V_{0}\left( 1-e^{\frac{-t}{CR}} \right)
$$
From this, we can deduce:
- The equation $x=x_{0}\left( 1-e^{\frac{-t}{CR}} \right)$ can be used for the charge of the capacitor or the voltage across the capacitor
- At any time $t$, the p.d across the the components adds up to $V_{0}$ that is $V_{0}=V_{R}+V_{C}$
