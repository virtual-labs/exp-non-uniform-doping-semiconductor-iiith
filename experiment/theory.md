### The PN Junction
It is important to realize that the entire semiconductor is a single-crystal material in which one region is doped with acceptor impurity atoms to form the p region and the adjacent region is doped with donor atoms to form the n region. The interface separating the n and p regions is referred to as the metallurgical junction.
Initially, at the metallurgical junction, there is a very large density gradient in both the electron and hole concentrations. Majority carrier electrons in the n region will begin diffusing into the p region and majority carrier holes in the p region will begin diffusing into the n region. If we assume there are no external connections to the semiconductor, then this diffusion process cannot continue indefinitely. As electrons diffuse from the n region, positively charged donor atoms are left behind.
Fig 7.1
The net positively and negatively charged regions are shown in Figure 7.1. These two regions are referred to as the space charge region. Essentially all electrons and holes are swept out of the space charge region by the electric field. Since the space charge region is depleted of any mobile charge, this region is also referred to as the depletion region: these two terms will be used interchangeably. Density gradi- ents still exist in the majority carrier concentrations at each edge of the space charge region. We can think of a density gradient as producing a "diffusion force" that acts on the majority carriers.

### No applied Bias
#### Built in potential Barrier
If we assume that no voltage is applied across the pn junction, then the junction is in thermal equilibrium-the Fermi energy level is constant throughout the entire system. Figure 2 shows the energy-band diagram for the pn junction in thermal equilibrium. The conduction and valence band energies must bend as we go through the space charge region.
Fig 2
The junction acts like a wall, not letting electrons from the n region pass through the barrier to the p region. It ensures that majority and minority carriers in the n and p region are in equilibrium. At equilibrium, the electron(np0) and hole(pp0) concentrations in the p region are
 pp0 = NA
np0 = ni2NA
Similarly, the electron(nn0) and hole(pn0) concentrations in the n region are
nn0 = ND
pn0 = ni2ND
To derive the expression for the junction potential, we must realize that the potential prevents further motion of carriers once equilibrium is reached. Thus, the electron (or hole) concentrations on either side of the junction can be written in terms of the contact potential (V0) as
np0nn0=pn0pp0= exp(eV0KBT) 
V0 = KbTeln(NANDni2)
V0 = Viln(NANDni2)

### Electric Field
An electric field is created in the depletion region by the separation of positive and negative space charge densities. Figure 3 shows the volume charge density distribution in the pn junction assuming uniform doping and assuming an abrupt junction approximation. 
fig 3
The depletion width typically extends on both the n and p side with relative widths inversely proportional to the dopant concentration,
 
wpwn=NDNA 
Where width of the depletion region in the p side is wp and that of the n side is wn.
We can find the relationship between the distribution of electric fields within the depletion region and the net charge. In a one dimension interface,
dEdx=⍴net𝜀

⍴net = -eNA  for wp<x<0

⍴net = eND  for  0<x<wn
E(x) =-eNA 𝜀(x+wp)  for wp<x<0
E(x) =eND 𝜀(x-wn)  for  0<x<wn
Before the junction is formed, the Fermi levels in the extrinsic semiconductors can be calculated individually by considering the shift from the intrinsic Fermi level. This is given by
EFn -EFi = KBT ln(NDni) = 0.36eV
EFp -EFi = -KBT ln(NAni) = -0.42eV
For the n type semiconductor the Fermi level is located above the intrinsic level while for the p type semiconductor it is located below the intrinsic level. When the junction is formed, as shown in the energy band diagram, the Fermi levels line up. For this to happen, either the p Fermi level can be considered to have shifted up or the n level can be considered to have shifted down or both. The magnitude of the shift is given by the di erence in the work functions, which is proportional to the Fermi level positions. So the shift is equal to the di erence in Fermi level positions and is given by
shift =EFn -EFp = 0.36eV-(-0.42) = 0.78eV 
Thus, the contact potential developed in a pn junction due to the motion of the charge carriers is nothing but the shift in Fermi levels to achieve equilibrium. This is related to another definition of the Fermi level which is the work done to remove or add an electron to a material.

### Depletion Width
The electric field is related to electric potential by
E(x) = -dVdx
E(x) =-eNA 𝜀(x+wp)2  for wp<x<0
E(x) =V0-eND 𝜀(x-wn)2   for  0<x<wn
Since the electric field is continuous, both these equations should be equal at x = 0
eNA 𝜀(wp)2 = V0-eND 𝜀(wn)2
V0 =eNA 𝜀(wp2+wn2) 
wp +wn=w0
wpNA = wnND
V0 =eNA 𝜀 w02 NANDNA+ND 
 w0 = 2𝜀V0e(NA+NDNAND)

### Non-uniformly Doped Junctions
#### Linearly Graded Junctions
If we start with a uniformly doped n-type semiconductor, for example, and diffuse acceptor atoms through the surface, the impurity concentrations will tend to be like those shown in Figure Fig 4. The point x = x' on the figure corresponds to the metallurgical junction. The depletion region extends into the p and n regions from the metallurgical junction as we have discussed previously. The net p-type doping concentration near the metallurgical junction may be approximated as a linear function of distance from the metallurgical junction. Similarly the n type doping concentration isa linear function extending from the metallurgical junction
.Fig 4
For convenience the junction is placed at x=0. The space charge density can be written as 
⍴(x)=eax
Where a is the gradient of the net impurity concentration. The electric field and concentration can be found by Poisson's equation. We can write
dEdx =⍴(x)𝜀s =eax𝜀s 
E = eax𝜀sdx =ea2𝜀s(x2- 
The electric field in the linearly graded junction is a quadratic function of distance rather than the linear function found in the uniformly doped junction.The potential is again found by integrating the electric field as 
(x) = -E dx
Say  (x) = 0  at x = -x0

 (x) = ea2𝜀s(x33-x02x)+ea3𝜀sx03
The magnitude of the potential at x = +.ro will equal the built-in potential barrier for this function. We then have that 
 (x) = 2ea3𝜀sx03 =Vbi
#### Hyperabrupt Junctions
The uniformly doped junction and linearly graded junction are not the only possible doping profiles. Figure 7.15 shows a generalized one-sided p+n junction where the generalized n-type doping concentration for x > 0 is given by
N = Bxm  
When the value of m is negative, we have what is referred to as a hyperabrupt junction. In this case, the n-type doping is larger near the metallurgical junction than in the bulk semiconductor. The above equation is used to approximate the n-type doping over a small region near x = xu and does not hold at x = 0 when m is negative.

