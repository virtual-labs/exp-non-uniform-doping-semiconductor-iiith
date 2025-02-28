### The PN Junction
It is important to realize that the entire semiconductor is a single-crystal material in which one region is doped with acceptor impurity atoms to form the p region and the adjacent region is doped with donor atoms to form the n region. The interface separating the n and p regions is referred to as the metallurgical junction.
Initially, at the metallurgical junction, there is a very large density gradient in both the electron and hole concentrations. Majority carrier electrons in the n region will begin diffusing into the p region and majority carrier holes in the p region will begin diffusing into the n region. If we assume there are no external connections to the semiconductor, then this diffusion process cannot continue indefinitely. As electrons diffuse from the n region, positively charged donor atoms are left behind.
<div align="center">
<image src="images/fig_7.1.png">
<span style="float: right;">(Fig 5.1)</span>
</div>

The net positively and negatively charged regions are shown in Figure 5.1. These two regions are referred to as the space charge region. Essentially all electrons and holes are swept out of the space charge region by the electric field. Since the space charge region is depleted of any mobile charge, this region is also referred to as the depletion region: these two terms will be used interchangeably. Density gradi- ents still exist in the majority carrier concentrations at each edge of the space charge region. We can think of a density gradient as producing a "diffusion force" that acts on the majority carriers.

### No applied Bias
#### Built in potential Barrier
If we assume that no voltage is applied across the pn junction, then the junction is in thermal equilibrium-the Fermi energy level is constant throughout the entire system. Figure 2 shows the energy-band diagram for the pn junction in thermal equilibrium. The conduction and valence band energies must bend as we go through the space charge region.
<div align="center">
<image src="images/fig_7.2.png" >
<span style="float: right;">(Fig 5.2)</span>
</div>
The junction acts like a wall, not letting electrons from the n region pass through the barrier to the p region. It ensures that majority and minority carriers in the n and p region are in equilibrium. At equilibrium, the electron(n<sub>p0</sub>) and hole(p<sub>p0</sub>) concentrations in the p region are
<div align="center">
<image src="images/1.png" height="50px" width="auto">
<span style="float: right;">(5.1)</span>
</div>
<div align="center">
<image src="images/2.png" height="50px" width="auto">
<span style="float: right;">(5.2)</span>
</div>
Similarly, the electron(nn0) and hole(pn0) concentrations in the n region are
<div align="center">
<image src="images/3.png" height="50px" width="auto">
<span style="float: right;">(5.3)</span>
</div>
<div align="center">
<image src="images/4.png" height="50px" width="auto">
<span style="float: right;">(5.4)</span>
</div>
To derive the expression for the junction potential, we must realize that the potential prevents further motion of carriers once equilibrium is reached. Thus, the electron (or hole) concentrations on either side of the junction can be written in terms of the contact potential (V<sub>0</sub>) as
<div align="center">
<image src="images/5.png" height="50px" width="auto">
<span style="float: right;">(5.5)</span>
</div>
<div align="center">
<image src="images/6.png" height="50px" width="auto">
<span style="float: right;">(5.6)</span>
</div>
<div align="center">
<image src="images/7.png" height="50px" width="auto">
<span style="float: right;">(5.7)</span>
</div>

### Electric Field
An electric field is created in the depletion region by the separation of positive and negative space charge densities. Figure 3 shows the volume charge density distribution in the pn junction assuming uniform doping and assuming an abrupt junction approximation. 
<div align="center">
<image src="images/fig_7.3.png" >
<span style="float: right;">(Fig 5.3)</span>
</div>
The depletion width typically extends on both the n and p side with relative widths inversely proportional to the dopant concentration,
 
<div align="center">
<image src="images/8.png" height="50px" width="auto">
<span style="float: right;">(5.8)</span>
</div>
Where width of the depletion region in the p side is w<sub>p</sub> and that of the n side is w<sub>n</sub>.
We can find the relationship between the distribution of electric fields within the depletion region and the net charge. In a one dimension interface,
<div align="center">
<image src="images/9.png" height="50px" width="auto">
<span style="float: right;">(5.9)</span>
</div>

<div align="center">
<image src="images/10.png" height="50px" width="auto">
<span style="float: right;">(5.10)</span>
</div>

<div align="center">
<image src="images/11.png" height="50px" width="auto">
<span style="float: right;">(5.11)</span>
</div>
<div align="center">
<image src="images/12.png" height="50px" width="auto">
<span style="float: right;">(5.12)</span>
</div>
<div align="center">
<image src="images/13.png" height="50px" width="auto">
<span style="float: right;">(5.13)</span>
</div>
Before the junction is formed, the Fermi levels in the extrinsic semiconductors can be calculated individually by considering the shift from the intrinsic Fermi level. This is given by
<div align="center">
<image src="images/14.png" height="50px" width="auto">
<span style="float: right;">(5.14)</span>
</div>
<div align="center">
<image src="images/15.png" height="50px" width="auto">
<span style="float: right;">(5.15)</span>
</div>
For the n type semiconductor the Fermi level is located above the intrinsic level while for the p type semiconductor it is located below the intrinsic level. When the junction is formed, as shown in the energy band diagram, the Fermi levels line up. For this to happen, either the p Fermi level can be considered to have shifted up or the n level can be considered to have shifted down or both. The magnitude of the shift is given by the di erence in the work functions, which is proportional to the Fermi level positions. So the shift is equal to the di erence in Fermi level positions and is given by
<div align="center">
<image src="images/16.png" height="50px" width="auto">
<span style="float: right;">(5.16)</span>
</div>
Thus, the contact potential developed in a pn junction due to the motion of the charge carriers is nothing but the shift in Fermi levels to achieve equilibrium. This is related to another definition of the Fermi level which is the work done to remove or add an electron to a material.

### Depletion Width
The electric field is related to electric potential by
<div align="center">
<image src="images/17.png" height="50px" width="auto">
<span style="float: right;">(5.17)</span>
</div>
<div align="center">
<image src="images/18.png" height="50px" width="auto">
<span style="float: right;">(5.18)</span>
</div>
<div align="center">
<image src="images/19.png" height="50px" width="auto">
<span style="float: right;">(5.19)</span>
</div>
Since the electric field is continuous, both these equations should be equal at x = 0
<div align="center">
<image src="images/20.png" height="50px" width="auto">
<span style="float: right;">(5.20)</span>
</div>
<div align="center">
<image src="images/21.png" height="50px" width="auto">
<span style="float: right;">(5.21)</span>
</div>
<div align="center">
<image src="images/22.png" height="50px" width="auto">
<span style="float: right;">(5.22)</span>
</div>
<div align="center">
<image src="images/23.png" height="50px" width="auto">
<span style="float: right;">(5.23)</span>
</div>
<div align="center">
<image src="images/24.png" height="50px" width="auto">
<span style="float: right;">(5.24)</span>
</div> 
<div align="center">
<image src="images/25.png" height="50px" width="auto">
<span style="float: right;">(5.25)</span>
</div>

### Non-uniformly Doped Junctions
#### Linearly Graded Junctions
If we start with a uniformly doped n-type semiconductor, for example, and diffuse acceptor atoms through the surface, the impurity concentrations will tend to be like those shown in Figure Fig 4. The point x = x' on the figure corresponds to the metallurgical junction. The depletion region extends into the p and n regions from the metallurgical junction as we have discussed previously. The net p-type doping concentration near the metallurgical junction may be approximated as a linear function of distance from the metallurgical junction. Similarly the n type doping concentration isa linear function extending from the metallurgical junction
<div align="center">
<image src="images/fig_7.4.png" >
<span style="float: right;">(Fig 5.4)</span>
</div>
For convenience the junction is placed at x=0. The space charge density can be written as 
<div align="center">
<image src="images/26.png" height="50px" width="auto">
<span style="float: right;">(5.26)</span>
</div>
Where a is the gradient of the net impurity concentration. The electric field and concentration can be found by Poisson's equation. We can write
<div align="center">
<image src="images/27.png" height="50px" width="auto">
<span style="float: right;">(5.27)</span>
</div>
<div align="center">
<image src="images/28.png" height="50px" width="auto">
<span style="float: right;">(5.28)</span>
</div>
The electric field in the linearly graded junction is a quadratic function of distance rather than the linear function found in the uniformly doped junction.The potential is again found by integrating the electric field as 
<div align="center">
<image src="images/29.png" height="50px" width="auto">
<span style="float: right;">(5.29)</span>
</div>
Say &phi;(x) = 0  at x = -x<sub>0</sub>
<div align="center">
<image src="images/30.png" height="50px" width="auto">
<span style="float: right;">(5.30)</span>
</div>
The magnitude of the potential at x = +.ro will equal the built-in potential barrier for this function. We then have that 
<div align="center">
<image src="images/31.png" height="50px" width="auto">
<span style="float: right;">(5.31)</span>
</div>
#### Hyperabrupt Junctions
The uniformly doped junction and linearly graded junction are not the only possible doping profiles. Figure 7.15 shows a generalized one-sided p+n junction where the generalized n-type doping concentration for x > 0 is given by
<div align="center">
<image src="images/32.png" height="50px" width="auto">
<span style="float: right;">(5.32)</span>
</div> 
When the value of m is negative, we have what is referred to as a hyperabrupt junction. In this case, the n-type doping is larger near the metallurgical junction than in the bulk semiconductor. The above equation is used to approximate the n-type doping over a small region near x = xu and does not hold at x = 0 when m is negative.

## References
1. S.M. Sze, "Physics of Semiconductor Devices"
2. Robert F. Pierret, "Semiconductor Device Fundamentals"
3. Ben G. Streetman, "Solid State Electronic Devices"

## Additional Resources
- [Interactive Semiconductor Simulations](https://www.semiconductors.org)
- [Online Calculator Tools](https://www.electronics-tutorials.com)
- [Video Lectures and Demonstrations](https://www.nptel.ac.in)