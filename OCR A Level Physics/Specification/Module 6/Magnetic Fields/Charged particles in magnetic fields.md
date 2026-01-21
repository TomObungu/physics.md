## The aurora
The aurora borealis or northen lights and its southern equivalent of the auroro australis, occur when energetic charged particles from the Sun spiral down the Earth's magnetic field towards a polar region and collide with atoms in the atmosphere causing them to emit light.

![[Pasted image 20260113213946.png]]


# Circular tracks
The figure below shows the path of a single electron as it travels through a region of uniform magnetic field. The direction of magnetic field vertically upwards into to plane of the paper. is . The electron describes describes a circular path within the magnetic field because the magnetic force $F$, predicted by Fleming's left hand rule, experiences is perpendicular to its velocity - A centripetal force.
![[Pasted image 20260113220114.png]]
No work is done by the magnetic field on the electron because the the force is perpendicular to the velocity - This force has no component in the direction of travel and therefore the speed of the electron remains constant. 

To find the force $F$ acting on a charged particle of charge $Q$ moving at a speed $v$ at right angles to a uniform magnetic field of flux density $B$, consider a section of conductor, or a beam of charged particles. In a time $t$ , all the charged particles contained within the shaded region go through section $XY$. The length of the shaded region is $vt$, where $v$ is the speed of the charged particle. 
![[Pasted image 20260113220221.png]]

Thus the force $F$ on the conductor is given by:
$$
F = BIL
$$
Therefore:
$$
F = BI(vt)
$$
The current $I$ in is the rate of flow of charge. If there are $N$ charged particles, each of charge $Q$, in the shaded region, the current is given by the equation:
$$
I = \frac{NQ}{t}
$$
So the force acting on the conductor is given by:
$$
 F= \frac{BNQvt}{t} = BNQv
$$
Thus, The magnitude of the magnetic force $F$ experienced by a particle of charge $Q$ moving at right angles to the magnetic field is given by the equation:
$$
F = BQv
$$
For an electron or proton, $Q=e=1.6\times 10^{-19}C$, the equation may be written as:
$$
F = Bev
$$

## Going round
Consider a charged particle of mass $m$ cand charge $Q$ moving perpendicular to a uniform magnetic field of flux density $B$. The particle will describe a circular path of radius $r$. The magnetic force $BQv$ provides the centripetal force $\frac{mv^{2}}{r}$, therefore:
$$
BQv = \frac{mv^{2}}{r} \qquad or \qquad r =\frac{mv}{BQ}
$$
It is possible to determine the velocity of the particle using $v=\frac{2\pi r}{T}$, where $T$ is the period, to analyse the motion of the particle. 

## Worked example: Circular tracks
Electrons are travelling in a circular path at right angles to a uniform magnetic field. Show that the period of revolution $T$ of an electron is independent of the path or its speed, but depends on its mass, the magnetic flux density $B$ and the elementary charge $e$.

1. Write an expression for the centrpetal force on the elctron:
 $$
 \begin{gather*}
F=BQv \qquad F = \frac{mv^{2}}{r} \\ 
BQv = \frac{mv^{2}}{r} \implies BQ = \frac{mv}{r}
\end{gather*}
$$
2. Substitute $v = \frac{2\pi r}{T}$ and $Q=e$ into the expression above:
 $$
Be = \frac{2\pi rm}{Tr} = \frac{2\pi m}{T}
 $$
 3. Rearrange for $T$:
  $$
T = \frac{2\pi m}{Be}
$$
Therefore the period $T$ just depends on $m$, $B$ and $e$. 

# Velocity selector
A velocity selector is a device used in instruments such as a mass spectrometer to selected charged particles of a specific speed. 
![[Pasted image 20260113222531.png]]

Two oppositely charged parallel plates provide a uniform electric field of strength $E$. There is also a uniform magnetic field of flux density $B$ at right angles to the field. 

- The electric force on a charge particle of charge $Q$ is equal to $F=EQ$
- The magnetic force on the charged particle is equal to $BQv$, where $v$ is the speed of the particle


The magnitude of either $E$ or $B$ is adjusted so that the magnetic force and the electric force are equal in magnitude and in opposite directions. Therefore:
$$
EQ = BQv \implies v = \frac{E}{B}
$$
Thus only charged particles with specific speed $v$ will travel in a straight line and emerge from the slit $Z$.


# Mass spectrometers
Mass spectrometers measure the masses and relative concentrations of atoms and molecules. They can be used to detect the age of rocks and even to examine pharmaceuticals.  Below is a figure of the structure of a mass spectrometer:
![[Pasted image 20260113223135.png]]

Atoms from sample are ionised and accelerated through a potential difference. They pass through a velocity selector and emerge with the same speed $v$ before entering a uniform magnetic field of flux density $B$. The radius $r$ of the curvature of each ion is given by:
$$
r = \frac{mv}{BQ}
$$
For a singly ionised atoms, $Q=e$.

Since $r \propto m$, each different ion is deflected by a different amount onto the detector, the detector is connected to a computer programmed to show the relative abundance of each type of ion. 

# The Hall Probe
The figure below shows a thin slice of semiconductor of thickness $t$, width $d$ and current $I$. An external magnetic field of flux density $B$ is applied at right angles to the direction of the current. According to Fleming's left hand rule, the force experience by the electrons causes them to be deflected towards the right-hand surface, where they accumulate, leaving the left-hand surface of the semiconductor with fewer electrons. This is a difference in potential with voltage $V_{H}$. 
![[Pasted image 20260113223920.png]]
The probe must be aligned at right angles to the magnetic field for the effect to be strongest.
![[Pasted image 20260113223814.png]]

The accumulated electrons create a uniform electric field of magnitude $E$where:
$$
E = \frac{V_{H}}{d}
$$
Since $V=\frac{W}{Q}$, the work done to move the electrons from the one side of the semiconductor is $W = Fd = BILd$ . The total charge of the electrons equal to the number density multiplied by $e$ and $t$ and $d$. $Q = nted$of the semiconductor. The Hall voltage $V_{H}$ is given by the equation
$$
V_{H} = \frac{BILd}{nted} = \frac{BI}{nte}
$$
