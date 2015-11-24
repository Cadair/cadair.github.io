<!--
.. title: Research
.. slug: research
.. date: 2014/01/27 20:52:50
.. tags:
.. link:
.. description:
.. type: text
-->

My research interests are varied, however mostly focused around computing and
data processing. During my PhD I have focused on using high-performance computing 
to simulate the low solar atmosphere studying wave phenomena in magnetic structures.
As well as this I have contributed to work on the automated detection and
tracking of 'Ellerman Bombs' which are small brightening is the solar
chromosphere. I developed a algorithm to identify and track these brightenings
over time which allowed for the detailed statistical analysis of these events
to be performed.
I have also been involved in the processing and analysis of data
from the Swedish Solar Telescope, in which evidence of upwardly
propagating waves from a magnetic pore was discovered.

The primary component of the PhD research has been the development
of an analysis pipeline for the identification and quantification of
wave modes in my numerical simulations of the solar atmosphere. This software 
and other supporting tools, have been made availible on GitHub under the
[pysac](https://github.com/SWAT-Sheffield/pysac) project.


## Publications
<a class='anchor' id='publications'></a>

<div class="paperblock">
<a href="http://labs.adsabs.harvard.edu/adsabs/abs/2015arXiv150101871M/"
target="blank_" class="papertitle">Photospheric Logarithmic Velocity Spirals as
MHD Wave Generation Mechanisms</a>
Mumford, S. J. and  Erdélyi, R. <br/>
<i>Monthly Noticies of the Royal Astronomical Society</i> - March 2015 - Volume 449 Issue 2.<br/>
<a href ="http://mnras.oxfordjournals.org/content/449/2/1679">Publisher Link (Open Access)</a> | <a href="https://bitbucket.org/smumford/expansion-factor-paper">Reproduceable repository</a> <br/>
<a href="javascript:toggle('mum2015a_abs', 'mum2015a_link');" id="mum2015a_link">[show abstract]</a>
<div id="mum2015a_abs" style="display: none;">
High-resolution observations of the solar photosphere have
identified a wide variety of spiralling motions in the solar plasma.
These spirals vary in properties, but are observed to be abundant at
the solar surface. In this work, these spirals are studied for their
potential as magnetohydrodynamic (MHD) wave generation mechanisms.
The inter-granular lanes, where these spirals are commonly observed,
are also regions where the magnetic field strength is higher than
average. This combination of magnetic field and spiralling plasma is
a recipe for the generation of Alfvén waves and other MHD waves.
This work employs numerical simulations of a self-similar magnetic
flux tube embedded in a realistic, gravitationally stratified, solar
atmosphere to study the effects of a single magnetic flux tube
perturbed by a logarithmic velocity spiral driver. The expansion
factor of the logarithmic spiral driver is varied and multiple
simulations are run for a range of values of the expansion factor
centred around observational constraints. The simulations are
analysed using ‘flux surfaces’ constructed from the magnetic field
lines so that the vectors perpendicular, parallel and azimuthal to
the local magnetic field vector can be calculated. The results of
this analysis show that the Alfvén wave is the dominant wave for
lower values of the expansion factor, whereas for the higher values
the parallel component is dominant. This transition occurs within
the range of the observational constraints, meaning that spiral
drivers, as observed in the solar photosphere, have the potential to
generate a variety of MHD wave modes. 
</div>
</div>

<div class="paperblock">
<a href="http://labs.adsabs.harvard.edu/adsabs/abs/2013arXiv1305.7415M/"
target="blank_" class="papertitle">Generation of Magnetohydrodynamic Waves in Low Solar
 Atmospheric Flux Tubes by Photospheric Motions</a>
Mumford, S. J., Fedun, V., Erdélyi, R. <br/>
<i>The Astrophysical Journal</i> -  January 2015 - Volume 799, Issue 1. <br/>
<a href="http://iopscience.iop.org/0004-637X/799/1/6/" target="_blank">Publisher Link (Paywall)</a> <br/>
<a href="javascript:toggle('mum2015_abs', 'mum2015_link');" id="mum2015_link">[show abstract]</a>
<div id="mum2015_abs" style="display: none;">
Recent ground- and space-based observations reveal the presence of
small-scale motions between convection cells in the solar
photosphere. In these regions, small-scale magnetic flux tubes are
generated via the interaction of granulation motion and the
background magnetic field. This paper studies the effects of these
motions on magnetohydrodynamic (MHD) wave excitation from broadband
photospheric drivers. Numerical experiments of linear MHD wave
propagation in a magnetic flux tube embedded in a realistic
gravitationally stratified solar atmosphere between the photosphere
and the low choromosphere (above $\beta = 1$) are performed. Horizontal
and vertical velocity field drivers mimic granular buffeting and
solar global oscillations. A uniform torsional driver as well as
Archimedean and logarithmic spiral drivers mimic observed torsional
motions in the solar photosphere. The results are analyzed using a
novel method for extracting the parallel, perpendicular, and
azimuthal components of the perturbations, which caters to both the
linear and non-linear cases. Employing this method yields the
identification of the wave modes excited in the numerical
simulations and enables a comparison of excited modes via velocity
perturbations and wave energy flux. The wave energy flux
distribution is calculated to enable the quantification of the
relative strengths of excited modes. The torsional drivers primarily
excite Alfvén modes (≈60% of the total flux) with small
contributions from the slow kink mode, and, for the logarithmic
spiral driver, small amounts of slow sausage mode. The horizontal
and vertical drivers primarily excite slow kink or fast sausage
modes, respectively, with small variations dependent upon flux
surface radius. 
</div>
</div>


<div class="paperblock">
<a href="http://labs.adsabs.harvard.edu/adsabs/abs/2015CS%26D....8a4009S/"
target="blank_" class="papertitle">SunPy: Python for Solar Physics</a>
The SunPy Community, Mumford, S. J., Christe, S., Pérez-Suárez, D., Ireland,
J., Shih, A. Y., Inglis, A. R., Liedtke, S., Hewett, R. J., Mayer, F., Hughitt,
K., Freij, N., Meszaros, T., Bennett, S. M., Malocha, M., Evans, J., Agrawal,
A., Leonard, A. J., Robitaille, T. P., Mampaey, B., Iván Campos-Rozo, J., Kirk,
M. S.<br/>
<i>Computational Science and Discovery</i> - January 2015 - Volume 8 Issue 1.<br/>
<a href ="http://iopscience.iop.org/article/10.1088/1749-4699/8/1/014009">Publisher Link (Paywall)</a> <br/>
<a href="javascript:toggle('sunpy2015_abs', 'sunpy2015_link');" id="sunpy2015_link">[show abstract]</a>
<div id="sunpy2015_abs" style="display: none;">
This paper presents SunPy (version 0.5), a community-developed Python package
for solar physics. Python, a free, cross-platform, general-purpose, high-level
programming language, has seen widespread adoption among the scientific
community, resulting in the availability of a large number of software
packages, from numerical computation (NumPy, SciPy) and machine learning
(scikit-learn) to visualization and plotting (matplotlib). SunPy is
a data-analysis environment specializing in providing the software necessary to
analyse solar and heliospheric data in Python. SunPy is open-source software
(BSD licence) and has an open and transparent development workflow that anyone
can contribute to. SunPy provides access to solar data through integration with
the Virtual Solar Observatory (VSO), the Heliophysics Event Knowledgebase
(HEK), and the HELiophysics Integrated Observatory (HELIO) webservices. It
currently supports image data from major solar missions (e.g., SDO, SOHO,
STEREO, and IRIS), time-series data from missions such as GOES, SDO/EVE, and
PROBA2/LYRA, and radio spectra from e-Callisto and STEREO/SWAVES. We describe
SunPyʼs functionality, provide examples of solar data analysis in SunPy, and
show how Python-based solar data-analysis can leverage the many existing tools
already available in Python. We discuss the future goals of the project and
encourage interested users to become involved in the planning and development
of SunPy.
</div>
</div>



<div class="paperblock">
<a href="http://labs.adsabs.harvard.edu/adsabs/abs/2014ApJ...791...61F/"
target="_blank" class="papertitle">The Detection of Upwardly Propagating Waves Channeling
Energy from the Chromosphere to the Low Corona</a>
Freij N., Scullion E. M., Nelson C. J., Mumford S. J., Wedemeyer S., and Erdélyi R. <br />
<i>The Astrophysical Journal</i> - July 2014 - Volume 791, Issue 1, p.61 <br />
<a href="http://iopscience.iop.org/0004-637X/791/1/61/" target="_blank"> Publisher Link (Paywall) </a> <br />
<a href="javascript:toggle('freij2014_abs', 'freij2014_link');" id="freij2014_link">[show abstract]</a>
<div id="freij2014_abs" style="display: none;">
There have been ubiquitous observations of wave-like motions in the
solar atmosphere for decades. Recent improvements to space- and
ground-based observatories have allowed the focus to shift to
smaller magnetic structures on the solar surface. In this paper,
high-resolution ground-based data taken using the Swedish 1 m Solar
Telescope is combined with co-spatial and co-temporal data from the
Atmospheric Imaging Assembly (AIA) on board the Solar Dynamics
Observatory (SDO) satellite to analyze running penumbral waves
(RPWs). RPWs have always been thought to be radial wave propagation
that occurs within sunspots. Recent research has suggested that they
are in fact upwardly propagating field-aligned waves (UPWs). Here,
RPWs within a solar pore are observed for the first time and are
interpreted as UPWs due to the lack of a penumbra that is required
to support RPWs. These UPWs are also observed co-spatially and
co-temporally within several SDO/AIA elemental lines that sample the
transition region and low corona. The observed UPWs are traveling at
a horizontal velocity of around 17 ± 0.5 km s-1 and a minimum
vertical velocity of 42 ± 21 km s-1. The estimated energy of the
waves is around 150 W m-2, which is on the lower bound required to
heat the quiet-Sun corona. This is a new, yet unconsidered source of
wave energy within the solar chromosphere and low corona. 
</div>
</div>


<div class="paperblock">
<a href="http://labs.adsabs.harvard.edu/ui/abs/2013MNRAS.435..689G"
target="_blank" class="papertitle">Magnetohydrostatic equilibrium - I. Three-dimensional open
magnetic flux tube in the stratified solar atmosphere</a>

Gent, F. A., Fedun, V., Mumford, S. J., Erdélyi, R. <br />

<i>Monthly Notices of the Royal Astronomical Society</i> - October 2013 - Volume 435, Issue 1, p.689-697 <br />
<a href="http://mnras.oxfordjournals.org/content/435/1/689" target="_blank"> Publisher Link (Paywall) </a> <br />
<a href="javascript:toggle('gent2013_abs', 'gent2013_link');" id="gent2013_link">[show abstract]</a>
<div id="gent2013_abs" style="display: none;">
A single open magnetic flux tube spanning the solar photosphere
(solar radius ≃ R☉) and the lower corona (R☉ + 10 Mm) is modelled in
magnetohydrostatic equilibrium within a realistic stratified
atmosphere subject to solar gravity. Such flux tubes are observed to
remain relatively stable for up to a day or more, and it is our aim
to apply the model as the background condition for numerical studies
of energy transport mechanisms from the surface to the corona. We
solve analytically an axially symmetric 3D structure for the model,
with magnetic field strength, plasma density, pressure and
temperature all consistent with observational and theoretical
estimates. The self-similar construction ensures the magnetic field
is divergence free. The equation of pressure balance for this
particular set of flux tubes can be integrated analytically to find
the pressure and density corrections required to preserve the
magnetohydrostatic equilibrium. The model includes a number of free
parameters, which makes the solution applicable to a variety of
other physical problems and it may therefore be of more general
interest. 
</div>
</div>


 
<div class="paperblock">
<a href="http://labs.adsabs.harvard.edu/ui/abs/2013SoPh..283..307N"
target="_blank" class="papertitle">Statistical Analysis of Small Ellerman Bomb Events</a>

Nelson, C. J., Doyle, J. G., Erdélyi, R., Huang, Z., Madjarska, M. S., Mathioudakis, M., Mumford, S. J., Reardon, K <br />

<i>Solar Physics</i> - April 2013 - Volume 283, Issue 2, p.307-323. <br />
<a href="http://link.springer.com/article/10.1007%2Fs11207-012-0222-3" target="_blank"> Publisher Link (Paywall) </a> <br />
<a href="javascript:toggle('nelson2013_abs', 'nelson2013_link');" id="nelson2013_link">[show abstract]</a>
<div id="nelson2013_abs" style="display: none;">
The properties of Ellerman bombs (EBs), small-scale brightenings in
the Hα line wings, have proved difficult to establish because their
size is close to the spatial resolution of even the most advanced
telescopes. Here, we aim to infer the size and lifetime of EBs using
high-resolution data of an emerging active region collected using
the Interferometric BIdimensional Spectrometer (IBIS) and Rapid
Oscillations of the Solar Atmosphere (ROSA) instruments as well as
the Helioseismic and Magnetic Imager (HMI) onboard the Solar
Dynamics Observatory (SDO). We develop an algorithm to track EBs
through their evolution, finding that EBs can often be much smaller
(around 0.3″) and shorter-lived (less than one minute) than previous
estimates. A correlation between G-band magnetic bright points and
EBs is also found. Combining SDO/HMI and G-band data gives a good
proxy of the polarity for the vertical magnetic field. It is found
that EBs often occur both over regions of opposite polarity flux and
strong unipolar fields, possibly hinting at magnetic reconnection as
a driver of these events.The energetics of EB events is found to
follow a power-law distribution in the range of a nanoflare (1022-25
ergs). 
</div>
</div>



<a id="talks"></a>
</br>
## Conferences &amp; Talks

This is a list off all the conferences I have attended and links to the material
 I presented, where applicable:

* [NAM 2015](http://stuartmumford.uk/talks/nam2015)
* [Python in Astronomy - Invited  Keynote](http://stuartmumford.uk/talks/pia)
* [EuroSciPy 2014](http://stuartmumford.uk/talks/euroscipy2014) - [Video (No Audio)](https://www.youtube.com/watch?v=-Lfz3kBjEyY)
* [NAM 2014](http://stuartmumford.uk/talks/nam2014)
* [UKMHD 2014](http://stuartmumford.uk/talks/ukmhd2014)
* [HPC @ Sheffield 2014](http://stuartmumford.uk/talks/hpc2014-poster.pdf)
* [Harvard-Simthsonian Center for Astrophysics 2013](http://stuartmumford.uk/talks/cfa)  Talk given to the Python user group at CfA.
* [SciPy 2013](https://www.youtube.com/watch?v=bXPPTCkaVu8) [(Proceedings)](http://conference.scipy.org/proceedings/scipy2013/mumford.html)
* [HPC @ Sheffield 2013](http://stuartmumford.uk/talks/hpc2013-talk.pdf)
* [UKMHD 2013](http://stuartmumford.uk/talks/ukmhd2013-talk.pdf)
* UKMHD 2012

<a style="margin-bottom: 10px;" id='simulations'></a>
## Simulations of the Solar Atmosphere
My primary research interest is the simulation and analysis of wave propagation
in magnetic structures in the low solar atmosphere. This involves the use of
the &ldquo;Sheffield Advanced Code&rdquo; a versatile code base able to simulate
wave perturbations on top of any background condition. The design of this code
allows for the study of comparatively small amplitude waves against the high
dynamic range of the solar atmosphere. Between the solar surface (the
photosphere) and the low solar corona the density of the plasma decreases by 8
orders of magnitude. Simulating wave phenomena in this kind of high gradient
atmosphere, under the influence of gravity, is much easier with separate
static background conditions.

My work has focused on the analysis of simulations of a single expanding flux
tube stretching from the photosphere. I developed a new analysis pipeline for
the fast and accurate decomposition of vector quantities in the simulations,
primarily velocity and wave energy flux, into components in the frame of the
magnetic field in three dimensions. To do this I utilised VTK, from Python, and
created a surface from magnetic field lines and used the normal vector from
this surface in addition to the magnetic field vector to compute the new
reference frame.

I have used this analysis method to study the effects of wave generation in
expanding flux tubes by a variety of different simulated drivers. The results
of this study indicated that a wider spectra of magnetohyrodynamic wave modes
are generated from broadband photospheric drivers than previously envisaged.

<div class="video-container">
<iframe src="http://www.youtube.com/embed/9zc6YTp2db4" frameborder="0" width="560" height="315"></iframe>
</div>
