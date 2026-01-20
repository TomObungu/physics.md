A simple transformer consists of a laminated iron core, an primary (input) and  a secondary (ouput) coil. An alternating current is supplied to the primary coil. This produces a varying magnetic flux within the iron core. The secondary coil which wound around the same coil, is linked by changing flux. The iron core ensures that all the magnetic flux created by the primary coil links the secondary coil and none is lost. Due to Faraday's law of electromagnetic induction, a vary e.m.f is produced across the ends of the secondary coil. 
![[Pasted image 20260120215801.png]]

The input voltage $V_{p}$ and the output voltage $V_{s}$ are related to the number $n_{p}$ of turns on the primary coil and number of turns $n_{s}$ of on the secondary coil by the turn-ratio equation:
$$
\frac{n_{s}}{n_{p}} = \frac{V_{s}}{V_{p}} \text{ for an ideal transformer}
$$
An ideal transformer means the transformer is 100% efficient. 
- A step-up transformer has more turns on the secondary than on the primary coil, $V_{s} > V_{p}$
- A step-down transformer has fewer turns on the secondary than on the primary coil, $V_{p} > V_{s}$
# Worked example
A step-down transformer changes 230V mains voltage to 5.0V. The transformer has 920 turns on its primary coil. Calculate the number of turns on its secondary coil.
$$
\begin{gather*}
\frac{n_{s}}{n_{p}} = \frac{V_{s}}{V_{p}} \\ \\
n_{s} = \frac{V_{s}}{V_{p}}(n_{p})  = \frac{5(920)}{230}= 20 \text{ turns}
\end{gather*}
$$
# Experimenting with transformers
An arrangement below shows how investigate transformers. A multimeter set to 'alternating voltage' can be used to measure input $V_{p}$ and output $V_{p}$ voltages or use an oscilloscope instead. Thin insulated copper wires are used to make primary and secondary coils. Changing the number of turns on one or both allows observation of what happens to $V_{s}$ for a fixed value of $V_{p}$ and vice versa.


# Efficient transformers
For a 100% efficient transformer, the output power from the secondary coil is equal to the input power into its primary coil. Therefore:
$$
V_{s}I_{s} = V_{p}I_{p}
$$
or:
$$
\frac{I_{p}}{I_{s}} = \frac{V_{s}}{V_{p}}
$$

Thus in a step up transformer, the voltage is stepped up but the current is stepped down. Increasing the voltage by a factor of 100 will decrease the output current by a factor of 100. Similarly, in a step-down transformer, the voltage is stepped down and the current is stepped up. 

## Making efficient transformers
- Using low resistance windings to reduce power loss due to heating effect of the current
- Making a laminated core with layers of iron separated by an insulator helps to minimise currents induced in the core itself (eddy currents)
- The core is made of iron, allowing easy magnetisation and demagnetisation

# The National Grid
The national grid consists of transformers and cables on pylons and underground. All a.c generators in large power stations produce an alternating voltage of about 25kV at a precise frequency of 50Hz.
![[Pasted image 20260120221229.png]]
Electrical power is transmitted at a high voltage to minimise heat losses in the transmission cables. To deliver a power $P_{0}$ at a voltage $V$, the current $I$ required is given by the equation $I = \frac{P_{0}}{V}$. For transmission cables of resistance $R$, the power loss $P_{L}$ due to heating in the cables is given by:
$$
P_{L} = I^{2}R = \frac{P_{0}^{2}R}{V^{2}}
$$
The higher the transmission voltage $V$, the smaller are the power losses through heating $\left( P_{L} \propto \frac{1}{V^{2}} \right)$
