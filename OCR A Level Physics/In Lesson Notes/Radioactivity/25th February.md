# Finding half life
- Easily contained and stored (not a gas)
- Suitable half life 

## Exponential decay derivation
$$
\begin{gather*}
\frac{dN}{dt} = -\lambda N \\ \\ 
\int_{N_{0}}^{N}  = \lambda \int_{N_{0}}^{N} dt \\ \\
[\ln N]_{N_{o}}^{N} = -\lambda t \\ \\
\ln \left( \frac{N}{N_{0}} \right) = -\lambda t \\ \\ \\
\implies \frac{N}{N_{0}} = e^{-\lambda t} \\ \\
N = N_{0}e^{-\lambda t}
\end{gather*}
$$

Half life occurs when $t=t_{\frac{1}{2}}$. When this is the case $N = \frac{N_{0}}{2}$
Therefore:
$$
\begin{gather*}
\frac{N_{0}}{2} = Ne^{-\lambda t_{\frac{1}{2}}}\\ \\ 
\frac{1}{2} = e^{-\lambda t_{\frac{1}{2}}} \\ \\
\therefore 2 = e^{\lambda t_{\frac{1}{2}}} \\ \\
\lambda t_{\frac{1}{2}} = \ln 2 \\ \\
t_{\frac{1}{2}} = \frac{\ln 2}{\lambda}
\end{gather*}
$$



