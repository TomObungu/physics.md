# Producing a varying $V_{\text{out}}$
Using a pair of fixed resistors has the effect of splitting the the p.d of $V_{in}$ however what if you want to vary $V_{\text{out}}$? It is possible to do this by using a variable resistor. In the circuit below, increasing the resistance of the of the variable resistor will increase $V_{out}$ and vice versa
![[Pasted image 20260106090927.png]]

# Temperature sensing circuits - thermistor
Replacing the variable resistor with a thermistor allows $V_{\text{out}}$ to vary automatically depending on the temperature of the surroundings. 

As the temperature increases, the resistor of the thermistor decreases and so $V_{out}$ drops. In a scenario like this, $V_{out}$ may be connected to a heating supply to allow continual regulation of specific temperature conditions.
![[Pasted image 20260106091300.png]]

# Light sensing circuits - LDR
An LDR can be used in the same way as a thermistor, producing a potential divider that gives an output that depends on light intensity. 

As the light intensity increases, the resistance of the LDR falls and so the p.d across it decreases, $R_{2}$ receives a greater proportion of the p.d and so $V_{out}$ increases. Again, this can allow automatic light regulation e.g. Street lamps turning on as daylight fades. 


![[Pasted image 20260106091530.png]]


## The potentiometer
Many low-voltage electrical circuits that need a varying p.d use a potentiometer rather than a potential divider.

A potentiometer is a variable resistor with three terminals and a sliding contact. Adjusting the p.d between two of the terminals, giving a variable $V_{out}$. 

Potentiometers allow variance of resistance often by the dial sliding over a coil of wire. Each time, you slide the dial in a certain direction, the turns in the coil of the wire increase and the overall length of the wire the current has to travel increases. This increases resistance due to $R = \frac{\rho L}{A}$

When the contact is moved towards $\mathbf{A}$, $V_{out}$ increases until at $\mathbf{A}$ it is equal to $V_{in}$. When the contact is moved towards $\mathbf{B}$, $V_{out}$ decreases until at $\mathbf{B}$ it is at zero.

An advantage of a potentiometer is that they can be made very compact, making them useful for portable electronic devices. As well as that, they can be constructed so that the change in resistance is logarithmic or linear. 

![[Pasted image 20260106091812.png]]