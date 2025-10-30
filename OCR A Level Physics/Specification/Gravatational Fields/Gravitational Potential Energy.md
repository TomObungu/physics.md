The gravitational potential energy $E$ of any object with mass $m$ within a gravitational field is defined as the work done to move the mass from infinity to a point in a gravitational field. 

As from previous knowledge the gravitational potential accounts for cases when we are not near the surface of the Earth or for cases when the planetary mass of the point mass differs from our Earth. This means the values of $g$ will differ from $9.81$ and therefore we must use the gravitational potential to do calculations for $w$.

We can calculate the gravitational potential of the point mass using. 
$$
V_{g} = -\frac{GM}{r}
$$

and there we can then calculate changes in $GPE$ using the gravitational potential the secondary test mass $m$ - the object that we are measuring changes in energy on.

Therefore:
$$
E = mV_{g}
$$

## Important note
When calculating the gravitational potential, the value of $r$ will account for the radius to the surface of the planet plus the height above the surface.

This is the reason why the equation for $E=mV_{g}$ differs from $mgh$ as $h$ is accounted for in $r$ when calculating $V_{g}$

# Uniform gravitational field 
In a uniform gravitational field such as the one close to the surface of a planet. In order to change the gravitational potential energy of an object, its height must be changed. 

For example on the earth increasing the height from $AB$ will increase the the $GPE$, whereas moving form $A$ to $C$ will not result in a change in $GPE$ as the height is constant. 
![[Pasted image 20251030175856.png]]

Often in a uniform gravitational field, the value of $g$ for the point mass $M$ (the mass of the planet on which you are near the surface of) will be considered to be constant and therefore you can calculate the value of g for that planet using $g = -\frac{GM}{r^{2}}$ and the radius of the planet and substitute that into the familiar $E=mgh$ equation where you only account for the changes in height from the surface only. 

# Radial gravitational field
In cases where scale is astronomical or the point mass $M$ is significantly different a radial gravitational field is considered at the gravitational potential energy can be written as:
$$
E = mV_{g} = -\frac{GMm}{r}
$$
An change in $r$ results in a change in gravitational potential and so a change in gravitational potential energy.


# Graphs of force against distance
The area under a the **magnitude** of the gravitational force $F$ against distance $r$ is the work done to move a mass 'up' from $B$ to $A$. This is because gravitational potential is negative and therefore increasing the height towards infinity will actually draw it closer to $0$. 

![[Pasted image 20251030180810.png]]

The intuition behind is this due to the gravitational field strength becoming weaker (tending to 0) as the distance from the planet increases

Therefore if we take the magnitude of the gravitational force $F$ against the distance $r$ we will get the work done which is the $GPE$
![[Pasted image 20251030180851.png]]

# Escape velocity
In order to escape the gravitational field of a mass like a planet, an object must be supplied with energy equal tot he gain in gravitational potential energy need to lift it out of the field.

Consider a projectile of mass $m$ fired upwards. If we ignore air resistance, the kinetic energy of the projectile is transferred into the gravitational potential energy as it rises. In order for the projectile to have just enough energy to leave the gravitational field, the loss of kinetic energy must be equal to the gain in gravitational potential energy:

Therefore equating $KE$ to $GPE$, we can see the test masses $m$ cancel out:
$$
\frac{1}{2}mv^{2} = \frac{GMm}{r}
$$
And therefore the minimum velocity $v$ for this condition to be met is called the escape velocity. We can see that the escape velocity is independent of the test mass $m$ and entirely dependant on gravitational field strength of and subsequently the point mass $M$.

But obviously a more massive object will require more work to accelerate it to a higher velocity but the velocity it must reach in order to to reach escape the velocity of the planet's point mass $M$ does not depend on the mass of the object:
$$
v = \sqrt{ \frac{2GM}{r} }
$$

## Escape velocity of gas atoms in molecules
In order for a gas molecules to escape the gravitational field of a planet, an individual atom or molecule from a has must have a minimum speed equal to $\sqrt{ \frac{2GM}{r} }$

The average kinetic energy of a single has atom or molecule is given by $\frac{1}{2}mv^{2}=E_{k}$ where $E_{k}=\frac{3}{2}kT$. Solving for $v$ will give the root mean speed of the molecules for a given temperature $T$. 

Thus it is possible that some molecules will be travelling faster than this r.m.s. Molecules travelling with a speed greater than $\sqrt{ \frac{2GM}{r} }$ can escape.

## Green box questions:
![[Pasted image 20251030182240.png]]
1. The escape velocity is just $v=\sqrt{ \frac{2GM}{r} }$ and we take $M$ to be $6\times 10^{24}$: and the radius of the Earth $r$ to be $6400km$ 
$$
v = \sqrt{ \frac{2(6.67 \times 10 ^{-11})(6\times 10 ^{24})}{6400\times 10^{3} }} = 11 183.134 = 11.186 kms^{-1} = 11.2kms^{-1}
$$
2. Using k = $1.38 \times 10^{-23}$as the Boltzmann constant: 
$$
\begin{gather*}
E_{k} = \frac{3}{2}(1.38\times 10 ^{-23})(20+273) = 6.0551\times 10^{-21} = 6.01 \times 10^{-21} J \\ \\
\text{Solving for } v \text{ to get } c_{r.m.s} : \\
6.01\times 10 ^{-21} = \frac{1}{2}mv^{2} \\ \\
v = \sqrt{ \frac{2(6.01\times 10 ^{-21})}{5.3\times 10^{-26} } } = 480ms ^{-1} \\ \\
\text{This speed is significantly less than the escape velocity} \\ 
\text{and thus the mean of oxygen molecules remain in the Earth's atmosphere}
\end{gather*}
$$
