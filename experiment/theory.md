### Einstein’s relationship
This equation relates the diffusivity and mobility together.

$$
D_{n} = \frac{KT}{q} \mu _{n} = V_{T}\mu _{n}
$$

K is the Boltzmann's constant =  1.3*10^(-23) J/K <br>
T temperature in K<br>
q is charge = 1.6 * 10^(-19) Coloumbs<br>

### Non-uniformly Doped Junctions
Assume a semiconductor bar divided into two parts (say, part 1 & part 2) such that each part is doped with n type of dopant ( or both with p type) but at different concentrations: lets say, N<sub>D1</sub> and N<sub>D2</sub> respectively such that N<sub>D1</sub>>N<sub>D2</sub>. Whole silicon as well as each individual part is neutral (has no net charge) right after doping.<br>

As part1 has higher concentration of mobile electrons than part 2, the 
mobile electrons from part 1 will diffuse to part 2 (diffusion from higher gradient to lower gradient). Now, part 1 will become positively charged as it has lost electrons, and part 2 will gain some electrons. Since part 1 is positively charged, and part 2 is negatively charged, an electric field will arise that points from part 1 to part 2. This is called the <b>Built-In Electric Field<b>. Built in field results drift current which opposes the diffusion current. The charge separation and the built-in field are shown in the 
bottom of below. <br>

In summary, when we have a region of high doping concentration next to a region of low doping concentration in equilibrium, then we will wind up with a built in electric field (and a built in potential), and the drift current will be equal and opposite to the diffusion current.<br>

<div align="center">
<image src="images/fig_7.4.png" height="300px" width ="auto">
<span style="float: right;">(Fig 5.5)</span>
</div>

The net (total) current equation will be
$$
J_{nT} = -q \mu _{n} n \frac{d\phi}{dx}+qD_{n}\frac{dn}{dx}
$$
 
Where n is the electron concentration, dn/dx is the electron gradient and &phi; is the potential gradient (d&phi;/dx is the electric field). Since in equilibrium, net current is zero,

$$
0 = -q \mu _{n} n \frac{d\phi}{dx}+qD_{n}\frac{dn}{dx}
$$

Using Einstein’s relationship and rearranging the terms, we get

$$
\frac{1}{V_{T}} \frac{d \phi}{dx} = \frac{1}{x}\frac{dn}{dx}
$$

When integrated from x1 to x2,
$$
\frac{1}{V_{T}} \int_{\phi(x_{1})}^{\phi(x_{2})} d\phi = \int_{n(x_{1})}^{n(x_{2})} \frac{1}{n}dn
$$

We obtain,
$$
n_{1} = n_{2} e^{\frac{\phi_{1}-\phi_{2}}{V_{T}}}
$$

If n1= N<sub>D1</sub> and n2=N<sub>D2</sub> as in case of the semiconductor bar, we get built in potential &phi<sub>BI</sub>; as

$$
\phi_{BI} = V_{T} ln \frac{N_{D1}}{N_{D2}}
$$

Corollary, this can be applied for finding potential built up between any two doping concentrations. If one of the dopings is intrinsic value, we get

$$
n(x) = n_{i} e^{\phi(x)}{V_{T}}
$$

#### Linearly Graded Junctions
If we start with a uniformly doped n-type semiconductor, for example, and diffuse acceptor atoms through the surface, the impurity concentrations will tend to be like those shown in Figure Fig 5.4. The point x = x' on the figure corresponds to the metallurgical junction. The depletion region extends into the p and n regions from the metallurgical junction as we have discussed previously. The net p-type doping concentration near the metallurgical junction may be approximated as a linear function of distance from the metallurgical junction. Similarly the n type doping concentration is a linear function extending from the metallurgical junction
<div align="center">
<image src="images/fig_7.4.png" height="300px" width ="auto">
<span style="float: right;">(Fig 5.5)</span>
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