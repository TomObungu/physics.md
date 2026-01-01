![[Pasted image 20260101093758.png]]

Main Elements of this question that I got:
- Assume that the rocket can be modelled as a particle and air resistance is negligible.
- Assume that acceleration produced by the rocket between A and B is constant. This allows the usage of constant acceleration formulae.
- From A to B:
	- By considering the vertical component of velocity only:
		-  $t=50$, $u=0$, $v=(3.1 \times 10^{3})\sin 75$
		- $s = \frac{1}{2}(u+v)t =  \frac{1}{2}((3.1 \times 10^{3})\sin 75)(50) = 74.9 \times 10^{3}m$
- From B to C, by modelling the rocket as a particle moving freely under gravity:
	- By considering the vertical component of velocity only:
		- $u=(3\times 10^{3})\sin 75$, $u=0$, $a=-9.81$
		- $v^{2}  = u^{2}+2as$, $s = \frac{v^{2}-u^{2}}{2a}=-\frac{(3.1 \times 10^{3})\sin 75)}{2(-9.81)} = 4.57 \times 10^{5}m$
- Thus the total height is $74.9 \times 10^{3}m + 4.57 \times 10^{5 = 5.31 \times 10^{5}m}$

Evaluation part that I missed out:
Question asks us to evaluate the assumption of $g=9.81$. The hint in the question is that it gives us the Earth's radius thus this is Newton's law of gravitation $g= \frac{GM}{r^{2}}$. Since we are not given the mass we have to think of proportionality:
$$
g \propto \frac{1}{r^{2}}
$$
This means:
$$
\begin{gather*}
g = \frac{k}{r^{2}}  \\ \\
g_{1}r_{1}^{2} = g_{2}r_{2}^{2} 
\end{gather*}
$$
From which we write it as:
$$
\frac{g_{1}}{g_{2}} = \frac{r_{2}^{2}}{r_{1}^{2}}
$$
Using the measurements that the question gave us:
$$
\frac{g_{1}}{g_{2}} = \frac{(6400+531)^{2}}{(6400)^{2}} = 1.17
$$
Thus if know that at the Earth's surface at $A$, $g=9.81$, we can calculate $g$ at $C$:
$$
\begin{gather*}
\frac{9.81}{g_{2}} = 1.17 \\ \\
g_{2} = \frac{9.81}{1.17} \approx 8.36
\end{gather*}
$$
This means that the value of $g$ at $C$ is $8.36$ which discredits the assumption of $g$ remaining constant at $9.81$. 
