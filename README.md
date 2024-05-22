# Analytical-Solutions-for-Rapidly-Rotating-Stars

This series of Jupyter notebooks provides an effective and economical method for obtaining the structures of rapidly rotating polytropic stars and calculating other physical parameters, such as the mass and volume of the star. 
These Python codes are based on the Izumi and Hachisu algorithm (https://articles.adsabs.harvard.edu//full/1986ApJS...61..479H/0000479.000.html), which calculates equilibrium configurations of rapidly rotating polytropic stars. 
These stars consist of an ideal fluid with a polytropic equation of state P = Kρ^γ.  
The procedure is iterative. You begin with an initial guess of the density profile. The algorithm then analytically solves the equations and returns a new density, which is used for the next iteration. This process continues 
until the desired accuracy in the solutions is achieved.

For some polytropic indexes, an analytical solution of the equations is not possible. To address this, one notebook that fits a polynomial in the density’s expression was used. This fitting approach avoids polynomials under roots, 
simplifies the addition of higher-order angular terms, and makes integration more manageable.

For further details on the iteration procedure, accuracy of the solutions and solutions to problems encountered with the analytical approach, please refer to my Bachelor Thesis 
(https://ikee.lib.auth.gr/record/352706/files/Bachelor%20thesis.pdf), for which these notebooks were developed.

The notebooks consists of:

1. The HSCF_code.ipynb
2. Fitting.ipynb
3. Virial.ipynb
4. Mass_Volume.ipynb
5. Structure_plot.ipynb

You may also find some .png files where you can see some models produced with these notebooks.
