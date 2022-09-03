# Turbulence
This Python script, calculates 3D energy spectra. For this purpose, velocity component $(u, v, w)$ should be available in a structured grid in a volume.
Here, an artificial isotropic and homogeneous velocity field is created for demo.
fftn, which calculates discrete Fourier coefficients in n-dimension, is used to obtain the energy spectra. By this point, the energy spectra is a function of $\vec{K}$. Using this relation \
$E(k) = \oint \frac{1}{2} E_{ii}(\vec{K}) dS(k) $, \
the spectra can be defined as a function of scalar wave numer $k$. Scalar k equals to $(K_{i}^2)^{1/2}$, ans $S(k)$ represent the surface area of an sphere of radius $k$.

Parameters:
L = domain width \
dim = sampling resolution
