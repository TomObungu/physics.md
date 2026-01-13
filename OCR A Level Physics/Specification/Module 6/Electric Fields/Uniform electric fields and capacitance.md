## LCD Displays
Some calculators and digital clocks use liquid crystal displays. The display is formed by applying electric fields across the display. When there is a current across the conductive later, the liquid crystals in the layer respond to the current's uniform electric field and are polarised. This allows light to pass between the gaps in the crystals. When the the electric field is removed, the crystals go back to their randomly orientated state and the window darkens. 
![[Pasted image 20251208161146.png]]

# Electric field between two parallel plates
Two oppositely charged parallel plates produce a uniform electric field in the region between the plates.

For an ideal parallel-plate capacitor, the electric field between the plates is uniform, however near the edges (Fringing Field): The field lines curve outwards at the edges of the plates.
![[Pasted image 20251208161430.png]]
 The electric field strength $E$ for the arrangement is uniform and is related to the $V$ across the plates and their separation $d$.  A small test charge $Q$ will experience a constant force $F$ given by the equation $F=EQ$.  The charge will gain energy as it moves from the positive plate to the negative plate. 

Since the definition of $p.d$ is equal to the work done per unit charge, and that work done $W$ is also the product of force and distance $d$, therefore:
$$
\begin{gather*}
V = \frac{W}{Q} \\
W = Fd \\
F = EQ \\ \\
V = \frac{E\cancel{ Q }d}{\cancel{ Q }} \\ \\
V =Ed
\end{gather*}
$$
This equation can be simplified to this form:
$$
E = \frac{V}{d}
$$
This equation only works for parallel plates with uniform electric fields. 

This equation is beneficial as it only requires a voltmeter to measure $V$ and a ruler to measure $d$ in order to determine the electric field strength. 

For cases other than this you must use $E = \frac{F}{Q}$

The Unit for Electric Field Strength is $NC^{-1}$ but the equation shows that you can also use $Vm^{-1}$.

# Worked Example
![[Pasted image 20251208162136.png]]
For this problem as plates are parallel it possible to use $E=\frac{V}{d}$ to calculate the electric field strength and then $F=EQ$ to work out the force:

$$
E = \frac{V}{d} = \frac{3.6\times 10 ^{3}}{1.2 \times 10^{-2}} = 3 \times 10 ^{ 5} Vm^{-1}
$$
Using $e$ as the value for the charge of an electron.
$$
F = EQ = (3 \times 10 ^{5})(1.60 \times 10 ^{-19}) = 4.8 \times 10 ^{-14}
$$
Finally using $F=ma$ to work out the acceleration and taking the mass of an electron to be $9.11 \times 10 ^{ -31}$
$$
F=ma =\quad a =\frac{F}{m} = \frac{4.8 \times 10 ^{-14}}{9.11 \times 10 ^{-31}} = 5.3 \times 10 ^{ 16}  m s ^{-2}
$$

# Parallel plate capacitor
The capacitance of a plate capacitor depends of the separation $d$ between the plates, the area of overlap between the plates and the insulator used between the plates. For plates in a vacuum or air, experiments show that the capacitance is proportional to the area $C \propto A$ and inversely proportional to the separation between the plates $C \propto \frac{1}{d}$. Therefore:
$$
\begin{gather*}
C \propto \frac{A}{d} \\ \
C = k \frac{A}{d}
\end{gather*}
$$
The constant of proportionality of this relationship is the permittivity of free space free space $\varepsilon_{0}$ . Thus the equation for the capacitance of a parallel plate capacitor is:
$$
C = \frac{\varepsilon_{0} A}{d}
$$
## But what is permittivity? 
Permittivity is the measure of a material's ability to oppose the formation of an electric field within. It quantifies how easily an electric field can be permitted to form in a substance.

Thus, permittivity described the effect of material determining the electric field intensity in response to charge. 

This arises from the derivation of electric field strength being $E \propto \frac{Q}{4\pi r^{2}}$. The constant of proportionality depends on the material and we can denote it as $\epsilon$ :
$$
\begin{gather*}
E \propto \frac{Q}{4\pi r^{2}} \\ \\ 
E =\frac{Q}{4\pi r^{2}} \frac{1}{\epsilon}
\end{gather*}
$$

This means that for an electric charge in a vacuum, the value value of $\epsilon$ is roughly equal to $\varepsilon_{0}$ as show in the textbooks.

### Relative permittivity
When the insulator or dielectric is anything other than a vacuum or air, the equation permittivity is always greater than $\varepsilon_{0}$, thus we use the term relative permittivity $\varepsilon_{1}$: Thus the permittivity of the insulator can be defined as:
$$
\varepsilon = \varepsilon_{1}\varepsilon_{0}
$$
Thus when factoring in relative permittivity, the equation for capacitance can be written as:
$$
C = \frac{\varepsilon A}{d}
$$
Or:
$$
C = \frac{\varepsilon_{1}\varepsilon_{0}A}{d}
$$
Below is a table of relative primitiveness $\varepsilon_{1}$ for different materials 
![[Pasted image 20251208165225.png]]
