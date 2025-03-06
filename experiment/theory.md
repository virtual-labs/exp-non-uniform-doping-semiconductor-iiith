### The PN Junction
It is important to realize that the entire semiconductor is a single-crystal material in which one region is doped with acceptor impurity atoms to form the p region and the adjacent region is doped with donor atoms to form the n region. The interface separating the n and p regions is referred to as the metallurgical junction.
Initially, at the metallurgical junction, there is a very large density gradient in both the electron and hole concentrations. Majority carrier electrons in the n region will begin diffusing into the p region and majority carrier holes in the p region will begin diffusing into the n region. If we assume there are no external connections to the semiconductor, then this diffusion process cannot continue indefinitely. As electrons diffuse from the n to p region, they leave behind positively charged donor ions and as holes diffuse from the p to n region they leave negatively charged ions behind.
<div align="center">
<image src="images/fig_7.1.png" height="300px" width ="auto">
<span style="float: right;">(Fig 5.1)</span>
</div>

The net positively and negatively charged regions are shown in Figure 5.1. These two regions are referred to as the space charge region. Essentially all electrons and holes are swept out of the space charge region by the electric field. Since the space charge region is depleted of any mobile charge, this region is also referred to as the depletion region: these two terms will be used interchangeably. Density gradients still exist in the majority carrier concentrations at each edge of the space charge region. We can think of a density gradient as producing a "diffusion force" that acts on the majority carriers.

### No applied Bias
#### Built in potential Barrier
If we assume that no voltage is applied across the pn junction, then the junction is in thermal equilibrium-the Fermi energy level is constant throughout the entire system. Figure 2 shows the energy-band diagram for the pn junction in thermal equilibrium. The conduction and valence band energies must bend as we go through the space charge region.
<div align="center">
<image src="images/fig_7.2.png" height="300px" width ="auto">
<span style="float: right;">(Fig 5.2)</span>
</div>
The junction acts like a wall, not letting electrons from the n region pass through the barrier to the p region. It ensures that majority and minority carriers in the n and p region are in equilibrium. At equilibrium, the electron(n<sub>p0</sub>) and hole(p<sub>p0</sub>) concentrations in the p region are

$$
p_{p0} = N_{A}
$$

$$
n_{p0} = \frac{n_{i}^{2}}{N_{A}}
$$

Similarly, the electron(n<sub>n0</sub>) and hole(p<sub>n0</sub>) concentrations in the n region are

$$
n_{n0} = N_{D}
$$

$$
p_{n0} = \frac{n_{i}^{2}}{N_{D}}
$$

To derive the expression for the junction potential, we must realize that the potential prevents further motion of carriers once equilibrium is reached. Thus, the electron (or hole) concentrations on either side of the junction can be written in terms of the contact potential (V<sub>0</sub>) as
$$
\frac{n_{p0}}{n_{n0}} = \frac{p_{n0}}{p_{p0}} = e^{\frac{eV_{0}}{k_{B}T}}
$$

$$
V_{0} = \frac{k_{B}T}{e} ln(\frac{N_{A}N_{D}}{n_{i}^{2}})
$$

$$
V_{0} = V_{i} ln(\frac{N_{A}N_{D}}{n_{i}^{2}})
$$

Where V <sub>i</sub> is the contact potential.

### Electric Field
An electric field is created in the depletion region by the separation of positive and negative space charge densities. Figure 3 shows the volume charge density distribution in the pn junction assuming uniform doping and assuming an abrupt junction approximation. 
<div align="center">
<image src="images/fig_7.3.png" height="300px" width ="auto">
<span style="float: right;">(Fig 5.3)</span>
</div>
The depletion width typically extends on both the n and p side with relative widths inversely proportional to the dopant concentration,
 
$$
\frac{w_{p}}{w_{n}} = \frac{N_{D}}{N_{A}}
$$

Where width of the depletion region in the p side is w<sub>p</sub> and that of the n side is w<sub>n</sub>.
We can find the relationship between the distribution of electric fields within the depletion region and the net charge. In a one dimension interface,

$$
\frac{DE}{dx} = \frac{\rho _{net}}{\epsilon}
$$

$$
\rho _{net} = -eN_{A} \quad for \quad -w_{p} < x < 0
$$

$$
\rho _{net} = eN_{D} \quad for \quad 0 < x < w_{n}
$$

Here "e" is elemental charge which is 1.602*10<sup>-19</sup> and &rho; is the charge density

$$
E(x) = -\frac{eN_{A}}{\epsilon}(x+w_{p})  \quad for \quad -w_{p} < x < 0
$$

$$
E(x) = -\frac{eN_{A}}{\epsilon}(x+w_{p})  \quad for \quad -w_{p} < x < 0
$$

Before the junction is formed, the Fermi levels in the extrinsic semiconductors can be calculated individually by considering the shift from the intrinsic Fermi level. This is given by
$$
E_{Fn} - E_{Fi} = k_{B}T ln(\frac{N_{D}}{n_{i}}) = 0.36eV
$$
$$
E_{Fp} - E_{Fi} = -k_{B}T ln(\frac{N_{A}}{n_{i}}) = -0.42eV
$$
For the n type semiconductor the Fermi level is located above the intrinsic level while for the p type semiconductor it is located below the intrinsic level. When the junction is formed, as shown in the energy band diagram, the Fermi levels line up. For this to happen, either the p Fermi level can be considered to have shifted up or the n level can be considered to have shifted down or both. The magnitude of the shift is given by the difference in the work functions, which is proportional to the Fermi level positions. So the shift is equal to the difference in Fermi level positions and is given by
$$
Shift = E_{Fn} - E_{Fp} = 0.36eV -(-0.42) = 0.78eV
$$
Thus, the contact potential developed in a pn junction due to the motion of the charge carriers is nothing but the shift in Fermi levels to achieve equilibrium. This is related to another definition of the Fermi level which is the work done to remove or add an electron to a material.

### Depletion Width
The electric field is related to electric potential by
$$
E(x) = -\frac{dV}{dx}
$$

$$
E(x) = -\frac{eN_{A}}{\epsilon}(x+w_{p})^{2} \quad for \quad -w_{p} < x < 0
$$

$$
E(x) = V_{0}-\frac{eN_{D}}{\epsilon}(x-w_{n})^{2} \quad for \quad 0 < x < w_{n}
$$
Since the electric field is continuous, both these equations should be equal at x = 0
$$
V_{0}-\frac{eN_{D}}{\epsilon}(w_{n})^{2} = -\frac{eN_{A}}{\epsilon}(w_{p})^{2}
$$

$$
V_{0} = \frac{eN_{D}}{\epsilon}((w_{n})^{2} (w_{p})^{2})
$$

$$
w_{p}+w_{n} = w_{0}
$$

$$
w_{p}N_{A} = w_{n}N_{D}
$$

$$
V_{0} = \frac{2}{2\epsilon} w_{0}^{2} \frac{N_{A}N_{D}}{N_{A}+N_{D}}
$$

$$
w_{0} = \frac{2\epsilon v_{0}}{e} \frac{N_{A}+N_{D}} {N_{A}N_{D}}
$$

Here, w<sub>0</sub> is the depletion width and V<sub>0</sub> refers to the built in potential.

### Non-uniformly Doped Junctions
#### Linearly Graded Junctions
If we start with a uniformly doped n-type semiconductor, for example, and diffuse acceptor atoms through the surface, the impurity concentrations will tend to be like those shown in Figure Fig 5.4. The point x = x' on the figure corresponds to the metallurgical junction. The depletion region extends into the p and n regions from the metallurgical junction as we have discussed previously. The net p-type doping concentration near the metallurgical junction may be approximated as a linear function of distance from the metallurgical junction. Similarly the n type doping concentration is a linear function extending from the metallurgical junction
<div align="center">
<image src="images/fig_7.4.png" height="300px" width ="auto">
<span style="float: right;">(Fig 5.4)</span>
</div>
For convenience the junction is placed at x=0. The space charge density can be written as 
$$
\rho(x) = eax
$$

Where a is the gradient of the net impurity concentration. The electric field and concentration can be found by Poisson's equation. We can write

$$
\frac{dE}{dx} = \frac{\rho(x)}{\epsilon} = \frac{eax}{\epsilon}
$$

$$
E = \int \frac{eax}{\epsilon}dx = \frac{ea}{2\epsilon}(x^{2})
$$
The electric field in the linearly graded junction is a quadratic function of distance rather than the linear function found in the uniformly doped junction.The potential is again found by integrating the electric field as 

$$
\phi(x) = - \int Edx
$$
Say &phi;(x) = 0  at x = -x<sub>0</sub>

$$
\phi(x) = \frac{ea}{2\epsilon}(\frac{x^{2}}{3} - x_{0}^{2}x) + \frac{ea}{3\epsilon}x_{0}^{3}
$$

The magnitude of the potential at x = +.ro will equal the built-in potential barrier for this function. We then have that 

$$
\phi(x) = \frac{2ea}{3\epsilon}x_{0}^{3} = V_{0}
$$

#### Hyperabrupt Junctions
The uniformly doped junction and linearly graded junction are not the only possible doping profiles. Figure 5.5 shows a generalized one-sided p+n junction where the generalized n-type doping concentration for x > 0 is given by

$$
N = Bx^{m}
$$

When the value of m is negative, we have what is referred to as a hyperabrupt junction. In this case, the n-type doping is larger near the metallurgical junction than in the bulk semiconductor. The above equation is used to approximate the n-type doping over a small region near x = xu and does not hold at x = 0 when m is negative.

## References
1. S.M. Sze, "Physics of Semiconductor Devices"
2. Robert F. Pierret, "Semiconductor Device Fundamentals"
3. Ben G. Streetman, "Solid State Electronic Devices"

## Additional Resources
- [Interactive Semiconductor Simulations](https://www.semiconductors.org)
- [Online Calculator Tools](https://www.electronics-tutorials.com)
- [Video Lectures and Demonstrations](https://www.nptel.ac.in)