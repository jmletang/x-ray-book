# Physics

## Ionizing radiations

Wilhem Röntgen a German physicist made the discovery in 1895 of X-rays during
studies of vacuum tubes (Crookes). The first x-rays on film (the
hand of his wife) date from this period.

```{figure} ../figures/RX/Images/Roentgen.jpg
---
width: 70%
figclass : margin
name: Roentgen
---
Wilhem Röntgen
```
```{figure} ../figures/RX/Images/RoentgenHand.png
---
width: 70%
figclass : margin
name: RoentgenHand
---
Radiography of Ms Röntgen's hand
```
```{figure} ../figures/RX/Images/CrookesTubeXrayExperiment.jpg
---
width: 70%
name: CrookesTubeXrayExperiment
---
Crookes Tube Xray Experiment
```

Less than 20 years after their discovery, X-ray imaging was used medicinally in battle fields.
```{figure} ../figures/RX/RadiographieSoldat25ansBlesseBalleTete19141130.png
---
width: 50%
name: RadiographieSoldat25ansBlesseBalleTete19141130
---
Radiography during WWI
```

Some societal applications of X-rays appeared in the first half of the 20th century
century, but radiobiological studies quickly put an end to these applications.

```{figure} ../figures/RX/Pedoscope001009a.jpg
---
width: 100%
figclass : margin
name: Pedoscope001009a
---
Ad for the Pedoscope
```
```{figure} ../figures/RX/Pedoscope002010a.jpg
---
width: 70%
name: Pedoscope002010a
---
Demo of the Pedoscope
```
```{figure} ../figures/RX/Podoscope_par_The_Pedoscope_Compagny_01.jpg
---
width: 60%
figclass : margin
name: Podoscope_par_The_Pedoscope_Compagny_01
---
The Pedoscope
```

X-rays can be modeled as massless particles, the photons to which
we associate an energy (expressed in keV by reference to the mode of production which is
based on electron acceleration and kinetic energy of an accelerated resting electron
by a potential difference of 1V acquires a kinetic energy of 1eV), or else
like electromagnetic radiation, characterized by its wavelength: it is the
wave-particle duality. The range of electromagnetic radiation is very wide.
```{figure} ../figures/RX/Physics/em-spectrum-nasa.png
---
width: 70%
name: em-spectrum-nasa
---
Electromagnetic spectrum
```
```{figure} ../figures/RX/Physics/matter_proton.png
---
width: 100%
figclass : margin
name: matter_proton
---
Constituents of an atom
```

The wavelength of x-rays is less than nm: ***atoms and their constituents are
therefore resolved***.
```{margin} Constants
- Energy conversion $1\;\mathsf{eV} = 1.60 \times 10^{-19}\;\mathsf{J}$
- Planck constant $h = 6.63 \times 10^{-34}\;\mathsf{J}\cdot$s
- Speed of light in vacuum $c = 3 \times 10^8\;\mathsf{m}\cdot\mathsf{s}^{-1}$
```
```{admonition} Photon
:class: note
The photon energy $E$ is related to the photon frequency $\nu$:
\begin{equation}
E = h\nu
\end{equation}

When all photons of an x-ray beam have the same energy, the x-ray beam is called  "monochromatic", and named "polychromatic" otherwise. The momentum $\mathbf{p}$ and wave vector $\mathbf{k}$ are given by:

$$
\mathbf{p} = \frac{h}{2\pi} \mathbf{k} 
\;\;\;\;\;\;\;\;\;\;
\left|\mathbf{p}\right| = \frac{h\nu}{c}
$$
```

 Mass particles exist at rest and their speed depends on their kinetic energy $KE$.
```{margin} Masses
- Electron mass at rest $m_{0,e}=511\;\mathsf{keV}/c^2$
- Nucleon mass at rest $m_{0,p} \approx m_{0,n} = 940\;\mathsf{MeV}/c^2$
```
```{admonition} Mass particle
:class: note
The energy of a mass particle is the sum of its rest energy energy $E_0 = m_0 c^2$ and its kinetic energy $KE$:

$$
E = E_0 + KE = \gamma m_0 c^2
$$

where the Lorentz factor $\gamma$ depends on the particle speed vector $\mathbf{v}$ (it becomes $+\infty$ if the particle speed is $c$):

$$
\gamma = \frac{1}{\sqrt{1-(\left|\mathbf{v}\right|/{c})^2}}
$$

The particle momentum $\mathbf{p}$ is simply $\mathbf{p} = \gamma m_0 \mathbf{v}$
```


## Attenuation law & Interactions

Photon-matter interactions are of two types: total absorption or diffusion. In
in the first case the energy of the photon is locally transferred to the atom. In the second
case, a scattered photon is emitted after interaction with its own energy and direction.
X-ray imaging is concerned with attenuation, ie the proportion of photons that do not have
not interacts: the radiation directly transmitted. This is the Beer-Lambert law.

The law of attenuation can be deduced from a thin beam model on a thick plate-
elementary sor dl. The fall in the number of directly transmitted photons is propor-
tional to the number of incident photons N and the thickness of this plate.

Integrating this equation gives the exponential law of attenuation which presents a
simple shape in the case of a homogeneous material and for a single radiation
energy. In the case of materials with several homogeneous phases, the attenuation results from
simple product of attenuations on the different constituent materials. In fact, for
a locally non-divergent geometry, the order and positioning of the materials
long radiation has no influence on the number of photons directly trans-
put (unlike the proportion of scattered radiation arriving on the detector). The
linear attenuation coefficient μ varies linearly with density. The effective section
σ, the component of μ, represents a probability of interaction expressed as a
area.

The Bragg additivity rule makes it possible to relate the mass attenuation coefficients μ / ρ
to calculate that of a mixture.

Rayleigh scattering, coherent and elastic, is an interaction with the atom as a whole,
without ionization or energy transfer. The scattered photon has a different cross section
tial (angular), denoted DCS, maximum in the incident direction, ie the angle of diffusion
θ ≈ 0. The probability of backscattering, ie θ> π / 2, is not zero but remains low, even
at low energy.

The interest of this scattering is its sensitivity to atomic arrangement. For materials
different but having the same attenuation, Rayleigh broadcast DCS can
be very different. It is the idea of ​​so-called dark field imagery that allows
puts access to these DCS by Talbot-Lau interferometry. The information thus extracted
are complementary to those of simple attenuation.

Regular atomic arrangements generate diffraction patterns in di-
rections related to Bragg's law according to the directions of the planes of atoms. This gives rise to
small (SAXS) or wide angle (WAXS) diffraction imaging techniques.
Teams recently proposed tomographic imaging combining attenuation
and diffraction on the same detector. Diffraction spots are associated in pairs
at π angular distance during the rotation of the source, which makes it possible to find
the local orientation of the atomic structure.

Compton scattering, inelastic and incoherent, is the dominant interaction for most
share of materials in a wide range of energy. The photon transfers a part
of its energy to the atom which expels a peripheral electron (therefore weakly bound). The
angular differential cross section (DCS) is much more isotropic than for the diff-
Rayleigh fusion: at low energy, the most likely direction for the scattered photon
Compton is even backwards, ie θ ≈ π.

The laws of conservation of energy and momentum allow mod-
elect the energy of the scattered Compton E 2 photon as a function of the scattering angle θ. This
law is decreasing monotonically with θ, and the energy is maximum and close to the energy
incident for small angles. This relationship assumes that the expelled Compton electron is at rest, in practice there is Doppler broadening. The atom is therefore ion-
ized as a result of this interaction, this is what gave the terminology of "
ionizing ”.

Compton backscattering has been the subject of scanning imaging protocol development.
whole body, especially for border control at airports. Source
collimated in a brush sweeps and turns around the person, the detector is the same
side as the source.

The photoelectric effect is a total absorption interaction, the photon transfers any
its energy to the atom. A strongly bound electron is expelled from the atom. This
electron called photoelectron leaves with a kinetic energy equal to that of the photon
incident minus its initial binding energy. At this point the atom is ionized on an gold-
internal bitale, a cascade of re-arrangement of the electronic procession takes place and
the associated energy releases result from a competition between two phenomena
exclusive: the expulsion of another but peripheral electron called the Auger electron, or
well the emission of a so-called fluorescence photon. The energies of fluorescent radiation
rescence are characteristic of the atom (eg use to measure lead in
paintings).

The fluorescence efficiency is very close to 100% for atom- numbered materials.
high ic. On the other hand, for materials with low atomic number, there will not be
fluorescence radiation but only Auger electrons.

Application to 3D fluorescence imaging of the different constituents of a cell.

In summary, X-ray imaging - which looks at directly transmitted radiation -
mis (without interaction) - can be parasitized by the presence of many types of radiation
secondary (Rayleigh and Compton scattering, Fluorescence). Electrons (here in red the
photons being green) are also products of interactions.

Traces of electrons (in red) of 500 keV impacting from the right a plate of 100 mi-
tungsten crons (submerged in a vacuum). We see that the electrons have trajectories.
roofs very disturbed and travel less than 100 microns. On the other hand, on the hundred
electron launched, a few generated photons (green).

Electron-matter interactions are shared between collisions (ionizations) and the
braking (radiative). The radiative efficiency is very low (less than%) in the range
energy used in imaging. However, it is mainly braking radiation
(Bremsstrahlung) and less those of fluorescence (from ionizations by electrons)
which are used in x-ray generators to produce the radiation. The
Heavy metal anodes increase radiative efficiency.

The path of electrons, normalized in density, depends on the energy of the electrons but very
bit of the material. The electrons expelled during photon-matter interactions are absorbed locally (this is the notion of dose): the path of 100 keV electrons in water is
less than 200 microns.

The linear attenuation coefficient μ can be interpreted as the sum of the dif-
strong interactions. The mean free path or MFP is the mean distance per-
ran by a photon at the next interaction. The half-attenuation layer or HVL
represents the thickness necessary to attenuate by a factor of 2 the number of di- photons
duly transmitted. The Beer-Lambert law of attenuation generalizes to spectra
large and heterogeneous materials in the form of a sum of exponentials. She
can be expressed in number of photons, in energy, or in dose.

Mass attenuation coefficient curves for carbon and tungsten. The dis-
continuities for the photoelectric effect (PhE) are visible for tungsten because the en-
link ergies are greater (70 keV for the K layer of tungsten while
it is only 0.3 keV for carbon). Note the relative constant of the coefficient
of mass Compton diffusion attenuation (CS) between the two materials, while
that of the photoelectric effect is much more dominant for tungsten. The creation of
electron-positron pair (PC) is a total absorption interaction that occurs at very
high energy.

The iso-probability curve between the interactions by photoelectric effect and by diffusion
Compton. Materials with a low atomic number will essentially interact with
X-rays by Compton scattering, while heavy metals mainly by
photoelectric effect.

The divergence of the beam is directly conditioned by the solid angle between a surface
and the source of radiation. This relation can be approximated by an inverse relation-
is proportional to the square of the distance from the radiation source, considering
that the surface is small and perpendicular to the direction of propagation.

The global X-ray propagation formula is therefore the product between the term of
divergence and attenuation.

## Monte Carlo simulation

## Wave
