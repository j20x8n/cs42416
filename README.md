java c
Mathematical Methods
1. Diffusion-Reaction and Hypoxia of Cellular Spheroids 
The concentration of   a reactant undergoing diffusion and a   first-order   irreversible reaction (or consumption by cells) in a   spherical   catalyst   is   described by   the reaction-   diffusion equation 

a.       Render this equation dimensionless and   show   that there   is   only   one   dimensionless   parameter---the (squared) Thiele modulus Φ2 =   ka2 /D.
b.          Show that the solution for the   dimensionless   concentration   is  
c.          By doing a Taylor   expansion   of   the   dimensionless   solution with respect   to   Φ   in   b,   show that for small Thiele modulus Φ    ≪   1, the concentration   is   described by
C(r)~   1   −   (1   − r2)Φ2 /6
Note that the concentration is finite at the center   of   the   sphere r=0 at   small   Thiele   modulus.
For large spheres, fast reaction or   small diffusivity,   such that   the   Thiele   modulus   is large Φ    >>   1,   expand the exact   solution from r=1 and   large   Φ   to   show   the concentration decays exponentially to zero rapidly from the   surface   and the   concentration approaches   zero at the   center.
d.       (Ref: Murphy et al, J.   of   Royal   Society Interface,   14:   20160851   (2017))
Cancer cells are often aggregated into   a   large   sphere   called   spheroids   for   drug testing. It has been found that cells in the center   of   larger   spheroids tend   to   die because oxygen cannot diffuse into the middle due to uptake   by   cells   closer   to   the   surface of   the spheroids.    You will see the decay   of   the   oxygen   concentration from the surface in figures c to e below,   corresponding   to numerical   solution   of the reaction-diffusion equation and actual measured data.      (Cr    is the concentration at a particular r position and C0    is the oxygen concentration   at   the   surface   (our C∞ ) of   about 267 μM. You can divide the K/D value in fig   f   by the   surface   oxygen concentration to get an estimated average value   of k/D.   (The   scale bar   in g   is   250         microns   and   be   careful   with   the   difference   in K and k.)Use the measured concentration   at the spheroid center   (r=0)   in   fig   e to   determine k/D for each spheroid, given that the radii   of   the   spheroids with   different   numbers   of   cells can be measured from fig g ?    Compare   your   results   to theirs   from   fig.   f.
e.       If   cells only die by hypoxia if   the oxygen   concentration   around   them 代 写Mathematical MethodsJava
代做程序编程语言  is below   Cc   ,
derive an explicit expression for   the   critical   spheroid   size   ac D/k, Cc) below which all cells will   survive. If Cc    is   253 μM   for hypoxia,    what is the actual dimensional   critical   spheroid   size   ac, using   the   average k/D you   have   estimated   ?
2. Cyclic Voltammetry Consider atypical   cyclic voltammetry data shown   below       with   different scan rates.    For the peak   current   of cyclic voltammetry,   the   possible   physical parameters      for the   problem   are
Peak current   Ip      in   C/s
Charge transferred to the electrode nF    in   C/mol, where   n   is   the   valency
Thermal   energy   RT         in J/mol
Surface area of   the electrode A          in m2
Bulk concentration of   the reactant   C∞ in mol/m3
Voltagescan   (sweep) rate   S         in   V/s
Diffusivity   D in   m2/s
a.    Use Buckingham pi theorem to   determine that   the   peak   current   is
Ip = AnFC∞(nFDS/RT)1/2 
The square root scaling with respect   to   the   scan   rate   S   is   shown   on   the   left   plot.
You will need to add   C   (Coulombs) and   mole to the   three   fundamental   units   L,   M   and   time.
b.       Explain   qualitatively why this peak current   corresponds to   a   Damkholer   number   of unity for the surface Faradaic electrode reaction   and   why   it   occurs   at   a voltage roughly equal to   RT/nF   (~25.6mV) above the oxidation   potential, which corresponds to the thermal   energy and barrier of most Faradaic   reactions.

3.    Exact Solution for Cyclic Voltammetry If   the redox reaction of a cyclic voltammetry experiment   becomes   fast   enough,   such   that the Damkohler number is larger   than   1,    then   the   ion   concentration   vanishes   at   the electrode at x=0 and a diffusion   front begins to   expand   away   from   the   electrode:
a.          Solve the above PDE by self-similar   solution   and   show that   the   flux   at   the   electrode is

Such that the   current is
I   =   AnFJ
b.       Determine how the   current   decreases   with   Voltage   V   by   replacing   t   with   the   scan rate   S, S    =   V/t.
c.          The peak current occurs when the voltage   exceeds   the thermal   voltage   (oxidation   potential) V~RT/nF at   sometime t~tp, hence   at Ip,

Recover the scaling result of Problem   2 to get   how   the   peak   current   depends   on the scan rate S and   the   diffusivity   D,   modulo   an   arbitrary   constant.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
