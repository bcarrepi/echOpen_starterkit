# Acoustic imaging (basics) 

The pdf version of this document can be download ['here'](./acoustic_imaging_src/acoustic.pdf).

In this section, we will explain some basis of the acoustic theory to understand the propagation of acoustic waves and the echographic process.

Propagation of acoustic waves
=============================

In this section, we will define the different types of acoustic waves and some basic equations and properties of the propagation of acoustic waves.

Wave types
----------

An acoustic wave is a perturbation of the local state without displacement of the global state. Acoustic waves are periodic, their spatial periodicity is given by the wavelength *λ*. Consider a medium at rest such as on Fig. 1, where the particles are represented by the dots. Such a periodic structure represent a metal for example. When an acoustic wave propagate in this medium, the particles will have a local displacement.

<figure>
  <img src="./acoustic_imaging_src/image/at_rest.png" alt="" />
  <figcaption> *Figure 1: Medium at rest.* </figcaption>
</figure>

There is two types of acoustic waves, the longitudinal waves (Fig. 2) also named P waves and the transverse waves (Fig. 3) also named SH or SV waves. The longitudinal waves are compressional waves, the direction of the displacement of the particles is the same than the direction of propagation of the wave. The transverse waves are shear waves, the direction of displacement is then perpendicular to the direction of propagation of the wave. In a fluid, such as the water, only longitudinal waves can propagate. In the human body, the shear modulus is very small, it can be considered as a fluid, and so only longitudinal waves will be generated.

<figure>
  <img src="./acoustic_imaging_src/image/Pwave.png" alt="" />
  <figcaption> *Figure 2: Longitudinal wave.* </figcaption>
</figure>

In the rest of the document, we will only consider longitudinal waves.

<figure>
  <img src="./acoustic_imaging_src/image/Swave.png" alt="" />
  <figcaption> *Figure 3: Shear wave.* </figcaption>
</figure>

Mathematical formulation
------------------------

In acoustic, a fluid medium is describe by two mecanical parameters: the mass density *ρ* and the bulk modulus *κ*. The bulk modulus relate the change of volume of a medium to the isostatic pressure apply on it. The velocity of the acoustic wave *c* is:

begin{equation}
 c=\sqrt{\dfrac{\kappa}{\rho}},
 \label{eq:speed of sound}
\end{equation}
