# PolLigMicro
Calculate Polarised Light Microscopy interactions.


1. from PolLigMicro.waves import IPolLig

2. w = IPolLig(l, u1, u2, t, u, p)

l: Wavelength of light (um)

u1: Low RI

u2: High RI

t: Thickness of light (100 um)

u: RI of medium (1.0)

p: number of values calculations (5000)

3. w.plotintrf(pr)

pr: error in analyzing angle (1 degree)

resultant wave and analyzer plane value

4. w.plotintrfwave()

resultant propagating wave
