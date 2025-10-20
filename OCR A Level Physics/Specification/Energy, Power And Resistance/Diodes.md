[[I-V Characteristics]] [[Circuit Diagrams]]
A diode only allows current in one particular direction. This is because diodes are made of semiconducting material that is negatively charged at one end and has a positively charged end with holes for the electrons to enter. However due to positive charge attracting the negative electrons causing them to pass through the holes. The electrons cannot renter back into the area of negative charge due to repulsion. Once the electrons enter through the hole through the positive part in the diode, they continue off the rest of the circuit and the flow of electrons continues.

![[Pasted image 20250930224721.png]]
## Why
https://www.youtube.com/watch?v=btOIDQeMrMg
https://youtu.be/O8M2z2hIbag?si=-nFijkLVIOLcl_fu&t=777
This is because the semiconductor material containing impurities through the process of doping. This causes one side to positive charge and the other to have negative or p and n for short. 
![[Pasted image 20250930225021.png]]
In the n region there are lots of free electrons. In the p region. The region is missing some electrons. However it has a lot of 'holes' that the electrons can 'sit in'. As the holes are positively charged. 
![[Pasted image 20250930231011.png]]
To acheieve this: we typically use silicone which has four electrons on the outer shell universally. For the n type layer, the silicone has added impurities like phosphorus through doping. Phosphorus has an additional electron on the outer shell. This electron becomes delocalised and is free to move to other atoms:
![[Pasted image 20250930231517.png]]
For the p type layer. Another material like aluminium is doped to into the silicon, however the  aluminium has 3 electrons on the outer shell. Thus this means there is a 'hole' for an additional electron to move to. Due to the lack of electrons, this region can be classified as positively charged.![[Pasted image 20250930231615.png]]
This all in all forms a region with two many electrons and a region with lesser electrons. These two regions join to form a pn junction. This joins to form a depletion region 
![[Pasted image 20250930232015.png]]
This forms the depletion region in which the 'holes' move to n type layer and the electrons move to the p-type layer to fill the 'holes'
![[Pasted image 20250930232123.png]]
![[Pasted image 20250930232131.png]]
However this swapping over will create a barrier with a slightly positively charged region and a slightly negatively charged region. This region creates an electric field that prevents more electrons from moving across:
![[Pasted image 20250930232335.png]]
Thus when the p.d is high enough, the electrons will flow and barrier will increase and keep alternating to form a forward bias:
![[Pasted image 20250930232533.png]]
However if the voltage is too small, then there will not be enough p.d to overcome this barrier:
![[Pasted image 20250930232611.png]]
## Light-emitting diode (LEDs)
Some diodes are made of a material that emits light when they conduct. These LEDs emit light of a single specific wavelength. 

## Why
In the nucleus of an atoms. In the solid representation model. There are certain bands around the nucleus in which electron orbit and the electron can be freed from the orbit of atoms shell. This band at which the electron can be freed is called the conduction band. The orbit of electron is called the valence band.
![[Pasted image 20250930233458.png]]

In conductors the conduction band is very close to the valence band. In semiconductors the conduction band is a short distance away from the valence band. In insulators the conduction band is far away from the valence band.
![[Pasted image 20250930233437.png]]

In a silicone semiconductor. The free electrons in the n-type region are jumping from the conduction band of the phosphorus into the valence bands of the aluminium atoms. Or in other words, into the 'holes' of the p-type region. 
![[Pasted image 20250930233419.png]]
However the further away the band of orbit is from the nucleus of the atom, the more energy the band of orbit requires. However in order for the free electrons to jump to the lower valence band of the alluminium atoms, the electrons need to to lose some energy. In order to lose energy. The electrons release a photon:
![[Pasted image 20250930233649.png]]
In silicone, the electron needs to lose 1.1 eV of energy to be accepted into the valence band. This energy roughly translates to a wave length of 1117nm which is infrared light.
![[Pasted image 20250930233908.png]]
![[Pasted image 20250930233919.png]]
For different types of semiconductors, the energy required for the electron to jump to the valence band will determine the wavelength of light produced.
![[Pasted image 20250930234233.png]]
Once red, green and blue photon emitting LEDs were produced, this then made it possible to produce white light.


LEDs are very efficient and take very little energy to run. Because of this they can be used to indicate direction of current through a particular part of a circuit.


![[Pasted image 20250901105923.png]]

## I-V Characteristic for a diode
- The potential difference across a diode or LED is not directly porptional through it. This means:
	- A diode does not obey Ohm's law - It is a non-ohmic conductor
	- The resistance of the diode is not constant
- Diodes behavior depends on polarity
![[Pasted image 20250901111212.png]]

![[Pasted image 20250901111224.png]]
At A the resistance of the diode is very high. At B as the p.d increase, the resistance gradually starts to drop. For a silicone diode this happens around 0.7V. This value of p.d in which the resistance starts to drop in a diode is called the threshold p.d

# Rms
With an A.C current, the D.C equivalent of the p.d is calculated by the peak voltage, $V_{rms}=\frac{V_{0}}{\sqrt{ 2 }}$
![[Pasted image 20250930221057.png]]This is the same for current $I_{rms}=I_{\frac{0}{\sqrt{ 2 }}}$

## Why
https://www.youtube.com/watch?v=3Et8xqC-764
In DC, since the current is constant through the circuit, it possible to just multiply, this magnitude of current and voltage to get the power output of the supply.
![[Pasted image 20250930221808.png]]

However with an alternating p.d. The voltage and current is constantly oscillating. Due to this it is not possible to directly multiply the peaks of the current and p.d form the graph. This is because if we were to multiply the mean, due to peaks being the magnitude but negative and positive, the averages will cancel out to be 0. However we can't just take the peaks of the current and p.d as this will only measure the power only at the point in time when the p.d and current are at their peaks.

From knowing that, we must take an alternate approach. Knowing that from $P=VI$. It is possible to graph the $P$ for each value of current and p.d on a separate graph without worrying about the negative values of p.d and current due to negative multiplication yielding a positive result. 
![[Pasted image 20250930221654.png]]
![[Pasted image 20250930222328.png]]
Once we calculate the mean power over one cycle. It is possible to see that the average power through the graph is the half the peak power: ![[Pasted image 20250930222713.png]]
![[Pasted image 20250930222721.png]]
![[Pasted image 20250930222734.png]]
![[Pasted image 20250930222740.png]]
![[Pasted image 20250930222827.png]]
![[Pasted image 20250930222842.png]]