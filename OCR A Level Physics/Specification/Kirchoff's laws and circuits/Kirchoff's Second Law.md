	[[Potential Difference And e.m.f]]
Kirchoff's second Law takes the conservation of energy and applies it to electrical circuits. It states: In any circuit, the sum of e.m.f is equal to the sum of the p.d's around a closed loop.
![[Pasted image 20251001114158.png]]
This means, that p.d through a circuit loop will be equal to the total e.m.f from the supply. 
$$
\sum\varepsilon=\sum V \text{ around a closed loop})
$$
Essentially, the law states that total energy transferred to the charge carriers  in a circuit $\sum\varepsilon$, is always equal to the total energy transferred from the the charges. 

## Series Circuits
A series circuit has only one path for the current, a single loop from one terminal of the source e.m.f back to the terminal.

This means that in a series circuit, the current is the same in every position of the circuit. 

Thus from Kirchoff's second law, the rate of flow of charge is the same in every point in the circuit. 
![[Pasted image 20251001130049.png]]

Since in a series circuit, the entire circuit is a closed loop, then from Kirchoff's second law, the e.m.f is shared between the components. The sum of the p.d across the components is always equal to the e.m.f. 

This means that if the components have the same resistance, then e.m.f is shared equally between them

However if the components have different resistances, the component wil take the greater proportion of e.m.f

## Why
This is because Ohm's law stating that $V=IR$. Thus if the current $I$ is constant then and Kirchhoff's law states that the e.m.f is equal to the sum of the potential differences of each component:
$$
\sum \varepsilon = V_{1} + V_{2} \dots V_{3}
$$
This leads to this which can later be proved to show that the total  resistance within a series circuit is the sum of the resistances within a component.
$$
\begin{gather*}
\sum\varepsilon = IR_{1} + IR_{2} + \dots IR_{n} \\
\end{gather*}
$$

 In circuit with more than one source of e.m.f the same rule applies however we need to add the e.m.f from each source. Before sharing it between the components.

In this case the $\varepsilon_{1}=9V$ in conventional current and $\varepsilon_{2}=-6V$ in conventional current. Then the total e.m.f of the circuit will be $9-6 = 3V$. This is the value of e.m.f that will shared across the components in a circuit.

Three components within all with different voltages will sum up to to $3V$. This can be especially useful, when dealing with missing voltage values e.g. 
$$
\begin{gather*}
\sum\varepsilon = 0.5 + 1.5 + V_{3} \\
3V = 2V + V_{3} \implies V_{3} = 1V
\end{gather*}
$$

![[Pasted image 20251001130953.png]]

## Parallel circuits
A parallel circuit provides more than one possible route for the charges through branches. How much charge flow down each path depends on the resistance of the path. Kirchoff's first law tells us that current into each junction must be equal to the current out of the junction.


The greater the resistance of the branch, the lower the current that passes through it. If one of the branches has half the resistance of the other. It will have twice the current though it. 

So two-thirds of the total current will go through the branch will the lower resistance.
# p.d in parallel circuits
Each branch forms its own loop. Kirchhoff's second law tells us that around each loop, the e.m.f must be equal to the p.d, this must been the p.d across each branch is equal to the e.m.f from the power supply. 

Thus, if one branch contains several components then the sum of the p.d.s across these components must equal the e.m.f.

![[Pasted image 20251001143824.png]]
In this circuit, the e.m.f produced must equal to the sum of the voltages of every component. Thus in this case the voltage across each branch for each component will add up to 12V.
![[Pasted image 20251001143841.png]]
In this branch, the sum of the total voltage of this component must equal to 5V. Thus for each component in this branch, the voltage must also equal to 5.
![[Pasted image 20251001144258.png]]
In this example, resistor A has a p.d 2V across it along the main branch of the cell circuit. So this means that the cumulative voltage remaining that can through the next branheches will be 10V and thus each branch will have a voltage of 10V.

It is possible to see that voltage going into a branch will be same across the branches from the same junction.

## Why
This is because every branch within the parallel circuit is connected to the positive and negative terminal. This means from every emerging branch from the parallel circuit, the difference in joules per columb of charge  between the negative terminal and and positive terminal will still always be equal to the voltage the potential difference of the chemical cell. ![[Pasted image 20251001151127.png]]
This is because from each branch, the charge carriers will always enter a selection of the available branches with the same joules of energy per coulomb of charge as it is emerging from negative charge off the cell. Once the charge carriers travel through that branch and emerge back to main positive terminal branch. The will have exhuasted 1.5V and return along the positive terminal wire back towards the positive terminal to where they will gain energy again. 

In series, each component is connected to each other so the energy entering into each component will cascade as a result of the previous component using up energy.

However in parallel, this the not same, as each branch is connected directly to the battery. Thus the difference in energy is equal to the difference in energy between the negative terminal and positive terminal which the potential difference. 

This is why adding to identical cells in parallel, will yield a potential difference of the the same voltage for each cell. The difference in potential in each branch will be each to the maximum voltage. However if the cells were not identical, then there would be an imbalance of current between the lower p.d cell and the higher one and the higher p.d cell would send a large current to the lower p.d to try and equalize their pontential. This large current will cause the cells to overheat. 

This is because a higher voltage will cause a higher current due to the charge carriers having more energy. This is Ohm's law:
![[Pasted image 20251001153446.png]]
