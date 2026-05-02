Physical quantities that decrease by the same factor in equal time interval have a constant-ratio pattern that is called exponential decay. The p.d across a capacitor decreases exponentially over time.

Exponential functions are governed by Euler's constant $e$, which has a value of $2.718\dots$

When a capacitor has capacitance $C$, the resistance in the resistor is $R$ and the p.d across the capacitor and the resistor is $V_{0}$
- The p.d V across the capacitor or the resistor $=V_{0}$
- The current in the resistor is $I=\frac{V_{0}}{R}$
- The charge in the capacitor $Q=V_{0}C$
![[Pasted image 20251127211530.png]]

When the capacitor discharges through the resistor, the charge stored by the capacitor decreases with time and hence the p.d across it also decreases accordingly due to $V = \frac{Q}{C}$. Eventually, the p.d and the charge stored by the capacitor, and the current $I$ in the resistor are all zero.

Below are $V-t$, $I-t$ and $Q-t$ graphs. These graphs all show exponential decay over time after the switch is opened
![[Pasted image 20251127212105.png]]

The equations for these quantities are:
$$
V = V_{0}e^{\frac{-t}{CR}} \qquad I = I_{0}e^{\frac{-t}{CR}} \qquad Q=Q_{0}e^{\frac{-t}{CR}}
$$
Where $V_{0},I_{0}$ and $Q_{0}$ are the initial values for voltage, charge and current of the capacitor before being discharged and $RC$ is the time constant with value resistance multiplied by capacitance.
# Constant-ratio property of exponential decay
 From the graph of p.d against t shows that $\frac{V_{1}}{V_{0}}\approx \frac{V_{2}}{V_{3}} \approx \frac{V_{3}}{V_{4}}$ which obeys the law voltage being the same for capacitors in series
 ![[Pasted image 20251127231748.png]]

## Time constant
The time constant of a capacitor resistor circuit is equal to to the capacitance and resistance. 

In general the time constant $\tau$ is the time taken for the p.d or current to decrease to a value of the initial value multiplied by $e^{-1}$. When the value of $x=x_{0}e^{-\frac{t}{RC}}$, $x$ be it charge, current or voltage, will equal to $xe^{-1}$ when the charge in the capacitor is fully discharged.

That is the time constant $RC$ is the time taken for the capacitor to be fully discharged
# Modelling exponential decay
As charge can be show that $I =\frac{V}{R}$ and $Q=VC$. Thus current may be written as:
$$
I = \frac{V}{R} = \frac{VC}{CR} = \frac{Q}{CR}
$$
As well as that we know that current is the rate of change of charge, thus $I=\frac{\Delta Q}{\Delta t}$. As the charge in a capacitor's decreases exponentially, the charge is $I=-\frac{\Delta Q}{\Delta t}$ thus:
$$
\frac{\Delta Q}{\Delta t} = -\frac{Q}{CR}
$$
The equation for exponential decay of $Q=Q_{0}e^{\frac{-t}{RC}}$ of charge is a solution to this equation. 

Further expanding on this. Since the potential difference across a discharging capacitor is the same as the the resistor it is discharging into. 

We can form another useful identity using, $I$, $R$ 
$$
\begin{gather*}
V = IR \ \ V = \frac{Q}{C} \\ \\
IR = \frac{Q}{C} \\
-\frac{\Delta Q}{\Delta t} R = \frac{Q}{C} \\ \\
\frac{\Delta Q}{\Delta t}R = \frac{Q}{C}
\end{gather*}
$$

# Iterative modelling
The equation $\frac{\Delta Q}{\Delta t} = -\frac{Q}{CR}$ can be used for model the decay of $Q$ on the capacitor.

1. Start with a known value for the initial charge $Q_{0}$ and a known value for the time constant $CR$. The readings can be taking from a circuit consisting of a switch, ammeter with a capacitor, resistor and voltmeter in parallel:
	1. ![[Pasted image 20260502103420.png]]
2. Choose a time interval $\Delta t$ which is small compared to the time constant. This is to ensure the capacitor does not discharge faster than you can take readings. This is also to keep the value of $\Delta Q$, precise. 
3. 
	1. Using the readings from the ammeter, the known value for capacitance and the known value for resistance, calculate the instantaneous charge $Q$, using $Q = CIR$. 
	2. Calculate the charge leaving the capacitor $\Delta Q$, in time interval $\Delta t$, using. 
$$
\Delta Q = \frac{\Delta t}{CR} \times Q
$$
4. Calculate the charge $Q$ left on the capacitor at the end of the period $\Delta t$ by subtracting $\Delta Q$ from the previous value of $Q$. On the first interval, the previous reading of $Q$ is $Q_{0}$. 
5. Repeat the process for multiple time intervals. 
An example table of the processes:
![[Pasted image 20251127234241.png]]
Using example values of time constant $RC = 2.0s$ and time interval $\Delta t = 0.1s$. We can show the constant time ratio of exponential decay in $\Delta Q$
$$
\Delta Q = \frac{0.1}{2}Q = 0.05Q
$$
After every $\Delta t = 0.1s$, the charge is $95\%$ of the previous value of $Q$.  This constant time-ratio property is characteristic of exponential decay. 

Once finished taking value for the iterative model. The value of Q from the table can be compared with the known mathematical model of $Q$:
$$
Q = Q_{0}e^{\frac{-t}{RC}}
$$
to test the accuracy of the model. Furthermore exponential decay can be shown by observing that value of $\Delta Q$ on each time interval is approximately constant. 
## Dealing with logarithms and experimental results
Taking the equation $V=V_{0}e^{-\frac{t}{CR}}$:
$$
\begin{gather*}
\ln V = \ln (V_{0}e^{-\frac{t}{CR}}) \\ \\
= \ln V_{0} + \ln e^{-\frac{t}{CR}} \\ \\
= \ln V_{0}  - \frac{t}{CR}
\end{gather*}
$$

Compare this with the equation of a straight line $y=mc+c$ a graph of $\ln V$ against $t$ gives gradient $-\frac{1}{CR}$ and y-intercept $V_{0}$

## Example 
An example table of information can be used to prove this:
![[Pasted image 20260502105707.png|166]]
Filling up the table by taking $\ln V$, to  give values to be used plot $\ln V$ against $t$:
![[Pasted image 20260502105851.png|198]]
Using the information we can draw  a digital line of best fit for $\ln V$ against $t$. From our mathematical model earlier, the $y$ intercept will be $\ln V_{0}$ and the gradient will be $-\frac{1}{RC}$
![[Pasted image 20260502105657.png]]
Using the calculator we can get the line equation to be:
$$
y = -0.03030308x + 2.197621
$$
Thus, we can get a time constant value of about $33s$
$$
\begin{gather*}
m =  -0.03030308 = - \frac{1}{RC} = \tau \\ \\
\tau = -(0.03030308)^{-1} = 32.99994\dots \approx 33s
\end{gather*}
$$
From that we can calculate the value of the capacitor if the resistance of the resistor is known. In this case it is $33k\Omega$. In this case it about $1000\mu F$
$$
\begin{gather}
RC = 33.99994\dots \implies 33.99994 = (33 \times 10^{3})C \\  \\
C = \frac{33.99994}{33 \times 10^{3}} = 9.9999836\dots \times 10 ^{-4}  \\ \\ \\
C \approx 1000 \mu F
\end{gather}
$$

 