### Einstein’s relationship
This equation relates the diffusivity and mobility together.

$$
D_{n} = \frac{KT}{q} \mu _{n} = V_{T}\mu _{n} 
$$
$$
\tag{5.1}
$$<br>

K is the Boltzmann's constant =  1.3*10<sup>-23</sup> J/K <br>
T temperature in K<br>
q is charge = 1.6 * 10<sup>-19</sup> Coloumbs<br>

### Non-uniformly Doped Junctions
Assume a semiconductor bar divided into two parts (say, part 1 & part 2) such that each part is doped with n type of dopant ( or both with p type) but at different concentrations: lets say, N<sub>D1</sub> and N<sub>D2</sub> respectively such that N<sub>D1</sub>>N<sub>D2</sub>. Whole silicon as well as each individual part is neutral (has no net charge) right after doping.<br>

As part1 has higher concentration of mobile electrons than part 2, the 
mobile electrons from part 1 will diffuse to part 2 (diffusion from higher gradient to lower gradient). Now, part 1 will become positively charged as it has lost electrons, and part 2 will gain some electrons. Since part 1 is positively charged, and part 2 is negatively charged, an electric field will arise that points from part 1 to part 2. This is called the <b>Built-In Electric Field</b>. Built in field results drift current which opposes the diffusion current. The charge separation and the built-in field are shown in the 
bottom of below. <br>

In summary, when we have a region of high doping concentration next to a region of low doping concentration in equilibrium, then we will wind up with a built in electric field (and a built in potential), and the drift current will be equal and opposite to the diffusion current.<br>

<div align="center">
<image src="images/fig_7.1.jpeg" height="300px" width ="auto">
<span style="float: right;">(Fig 5.1)</span>
</div>

The net (total) current equation will be
$$
J_{nT} = -q \mu _{n} n \frac{d\phi}{dx}+qD_{n}\frac{dn}{dx} 
$$
$$
\tag{5.2}
$$<br>
 
Where n is the electron concentration, dn/dx is the electron gradient and &phi; is the potential gradient (d&phi;/dx is the electric field). Since in equilibrium, net current is zero,

$$
0 = -q \mu _{n} n \frac{d\phi}{dx}+qD_{n}\frac{dn}{dx} 
$$
$$
\tag{5.3}
$$<br>

Using Einstein’s relationship and rearranging the terms, we get

$$
\frac{1}{V_{T}} \frac{d \phi}{dx} = \frac{1}{n}\frac{dn}{dx} 
$$
$$
\tag{5.4}
$$<br>

When integrated from x1 to x2,
$$
\frac{1}{V_{T}} \int_{\phi(x_{1})}^{\phi(x_{2})} d\phi = \int_{n(x_{1})}^{n(x_{2})} \frac{1}{n}dn 
$$
$$
\tag{5.5}
$$<br>

We obtain,
$$
n_{1} = n_{2} e^{\frac{\phi_{1}-\phi_{2}}{V_{T}}} 
$$
$$
\tag{5.6}
$$<br>

If n1= N<sub>D1</sub> and n2=N<sub>D2</sub> as in case of the semiconductor bar, we get built in potential &phi;<sub>BI</sub> as

$$
\phi_{BI} = V_{T} ln \frac{N_{D1}}{N_{D2}} 
$$
$$
\tag{5.7}
$$<br>

Corollary, this can be applied for finding potential built up between any two doping concentrations. If one of the dopings is intrinsic value, we get

$$
n(x) = n_{i} e^{\phi(x)}{V_{T}} 
$$
$$
\tag{5.8}
$$<br>

### Space Charge Region or Depletion region.
 When mobile majority carriers diffuse out from doped semiconductor, immobile charged dopant atoms remain behind. The region from where mobile carriers have diffused away is devoid of mobile charges and is called the Depletion region. Width of the depletion region will depend on doping concentration.

### Other junctions:
<b> (a) PN junction</b>: When semiconductor junction is doped, such that one side is p-type and other side is n-type, it is called a PN junction. Diffusion and Drift happen similar to as in a non-uniformly doped junction. (We will go into more detail in the next module). <br>
<b>(b)  Linearly graded junction,</b> as the name implies is a special PN junction, where doping concentration changing linearly with location. <br>
<b>(c) Hyper-abrupt junctions,</b> are PN junctions where doping profile on one side decreases away from the metallurgical junction.
