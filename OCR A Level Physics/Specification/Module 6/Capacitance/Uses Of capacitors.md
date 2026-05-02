Unlike chemical energy cells, capacitors cannot store a great deal of energy in a small volume. As well as that capacitors cannot store energy for large amounts of time. However, capacitors are capable of releasing energy very quickly and generating a high power output.

A joule of energy is stored in a normal capacitor however all of the energy is released in $1ms$. The gives a power output of about $1kW$ This is what happens in a camera flash.  

As well as that capacitors can be used to proved back-up power for computers and emergency lighting when the mains supply cuts out briefly.
## Power and Capacitors
### Example 1
A camera flash uses 1.2F capacitor and a cell of e.m.f 1.5. Calculate the maximum power from a flash of 1.1ms.
1. Calculate the energy/work of the capacitor:
$$
W = \frac{1}{2}CV^{2} = \frac{1}{2}(1.2)(1.5)^{2} = 1.35J
$$
2. Use $P = \frac{W}{t}$ to calculate the power output of the capacitor
$$
P = \frac{1.35}{1.1 \times 10^{-3}} = 1227.272727\dots \approx 1.2 kW
$$

## Smoothing Capacitors
Household mains supply is supplied as alternating current. In order to convert this alternating voltage into a smooth direct voltage, a rectifier circuit is used:

![[Pasted image 20251128001046.png]]

Firstly, the diode is what allows current to flow in one direction only. However, the diode alone cannot provide a smooth direct current. If the circuit were only to contain the diode, then the voltage would consist of positive the positive region of the oscillating motion of the voltage:
![[Pasted image 20251128001244.png]]

However, adding the capacitor causes the output voltage to be smoothed out and almost becomes a direct voltage of constant value. This is done through a capacitor with a time constant $\tau = RC$ much greater than the period of the the alternating voltage.
![[Pasted image 20251128001619.png]]
In most cases the frequency of mains voltage is $50Hz$ giving a time period of $T = \frac{1}{50} = 0.02S$ thus in this case $RC\gg 0.02$

This smooth effect is cause by the capacitor charging up when going through a positive cycle of voltage. Once the voltage hits its peak voltage during the positive cycle, it starts to decrease. At the same time the capacitor starts to discharge.

Once the alternating voltage supply enters its negative phase, no voltage is present for the period of its negative cycle. However, as the capacitor stored charge, the capacitor will still continue to supply voltage, with supply of voltage decreasing at an exponential rate. However, as the time constant $RC$ is far greater than the period of oscillation of the voltage supply decreases very little before the voltage supply begins to rise to a positive cycle

# Ripple Voltage
For a conducting silicon diode with a threshold voltage of $0.7V$, the diode will allow the capacitor to charge every time time the alternating p.d is greater than $0.7V$. As soon as the input voltage starts to decrease, the capacitor, starts to discharge through the resistor. The rate of discharge depends on the time constant $CR$.

It is possible to calculate the voltage of this period in where the capacitor is discharging. This voltage is called the ripple voltage $V_{ripple}$. The ripple voltage is the difference between the maximum output voltage $V_{0}$ and the minimum output voltage.

From the diagram above, we can label the maximum output voltage $V_{0}$ as the the peak of the motion of voltage and the minimum point of voltage during discharging. The differences in those points is $V_{ripple}$
![[Pasted image 20251128003417.png]]

Assuming that the peak voltage $V_{0}\ll 0.7$ during this time and time constant $CR\gg T$. The ripple voltage will be the difference between the $V_{0}$ and the voltage of the capacitor:
$$
V_{ripple} = V_{0} - V_{0}e^{\frac{-t}{CR}}
$$
However for small values $t$, the period of the ripple is approximately equal to the period of oscillation. As well that for small values of $x$ $e^{-x}\approx 1-x$. Thus:
$$
\begin{gather*}
V_{ripple} = V_{0}\left( 1-e^{\frac{-T}{CR}} \right) \\ \\
V_{ripple} \approx V_{0}\left( 1-1+\frac{T}{CR} \right) \\ \\
V_{ripple} \approx \frac{V_{0}T}{CR}
\end{gather*}
$$
