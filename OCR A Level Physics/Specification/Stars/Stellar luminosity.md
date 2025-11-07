The hottest stars glow blue-white and the cooler stars a deeper shade of red. This affect applies to a metal that is heated. At first the metal glows dull red, then reddish-orange and as the temperature increases, it will eventually glow white-hot if it does not melt.

# Black body radiation
All objects above absolute zero, emit electromagnetic radiation of different wavelengths and different intensities. 

We can model objects a black body. A black body is an ideal object that absorbs all the electromagnetic radiation that shines onto it. A black body model also emits a specific distribution of electromagnetic radiation at specific wavelengths at a specific temperature. 

For example, the specific distribution curves of hot metal sheets modelled as black body at temperatures 7000K, 6000K, 5000K and 4000K can be seen below. It can be seen that that at 7000K, the metal is mostly emitting electromagnetic radiation with a wavelength of 450nm which lies with the violet light of visible light on the EM spectrum. 
![[Pasted image 20251107140459.png]]

# Wien's displacement law
This relates the absolute temperature $T$ of a black body to peak wavelength $\lambda_{max}$ at which the intensity is a maximum. The law can be applied to most objects from stars, to filament lamps and even to mammals. 

Wien's law states that $\lambda_{max}$ is inversly proportional to $T$:
$$
\lambda_{max} \propto \frac{1}{T}
$$
For any black-body emitter:
$$\lambda_{max}T = b$$ The value of this constant $b$ is is $2.90\times 10^{-3}mK$, where $mK$ is meter-Kelvins and is known as Wien's constant. 

Many objects can be modelled as approximate black bodies. This can help scientists determine the temperatures of objects simply by analysing the electromagnetic radiation they emit.

| Object           | $\lambda_{max}(m)$  | $T(K)$ |
| ---------------- | ------------------- | ------ |
| Sun              | $5\times 10^{-7}$   | 5000   |
| Healthy Human    | $9.4\times 10^{-6}$ | 310    |
| Wood fire flames | $9.4\times 10^{-6}$ | 1500   |
# Stefan's (Stefan-Boltzmann) Law
This law is also states the total power radiated per unit surface area of a black body is directly proportional to the fourth power of the absolute temperature of the black body. 

The total power radiated by a star is called luminosity. 

According to Stefan's law, the equation for luminosity $L$ in watts $(W)$ is given by equation:
$$
L = 4\pi r^{2}\sigma T^{4}
$$
where r is the radius of the star in meters (m), T is the surface absolute temperature of the star in kelvin (K), and $\sigma$ is the Stefan constant, $5.67\times 10^{-8}Wm^{-2}K^{-4}$ where $WmK$ is Watts per square meter per kelvin to the fourth power.

Stefan's law shows that the luminosity of a star is directly proportional to:
- The square of its radius $L\propto r^{2}$
- Its surface area $L\propto4\pi r^{2}$
- The fourth power of its surface temperature $L\propto T^{4}$

Using Wien's law and Stefan's law can be used to estimate the radius of a distant star. 

Once the radius is known, the mass and density of the star can be determined using Newton's law of gravitation.

## Worked example 1
The peak wavelength of radiation emitted by our Sun is about 500nm, its surface temperature is 5800K, and its luminosity is $3.85\times 10^{26}$W. The peak wavelength emitted by a nearby star with a luminosity 10 times that of our sun is 310nm. Show that the radius of this star is approximately $840000km$.

1. Calculate the temperature of second star with its peak wavelength and Wien's constant $b$
$$
\begin{gather*}
\lambda_{max}=\frac{b}{T} \\ 
T = \frac{b}{\lambda_{max}} \\ \\
T = \frac{2.9\times 10^{-3}}{310\times 10^{-9}} = 9354.387\dots K
\end{gather*}
$$
2. Use the luminosity of the Sun multiplied by 10 as L and then substitute the value for $T$ into Stefan's formula and calculate r:
$$
\begin{gather*}
4\pi r^{2}(5.67\times 10^{-8}) (9354.387\dots)^{4} = 10(3.85\times 10^{26}) \\ 
r = \sqrt{ \frac{10(3.85\times 10 ^{26})}{4\pi(5.67\times 10 ^{ -8})(9354.387\dots)^{4}} } = 8.40 \times 10 ^{8} \\ \\ 
\text{To get in kilometers} : \frac{8.40 \times 10^{8}}{10^{3}} = 840 000km \\ 
QED
\end{gather*}
$$


