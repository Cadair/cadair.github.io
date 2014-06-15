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
data processing. During my PhD I have focused on high-performance simulations
of the low solar atmosphere studying wave phenomena in magnetic structures.
As well as this I have contributed to work on the automated detection and
tracking of 'Ellerman Bombs' which are small brightening is the solar
chromosphere. I developed a algorithm to identify and track these brightenings
over time which allowed for the detailed statistical analysis of these events
to be performed.

## Publications
<a id='#publications'></a>

### Published
* <a href="http://labs.adsabs.harvard.edu/ui/abs/2013MNRAS.435..689G"
target="_blank"><b>Magnetohydrostatic equilibrium - I. Three-dimensional open
magnetic flux tube in the stratified solar atmosphere</b></a> - Gent, F. A.,
Fedun, V., Mumford, S. J., Erdélyi, R. - *Monthly Notices of the Royal
Astronomical Society* Volume 435, Issue 1, p.689-697 - Oct 2013

* <a href="http://labs.adsabs.harvard.edu/ui/abs/2013SoPh..283..307N"
target="_blank"><b>Statistical Analysis of Small Ellerman Bomb Events</b></a> -
Nelson, C. J., Doyle, J. G., Erdélyi, R., Huang, Z., Madjarska, M.
S., Mathioudakis, M., Mumford, S. J., Reardon, K - *Solar Physics*, Volume 283,
Issue 2, pp.307-323 - Apr 2013.

### Submitted

* <a href="http://labs.adsabs.harvard.edu/adsabs/abs/2013arXiv1305.7415M/"
target="blank_"><b>Generation of Magnetohydrodynamic Waves in Low Solar
 Atmospheric Flux Tubes by Photospheric Motions</b></a> - Mumford, S. J.,
Fedun, V., Erdélyi, R. - re-submitted April 2014

##Conferences
<a id="#conferences"></a>

* UKMHD 2012
* [UKMHD 2013](http://stuartmumford.co.uk/talks/ukmhd2013-talk.pdf)
* [HPC @ Sheffield 2013](http://stuartmumford.co.uk/talks/hpc2013-talk.pdf)
* [SciPy 2013](https://www.youtube.com/watch?v=bXPPTCkaVu8)
  [(Proceedings)](http://conference.scipy.org/proceedings/scipy2013/mumford.html)
* [HPC @ Sheffield 2014](http://stuartmumford.co.uk/talks/hpc2014-poster.pdf)
* [UKMHD 2014](http://stuartmumford.co.uk/talks/ukmhd2014)

## Simulations
<a id='simulations'></a>
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
