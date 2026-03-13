The term attenuation is used to describe the decrease in intensity of electromagnetic radiation as it passes through matter. 


In the medical industry, bones tend to attenuate X-rays more than soft tissue. This means that bones tend to absorb more X-rays photons than soft tissue.

![[Pasted image 20260313060336.png]]

# Attenuation mechanisms
The intensity of a parallel (collimated) beam of X-rays will decrease as they pass through matter. There are four attenuation mechanisms  by which X-rays photons interact with atoms. 

Recall that intensity is defined as the radiant power per unit cross-sectional area and has unit $Wm ^{-2}$. 

## Simple Scatter
![[Pasted image 20260313060037.png]]

This applies for electrons within the range of 1-20keV. The X-ray photon interacts with an electron in the atom but has less energy than the energy required free the electron. The X-ray photon is deflected (scattered) without any change to its energy. 

X-ray machines used in hospitals use p.ds greater than 20keV so this mechanism is insignificant for hospital radiography. 

## Photoelectric effect
![[Pasted image 20260313060450.png]]

This mechanism is significant for X-rays photons with energy less than 100keV. The x-ray photon is absorbed by one of the electron in the atom. This frees the electron from the atom. 

Attenuation of X-rays via the photoelectric effect is common in hospitals as radiography machines use p.ds in range 30-100keV.

## Compton scattering
![[Pasted image 20260313060711.png]]

This mechanism is significant for X-ray photons with energy in the range 0.5 - 5.0 MeV. The incoming X-ray photon interacts with an electron within the atom. The electron is ejected from the atom. 

However recall from Module 4 that any excess energy above the work function of electron is left as $KE_{max}$. 

The X-ray photon does not disappear completely - instead it is scattered with reduced energy. In the interaction, both energy and momentum are conserved. 

## Pair production
![[Pasted image 20260313061619.png]]

This mechanism only occurs when X-rays photons have energy equal to or greater than 1.02 MeV. An X-ray photon interacts with the nucleus of the atom. It disappears as the electromagnetic energy of the photon is used to create an electron and its antiparticle, the positron. This can be explained using Einstein's mass-energy equation.

# Attenuation Coefficients
The transmitted intensity of X-rays depends on the energy of the photons and the thickness and type of substance. 

For a given substances and energy of photons, the intensity falls exponentially with thickness of substance. 

The transmitted intensity $I$ is given by the equation:
$$
I = I_{0}e^{-\mu x}
$$
Where $I_{0}$ is the initial intensity before any absorption, $x$ is the thickness of the substance and $\mu$ is the attenuation coefficient or absorption coefficient. 

From above, we can deduce bones have a higher attenuation coefficient than muscle. 

The SI unit for $\mu$ is $m^{-1}$. It is possible to also use $cm ^{-1}$ or $mm ^{-1}$.

## Example 
A collimated beam of X-rays from a 100kV supply is incident on bone. The initial intensity of the beam is $18Wm ^{-2}$. The attenuation coefficient of the bone is $0.60 cm ^{-1}$. Calculate the intensity of the bone after is has passed through $7.0 mm ^{-1}$ of bone. 

Using the formula:
$$
\begin{gather*}
I = I_{0}e^{-\mu x} \\ \\
\end{gather*}
$$
It is important the match the units to the same units as the attenuation coefficient as given in the question. In the question the units given were $cm ^{-1}$ and the thickness was $mm ^{-1}$. Therefore we must multiply the thickness by $\frac{10^{-3}}{10^{-2}}$ to get the thickness in $cm ^{-1}$. 
$$
\mu = 0.60 cm ^{-1} \qquad x = 7\left( \frac{10^{-3}}{10^{-2}} \right) = 0.70 cm ^{-1}
$$
Substituting into the formula:
$$
I = 18e^{-(0.60)(0.70)} = 11.85\dots \approx 12W
$$

# Contrast medium
Soft tissues have low absorption coefficients, so a contrast medium is used to improve the visibility of their internal structures in X-ray images. 

The two most common and iodine and barium compounds which are harmless to humans.

Barium and iodine have large atomic numbers, $Z$. From X-ray imaging, the predominant attenuation mechanism is the photoelectric effect.  

The attenuation coefficient is proportional to the cube of the atomic number:
$$
\mu \propto Z^{3}
$$

For soft tissues, the average atomic number for its material composition is $7$. This means iodine ($Z=53$) and $(Z=56)$ are about 430 times and 510 times more absorbent than soft tissues.

This is why iodine and barium are suitable as they have high atomic numbers and relatively harmless to humans. 

Iodine is used a contrast medium in liquids. Often to view blood, iodine is injected into blood vessels so that doctors can diagnose blockages in blood vessels and the structure of organs such as the heart.

Barium sulphate is often used to image digestive systems. It is given to a patient in the form of a white liquid mixture (a 'barium meal'). Which the patient swallows before an X-ray image is taken. 

# Therapeutic use
X-rays are also used for therapy rather than imaging. X-ray machines called lincas (linear accelerators) are used to create high energy X-ray photons that kill of cancerous cells. 

