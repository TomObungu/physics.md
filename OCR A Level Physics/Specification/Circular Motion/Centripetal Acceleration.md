Moving in a circular path results in the direction of continuously changing. As a result, your velocity is changing even if you travel at a constant speed. This means objects following a circular path must be accelerating.

## Force acting towards the center of motion
Any accelerating object requires a net force to be acting on it.
Any force that keeps a body moving with a uniform speed along a circular path is called a centripetal force. 

For example a rollercoaster with a loop in it. The source of the centripetal force comes from your weight and the normal contact force and your seat. 

Types of centripetal forces include a gravitational attraction for a satellite in orbit around a planet, friction for a car going around a bend, tension in a string or a magnet changing the polarity of an object. 

![[Pasted image 20250910003404.png]]

## Angular and linear velocity
At any point on a circular path, the linear velocity is always at a tangent to the circular path. 

In one complete rotation, the distance travelled is the circumference of the circle, and the time is the period T. Therefore:
$$
v=\frac{2\pi r}{T}
$$
we can expressed $\omega=\frac{2\pi}{T}$ we can express the speed (linear velocity) as 
$$
v=r\omega
$$
For objects with the same angular velocity. The linear velocity is directly proportional to the radius. 
$$
\begin{gather*}
v \propto r \\ 
v = kr
\end{gather*}
$$
An object may have the same angular velocity as another but if the other object has a greater radius, it will have the greatest linear velocity.
![[Pasted image 20250910004800.png]]

## Centripetal Acceleration
The acceleration of any object travelling in a circular path at constant speed is called the centripetal acceleration. This acceleration always acts towards the center of the circle, much like centripetal force.

The centripetal acceleration $a$ depends on the speed of the object, $v$, and the radius $r$ of the circular path. As an object travels, the faster the car travels the greater the acceleration. This is same is true if the radius of the motion of travel is smaller. The centripetal acceleration is given by the equation:
$$
a=\frac{v^{2}}{r}
$$
Combing this with the equation $v=\omega r$ gives:
$$
\begin{gather*}
a=\frac{(r\omega)^{2}}{r} \\
= \frac{r^{2}\omega^{2}}{r} \\
= \omega^{2}r
\end{gather*}
$$
## Work example
*Calculate the centripetal acceleration of a person standing on the equator as the Earth rotates. The radius of the Earth =6370km. The period is 24hours =86400 second*

We can determine the acceleration using either $a=\frac{v^{2}}{r}$ or $a=\omega^{2}r$

### Method 1
1. $$
\begin{gather*}
a=\frac{v^{2}}{r} \\ \\
v=\frac{2\pi r}{T}=\frac{2\pi \times 6370 \times 10^{6} \times r}{86400} = 463 \\ \\
a=\frac{463^{2}}{6370 \times 10^{6}} = 3.37 \times 10^{-2}
\end{gather*}
$$
### Method 2
$$
\begin{gather*}
a=\omega^{2}r \\ 
\omega=\frac{2\pi}{T} \\ 
\omega = \frac{2\pi}{86400} = 7.27 \times 10^{-5} \\
a = (7.27\times 10^{-5})^{2} \times 6370 \times 10^{6} = 3.37\times 10^{-2}
\end{gather*}
$$

## Deriving $a=\frac{v^{2}}{r}$
The object moving at constant speed $v$ subtends angle $\delta \theta$ in short time $\delta t$ 
![[Pasted image 20250910013801.png]]
By definition:
$$
\delta \theta = \frac{\delta x}{r}
$$
As the velocity at A is $V_{A}$ and the velocity at B is $V_{B}$. The two velocities are different as the direction has changed. Thus the acceleration is:
$$
a=\frac{\delta v}{\delta t}
$$
If the distance between A and B is very small then the displacement from A to B, $\delta x$ is almost a straight line and can be expressed as 
$$
\delta x=v\delta t
$$
Substituting this into $\delta\theta=\frac{\delta x}{r}$ gives 
$$
\delta\theta = \frac{v\delta t}{r}
$$
The velocities of the circular motion can be represented in the arc and segment of the circular motion path:
![[Pasted image 20250910014553.png]]
$\delta\theta$ must also be the angle between the velocities $V_{a}$ and $V_{B}$, so we have a second expression for $\delta\theta$ as long as the velocity is constant and so the magnitude of v is also constant.

Since v is constant, $V_{B} = V_{A}$ thus the the velocity can be represented as v. Thus
$$
\delta\theta = \frac{\delta v}{v}
$$
Equating the two equations for $\delta\theta$ gives:
$$
\begin{gather*}
\delta\theta = \frac{v\delta t}{r}=\frac{\delta v}{v} \\ \\
\frac{v^{2}}{r} = \frac{\delta v}{\delta t}=a
\end{gather*}
$$
where a is the centripetal force for an object moving at constant speed v in a circular path of radius r.