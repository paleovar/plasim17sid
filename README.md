# README PlaSim17-LSG with sea ice dynamics

This repository holds an adapted version of the simplified general circulation model PlaSim-LSG \[1-3\] with a component for sea ice dynamics adapted from the more complex general circulation model MITgcm \[4-8\].
Sea ice dynamics are modelled with the viscous-plastic rheology by Hibler, 1979 \[6\] in the implementation by Zhang and Hibler, 1997 \[7\].
An extended abstract covering initial tests and a description of this model extension is currently under review for publication in the Conference Proceedings of VI ECCOMAS Young Investigators Conference 2021.

The original code stack for PlaSim v17 can be obtained from: https://www.mi.uni-hamburg.de/en/arbeitsgruppen/theoretische-meteorologie/modelle/plasim.html

The code stack from MITgcm can be obtained from: https://doi.org/10.5281/zenodo.1409237 and is documented at https://mitgcm.readthedocs.io/en/latest/. The code of the sea ice dynamics component is based upon MITgcm *checkpoint67m*, Oct 16, 2019.

For a description of model changes beyond the the component for sea ice dynamics and for the transient capabilities refer to Andres and Tarasov, 2018 \[9\].

Note that this model configuration is still under development and that this repository is currently being populated. Therefore, the code is already prepared for transient simulations (see \[9\]) but not equipped with the necessary handling of boundary conditions. In the future, a detailed documentation and tutorials will be provided within the scope of the "PaleoPlaSim" model version which is in development at Memorial University of Newfoundland, Canada and at the Institute of Environmental Physics Heidelberg, Germany. For now, as a starting point for the coupled model with sea ice dynamics, see `./model/icedyn`.

Please reach out to the authors for questions:

Moritz Adam,  
*Institute of Environmental Physics Heidelberg, Germany*

Heather J. Andres,  
*Memorial University of Newfoundland, St. John's NL, Canada*

Kira Rehfeld,  
*Geo- und Umweltforschungszentrum, Eberhard Karls Universität Tübingen, Germany* and  
*Institute of Environmental Physics, Heidelberg, Germany*

October 2021

## References

\[1\] K. Fraedrich et al. *Meteorol. Z.* 14.3 (2005), 299–304. doi: https://doi.org/10.1127/0941-2948/2005/0043

\[2\] F. Lunkeit et al. Tech. rep. 2012. url: https://www.mi.uni-hamburg.de/en/arbeitsgruppen/theoretische-meteorologie/modelle/sources/psusersguide.pdf

\[3\] F. Lunkeit et al. Tech. rep. 2012. url: https://www.mi.uni-hamburg.de/en/arbeitsgruppen/theoretische-meteorologie/modelle/sources/psreferencemanual-1.pdf

\[4\] E. Maier-Reimer and U. Mikolajewicz. Tech. rep. Max-Planck-Institut fuer Meteorologie Hamburg, 1992. doi: https://doi.org/10.2312/WDCC/DKRZReport_No02

\[5\] MITgcm Group. Last accessed: 26.05.2021. MIT/EAPS, Cambridge, MA  02139, USA, 2002. doi: https://doi.org/10.5281/zenodo.1409237 url: https://mitgcm.readthedocs.io/en/latest/

\[6\] M. Losch et al. *Ocean Model.* 33.1-2 (2010), 129–144. doi: https://doi.org/10.1016/j.ocemod.2009.12.008

\[7\] W. D. Hibler. *J. Phys. Oceanogr.* (1979), 815-846. doi: [https://doi.org/10.1175/1520-0485(1979)009<0815:ADTSIM>2.0.CO;2](https://doi.org/10.1175/1520-0485(1979)009<0815:ADTSIM>2.0.CO;2)

\[8\] J. Zhang and W. D. Hibler.J. *Geophys. Res.* 102.4 (1997), 412–415. doi: https://doi.org/10.1029/96JC03744

\[9\] H. J. Andres and L. Tarasov. *Clim. Past* 15.4 (2019), 1621–1646. doi: https://doi.org/10.5194/cp-15-1621-2019
