An e.m.f is induced in a circuit whenever there is a change in the magnetic flux linkage.

# Faraday's law
The magnitude of the induced e.m.f is directly proportional to the rate of change of magnetic flux linkage.
$$
\varepsilon \propto \frac{\Delta(N\phi)}{\Delta t}
$$
where $\varepsilon$ is the induced e.m.f and $\Delta(N\phi)$ is the change in magnetic flux linkage and $\Delta t$ is a time interval

This relationship can be written as an equation with constant of proportionality equal to -1. Therefore:
$$
\varepsilon = -\frac{\Delta(N\phi)}{\Delta t}
$$
The reason for the constant of proportionality being -1 is due to Lenz's law and conservation of energy.
# Worked Example 1
![[Pasted image 20260119193825.png]]
Calculate $\Delta \phi$ by realising that the value of $\phi$ will be when it fully removed from the field in a time 80ms. The initial value of $\phi$ will be $\phi = BA\cos\theta$, where $\theta=0$. 
$$
\Delta \phi = 0 - (2000)(1.4 \times 10^{ -2})(0.3) = -8.40 \times 10^{-2}
$$
Calculate the induced e.m.f $\varepsilon$ using Faraday's law:
$$
\varepsilon = \frac{\Delta \phi}{\Delta t} = \frac{8.40 \times 10^{-2}}{80 \times 10^{-3}} = 1.1V
$$


# Lenz's law
Consider a coil and magnet arrangement such that the wires are connected together so that induced currents are large enough to create their own strong magnetic fields.
![[Pasted image 20260119194300.png]]

When the magnet and the end of $X$ are brought close together, in the upper image, the induced current is such that the end of X of the coil has a north polarity. 

(My guess on this that the electrons within the wire experience a magnetic force $F=Bev$ due to the relative motion $v$ of the magnet. This causes the electrons to move in the direction you are pushing the magnet, thus inducing a counterclockwise current. As electrons move away as you push the north of the magnet towards the solenoid, this mimics repulsive behaviour and so that region behaves like a north pole.)

Work is done to push the magnet towards the coil. The work done on the magnet is equal to the electrical energy produced in the coil. The end $X$ cannot be a south pole. If it could be then, the principle of conservation of energy would be violated. This is because an attraction between the coil and the magnet would create electrical energy from nowhere. 

When the magnet is pulled away from the coil, the motion of the magnet is opposed so that you must do work. The end $X$ of therefore has a south polarity and the induced e.m.f and current are reversed. 

Lenz's law is an expression of this scenario of conservation of energy.

Lenz's law states the direction of the induced e.m.f or current is always such as to oppose the change producing. 

The negative sign in the equation for Faraday's law is a mathematical way of expressing Lenz's law:
$$
\varepsilon = -\frac{\Delta(N\phi)}{\Delta t}
$$

# The alternating current generator

A simple a.c generator consists of a rectangular coil of cross-sectional area $A$ and $N$ turns of coil rotating in a uniform magnetic field of flux density $B$. The flux  linkage for the coil is:
$$
MFL = N\phi = N(BA\cos\theta) = BAN\cos\theta
$$
![[Pasted image 20260120112227.png]]
As the coil rotates at a steady frequency, the flux linkage changes with $t$. This variation is referred to sinusoidal and is causes by the changing $\cos\theta$ factor. 

According to Faraday's law, the induced e.m.f $\varepsilon = - \frac{BAN\cos\theta}{\Delta t}$
- The magnitude of the gradient from the magnetic flux linkage against time graph is equal to the induced e.m.f
- For a given generator, $B$, $A$ and $N$ are all constant, therefore:
- $$
\varepsilon = - \frac{\Delta \cos\theta}{\Delta t}
$$

The lower graph in figure 5 shows the variation of e.m.f $\varepsilon$ with time $t$. The maximum induced e.m.f is directly proportional to:
- magnetic flux density $B$
- cross-sectional area $A$
- the number of turns $N$
- frequency $f$ of the rotating coil

## Mathematical treatment
If the MFL is changing at rate proportional to $\cos\theta$, then $\frac{d(N\phi)}{dt}$ is proportional to $-\sin\theta$. However due to Lenz's law negating the gradient in Faraday's law $\varepsilon = - \frac{\Delta(N\phi)}{\Delta t}$, $\frac{d(N\phi)}{dt}$ is proportional to $\sin \theta$, hence the standard sine wave seen in a.c current. 

The amplitude of this wave is the maximum induced e.m.f. It is then possible to convert this into a d.c current metric using a rectifier and peak voltage $$V_{rms}=\frac{V_{0}}{\sqrt{ 2 }}$$
