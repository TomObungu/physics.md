The clock tower at Big Ben is an example of a pendulum clock. It is an isochronus oscillator.  This means that time taken to oscillate is constant regardless of the amplitude. The pendulum is 4.4m long and has a mass of 310kg. However, adding a single coin to the top of the pendulum has the effect of slightly lifting the pendulum's centre of gravity, reducing the duration of the swings by 400ms per day. 

## Graphs to describe SHM
The graph of displacement in an object in SHM has a sinusodial shape. If no energy is transferred to the surroundings, then the amplitude A of each oscillation remains constant. (However air resistance would be present on Earth, thus amplitude will decrease with every oscillation)

Below is variation of displacement $x$ with time $t$ . At zero displacement, the pendulum is at or moving through its equilibrium position. The maximum displacement is at the top of the string. 

![[Pasted image 20250916205425.png]]

Holding the pendulum at maximum displacement then letting go of it will produce a cosine shaped graph.

Pushing the pendulum at equilibrium displacement will produce a sine graph.

The gradient of displacement-time graph is equal to the velocity $v$ of the oscillator. At maximum displacement, **the velocity is zero** because the gradient of the graph is zero. This is also because at maximum displacement, the pendulum has momentarily stopped before it returns towards equilibrium position. 

Below shows how velocity $v$ varies with time $t$ and how acceleration $a$ varies with time. The acceleration $a$ can be determined from the gradient of the velocity-time graph. 

### Velocity
![[Pasted image 20250916205439.png]]
### Acceleration
![[Pasted image 20250916205458.png]]

#### Synoptic note with trigonometric derivatives

If the starting motion of the oscillator e.g A pendulum, has the shape of a cosine graph i.e When it is held at maximum displacement and released. Since:
$$
\begin{gather*}
x = \cos\theta dt\\ 
v=\frac{dx}{dt} = -\sin\theta\\ \\
a=\frac{dv}{dt} = -\cos\theta
\end{gather*}
$$
Thus, the shape of each graph can explained and predicted due the nature of derivatives.
The same can be explained for a oscillator pushed from equilibrium:
$$
\begin{gather*}
x=\sin\theta dt \\ 
v=\frac{dx}{dt} = \cos \theta \\ 
a=\frac{dx}{dt} = -\sin\theta 
\end{gather*}
$$

## Mathematical treament of SHM
The defining equation for SHM is $a=\omega^{2}x$. The displacement x of a simple harmonic oscillator varies with time $t$ in sinusoidal manner. Therefore:
$x=A\cos(\omega t)$ or $x=A\sin(\omega t)$

These equations are the solutions to the equation $a=-\omega^{2}x$. 

### Worked example
*A simple pendulum is released 30cm from its equilibrium position and completes one oscillation every 1.4s. Calculate its displacement 6.2s after it was released.*

 1. $$
\omega=2\pi  \frac{1}{1.4} = 4.5 rads ^{-1}
$$
2. $$
x=0.3\cos(4.5\times 6.2) = -0.27
$$

## Velocity
In SHM velocity $v$ varies with time. As $\omega$ is increased with no change in amplitude. The oscillator will be travelling the same distance in a shorter time interval.  Therefore $v$ is increased. As $v$ increases, the gradient of the x-t graph will increase.

The affect of increasing the amplitude $A$ of the oscillator on an isochronous oscillator, it will travel a greater distance in the same amount of time. Hence the maximum velocity will also increase. Thus velocity of an isochronus oscillator can be calculated using:

$$
v=\pm\omega\sqrt{ A^{2}-x }
$$

The velocity at any particular displacement has a positve or negative value, depending on the direction in which the oscillator is moving. 

From this equation, it follows that velocity can vary between zero at $x=A$ to its maximum values, $\pm v_{max}$ , at the equilibrium position. At equilibrium position, $x=0$ , so the equation becomes:
$$
V_{max} = \omega A
$$
## Worked example: The velocity of an oscillating toy
*A toy bird suspended on a spring from the ceiling. It is pulled 6cm downwards and, upon release, oscilaltes up and down with an angular frequency of 9.1 $rads^-1$. Calculate the magnitude of the velocity of the toy after $3.4s$*

1. $$
x=0.06\cos(9.1 \times 3.4) = 0.0533 
$$
2. $$
v = \pm 9.1\sqrt{ A^{2}-0.05333^{2} } = \pm 0.25 
$$
3. $$
|v| = 0.25ms^-1
$$

#### Personal Surface level derivation for velocity
$$
\begin{gather*}
x=A\cos(\omega t) \\ \\
x^{2}=A^{2}\cos ^{2}(\omega t) \\ \\
x^{2}=A^{2}(1 - \sin ^{2}(\omega t))\\
x^{2}=A^{2} - A^{2}\sin^{2}(\omega t) \\ 
x^{2}=A^{2}-x^{2} \\ \\
\therefore x=\sqrt{ A^{2}-x^{2} }
\end{gather*}
$$

If $\theta$ is small and in radians:
$$
\begin{gather*}
v=\omega r \qquad \sin\theta \approx\theta \\ \\
x=r\theta \\
\therefore x\approx r \\ \\
\text{But } x = \sqrt{ A^{2}-x^{2} } \\ \\
\therefore v=\omega\sqrt{ A^{2}-x^{2} } 
\end{gather*}
$$
![[Pasted image 20250916214513.png]]Due to the acceleration acting in opposing motion to the displacement:
$$
v=\pm\omega\sqrt{ A^{2}-x^{2} } 
$$
This also means v can be calculated by :
$$
v=\pm A\omega\sin(\omega t) \qquad or \quad v=\pm A\omega\cos(\omega t)
$$

#### Assisted Personal derivation for acceleration
https://youtu.be/KpEWRANx-Ao?si=-Ugl3dKwn4LUExVl
To calculate the velocity $v$ of the object we can differentiate the displacement $x$ using the chain rule. Assuming the oscillating object is released from the maximum displacement. It is possible to differentiate with respect as  A is constant.
$$
\begin{gather*}
x=A\cos(\omega t)\\
v=\frac{dx}{dt} = -A\omega\sin(\omega t)\\ \\ 
\end{gather*}

$$
To calculate the acceleration, you can differentiate the velocity $v$ you get. $\Omega$ becomes $w^{2}$ due to the chain rule.
$$
a=\frac{dv}{dt} = -Aw^{2}\cos(\omega t) 
$$
However this is the same thing as the defining equation for acceleration
$$
\begin{gather*}
a=-\omega^{2}A\cos(\omega t) \\ \\
 \text{Recall that } x = A\cos(\omega t) \\ \\
 \therefore a=-\omega^{2}x

\end{gather*}

$$

## Writing everything in terms of $f$ or $\frac{1}{T}$
$$
\omega=2\pi f
$$

$$
a=-4\pi^{2}f^{2}A\cos(2\pi ft)
$$
$$
v=-2\pi fA\sin(2\pi ft)
$$

## Equations if motion is from equilibrium
$$
\begin{gather*}
x=A\sin(\omega t) \\ \\
v=\frac{dx}{dt}
\end{gather*}

$$