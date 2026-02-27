# Carbon Dating
Atmospheric carbon is mainly the stable isotope, carbon-12, but also a tiny amount of the radioactive isotope carbon-14. Carbon-14 has a half life of about 5700 years and is produces continuously in the atmosphere by cosmic rays.

The ratio of carbon-14 to carbon-12 nuclei is the same in all living things. Once an organism dies, it stops taking in carbon, whilst the total number of carbon-14 it contains continues to decay, so this ratio decays over time. 

The activity from carbon-14 in a sample of organic material is proportional to the number of undecayed carbon-14 nuclei. 

The time since the organism died can therefore be determined by comparing the activities, or the ratios of carbon-14 to carbon-12 nuclei of the dead material and similar living material. 

Carbon dating of organic materials as old as 50000 years is possible with samples as small as nanograms using mass spectrometry. 

# Atmospheric carbon-14
High-speed protons in cosmic rays from space colliding with atoms in the upper atmosphere produce neutrons. These neutrons in turn collide with nitrogen-14 nuclei in the atmosphere to form carbon-14 nuclei. 

The carbon-14 nuclei in the atmosphere eventually emit beta-minus particles (electrons) and become nitrogen-14 again, so the amount of nitrogen-14 in the atmosphere is replenished. 
$$
^{1}_{0}n + ^{14}_{7}N \to \underbrace{ ^{14}_{6}C + ^{1}_{1}p }_{ \text{Half life } \approx \ 5700y} \to ^{14}_{7}N + ^{0}_{-1}e + \bar{v_{e}}
$$

# Worked Example 
A wooden axe found in an Egyptian tomb is found to have an activity of $0.38Bq$. The activity of an identical mass of wood cut from a living tree is $0.65Bq$. Calculate the age of the wood used to make the axe. 

1. Calculate the decay constant $\lambda$ of the isotope of carbon-12.  Ensure the half life is in seconds
$$
\lambda = \frac{\ln(2)}{t_{\frac{1}{2}}} = \frac{\ln(2)}{5700(3.16 \times 10^{7})} = 3.484 \times 10^{-12}
$$
2. Use $A = A_{0}e^{-\lambda t}$ for activity to determine the age $t$ of the wood
$$
0.38 = 0.65e^{-3.484 \times 10^{-12}} 
$$
3. Taking the natural logarithm of both sides:
4. $$
\begin{gather*}
\ln\left( \frac{0.38}{0.65} \right) = -3.484 \times 10^{-12}t \\ \\ 
t = \frac{\ln\left( \frac{0.38}{0.65} \right)}{-3.484 \times 10^{-12}} = 1.395 \times 10^{11}s = 4400 \text{ years}
\end{gather*}
$$
# Limitations to carbon-dating 
A limitation to carbon dating is the assumption that the ratio of carbon-14 atoms to carbon-12 atoms has remained constant over time. Increased emission of carbon dioxide due to burning fossil fuels may have reduced this ratio. 

The ratio may still be affected by solar flares from the Sun and by the testing of nuclei bombs.  

The tiny amounts of carbon-14 present in organisms also means that the activities are extremely small, about 15 counts per minute for $1g$ of carbon - comparable to the background rate. 

# Dating rocks
As the half-life of carbon-14 is not long enough to date rocks formed during the creation of the Solar System, instead, geologists use the decay of rubidium-87 to date ancient rocks. Nuclei of rubidium-87 emit beta-minus particles and transform into stable nuclei of strontium-87. The half-life of the isotope rubidium-87 is about 49 billion years. 