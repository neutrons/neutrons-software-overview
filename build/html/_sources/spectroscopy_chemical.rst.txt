Spectroscopy - Chemical Spectroscopy Group
==================================

.. _spectroscopy_chemical:

Overview
-----------------------------------
The subject matter for the Chemical Spectroscopy Group is vibrational or 
diffusive dynamics, which often attracts scientists with a biology or chemistry 
background. However, technically, what the two instruments (VISION & BASIS) 
measure are very different, and consequently the data analysis workflows 
are also different.

Data Reduction Process
-----------------------------------
At BASIS, most users are assisted by the instrument scientists to reduce 
the data. There are existing algorithms in Mantid and experienced users 
can easily reduce the data by themselves. At VISION, all data is reduced 
automatically. These are python scripts that are view for anyone to inspect 
at analysis.sns.gov. Some of the post-reduction operations include merging 
the data that is saved hour by hour and smoothing. For the NSE instrument 
(part of the SANS & Spin Echo Group), which is a very different technique 
than all the other instruments, the reduction software that is used is DrSpine.

At VISION, all data is reduced automatically. These are python scripts that 
are view for anyone to inspect at analysis.sns.gov. Some of the post-reduction 
operations include merging the data that is saved hour by hour and smoothing.

For the NSE instrument (part of the SANS & Spin Echo Group), which is a very 
different technique than all the other instruments, the reduction software 
that is used is DrSpine.

Data Reduction Software
-----------------------------------

Mantid
```````````````````````````````
Overview
    “The Mantid project provides a framework that supports high-performance 
    computing and visualization of scientific data. Mantid has been created 
    to manipulate and analyze Neutron and Muon scattering data but could be 
    applied to many other techniques.” [21]
Useful Links and Resources
    The Mantid website includes downloads, tutorials, user documentation, 
    developer documentation, and more.

DrSPINE
```````````````````````````````
Overview
    “DrSPINE is a software package that performs data reduction and analysis 
    for reactor and pulsed source based Neutron Spin Echo experiments.” [22]

Useful Links and Resources
    “DrSPINE is a software package that performs data reduction and analysis 
    for reactor and pulsed source based Neutron Spin Echo experiments.” [22]

Data Analysis Process
-----------------------------------

Spectroscopy investigates interactions, while, for example, 
Diffraction investigates how atoms are arranged. Interactions 
are more complicated than structure and, for example, a magnetism 
perspective may be relevant.

Data Analysis Software
-----------------------------------
There are lots of software packages that can be used, it is ultimately the 
user’s choice. The data is usually a 1-dimensional spectrum. Oclimax is one 
example of software that is being used. Some of the main functions include 
analyzing lattice dynamics, phonon calculations.

Oclimax
```````````````````````````````
Overview
    “A program for the calculation of inelastic nuclear scattering.” [23]

Useful Links and Resources
    Website. An introduction, examples, and installation can be found in 
    this presentation.

JScatter
```````````````````````````````

Overview
    “Jscatter is a python package that provides useful models for neutron 
    and X-ray scattering form factors, structure factors, and dynamic 
    models (quasi elastic neutron scattering) and other topics.” [24]

Useful Links and Resources
    “Jscatter is a python package that provides useful models for neutron 
    and X-ray scattering form factors, structure factors, and dynamic 
    models (quasi elastic neutron scattering) and other topics.” [24]
