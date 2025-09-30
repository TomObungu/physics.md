The resistance of a component in a circuit can be determined by measuring the current $I$ and the p.d $V$.

Resistance is the measure of how difficult it is for current to flow through a component in a circuit

## Why
It takes energy to push an electron through a component. For specific components like resistors, their molecular structure inhibits the flow electrons. This is due to the electrons constantly colliding with the atoms of the material that the resistor is made of as they flow through the component. This collision causes a transfer of electrical and kinetic energy ($eV=\frac{1}{2}mv^{2}$) from the electron into thermal energy (heat) which is dissipation. As well as that the material of components like resistors typically have a low number of de-localised electrons, so the source of charge is mainly from the incoming wire from the current. Thus there are little new electrons from the material. 

My question is, as they are losing this energy and thus in turn creating a difference in high and low potential between the component. How come they still have enough energy to move through the wire. What if the the component has a high resistance, and the electrons lose so much potential and in turn kinetic energy, to the point the electrons slow down a halt and do not make it to the other end of the component? Is this why branches with high resistance have a low current along side the fact that $\sigma=\frac{1}{\rho}$?

Well this is because, the electrons are continually accelerating due to the work that the electric field does on them. The electrons gain energy kinetic due to the electric field $eV=\frac{1}{2}mv^{2}$ but immediately collide with atoms of the resistive component. This causes the electrons to lose kinetic energy and then gain it again. This process happens millions of time as the electron travels through the wire. These collisions cause a transfer of electrical energy to heat. 

A high voltage will increase the joules of energy per unit charge of electrons. So initially as the electrons are about to pass into the component, they have a certain amount of energy but due to process described, of starting and stopping due to collisions. The electrons emerge out the other side of the component as they have only accelerated as much as the time between the last collision in the component and the time they exit the component back into the wire.

This is why high voltages can travel through insulators like human skin, as the charge carriers have enough electrical energy which transfers into kinetic energy energy (and therefore a higher mean drift velocity) the charge carriers have a strong accelerating force due to the high energy electric field. This causes the few electrons to  have strong force and literally rip electrons away from their atoms to create new free electrons and positive ions (plasma). These few electrons are then accelerated violently by the strong field, the electric field causes them to gain so much energy and knock more electrons loose. This energy repeats.
### The Ohm
An ohm is defined as the resistance of a component when a p.d of 1V is produced per ampere of current.
$$
1 \Omega = 1VA^{-1}
$$
### Ohm's Law
At constant temperature, the current in a wire is directly proportional to the potential difference across it.
## Temperature and resistance
For a tightly bundled metallic wire. The p.d across the wire remains constant at 1.5V, but the current in the wire decreases with time. The shape of the graph can be explained as the resistance decreasing with time.  
![[Pasted image 20250829082638.png]]
```desmos-graph
left = -0.1; right = 5; 
bottom = -1; top = 4;
---
y = \frac{2}{x+1} + 1
```
When the temperature of wire increases, the positive ions inside the wire have more internal energy and vibrate with greater amplitude about their mean positions. The frequency of the collisions between the charge carriers and ions increases and so the charge carriers do more work which in turn transfers more energy as they travel through the wire. 
![[Pasted image 20250929203714.png]]

## Variable resistor
The reason why a variable resistor works is due to each resistance "step" having an increase in wire length which is turn directly affects the resistance due to $R=\frac{\rho L}{A}$

![[Pasted image 20250929170111.png]]