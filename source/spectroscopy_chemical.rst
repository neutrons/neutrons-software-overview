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

Data Reduction Software
-----------------------------------


Dave
```````````````````````````````
Overview
    “The main objective of DAVE is to provide a user friendly tool for 
    scientists involved in neutron scattering research to quickly reduce, 
    visualize and interpret their data” [11]

Useful Links and Resources
    The Dave website includes links to user manuals, paper, documentation, 
    course notes, downloads, features, screenshots, changelogs, and more.

Shiver
```````````````````````````````
Overview
    “The main objective of DAVE is to provide a user friendly tool for 
    scientists involved in neutron scattering research to quickly reduce, 
    visualize and interpret their data” [11]

Useful Links and Resources
    “Tool (desktop application) for allowing the examination of Time of 
    Flight (ToF) inelastic neutron data, from single crystal, direct 
    geometry experiments.” [12]

Horace
```````````````````````````````
Overview
    “Horace is a suite of programs for the visualization and analysis of large 
    datasets from time-of-flight neutron inelastic scattering spectrometers.” [13]

Useful Links and Resources
    User documentation, developer documentation, source code, examples, local 
    installation. To use in the analysis cluster, open Matlab, then type ‘horace’ 
    in the command line.

Data Analysis Process
-----------------------------------

Spectroscopy investigates interactions, while, for example, 
Diffraction investigates how atoms are arranged. Interactions 
are more complicated than structure and, for example, a magnetism 
perspective may be relevant.

Data Analysis Software
-----------------------------------

SpinW
```````````````````````````````
Overview
    “SpinW is a MATLAB, Python, and C++ library that can plot and numerically 
    simulate magnetic structures and excitations of given spin Hamiltonian using 
    classical Monte Carlo simulation and linear spin wave theory.” [14]

Useful Links and Resources
    Source code, official documentation. The SpinW website also includes documentation, 
    installation instructions, tutorials, publications, presentations, and more.

Sunny
```````````````````````````````

Overview
    “Sunny is a Julia package for modeling atomic-scale magnetism. It provides powerful 
    tools to study equilibrium and non-equilibrium magnetic phenomena. In particular, it 
    allows estimation of dynamical structure factor intensities, S(q,w), to support quantitative 
    modeling of experimental scattering data.” [15]

Useful Links and Resources
    Documentation, github

Phonopy
```````````````````````````````

Overview
    “Phono3py is another open source package for phonon-phonon interaction and lattice thermal 
    conductivity calculations.” [16]

Useful Links and Resources
    The Phonopy website includes guides, documentation, features, and more.

GSAS-II
```````````````````````````````

Overview
    “GSAS-II is used to analyze all types of x-ray and neutron diffraction data, including 
    single-crystal, powder, constant-wavelength, pink-beam and time-of-flight, lab, synchrotron, 
    spallation and reactor sources, including Rietveld analysis.” [17]

Useful Links and Resources
    The GSAS-II website includes developer documentation, tutorials, and source code.

Spice/Graffiti
```````````````````````````````

Overview
    “SPICE is a LabVIEW based program designed for control of neutron scattering instruments. 
    Currently, SPICE is being used on the HB1 and HB3 triple-axis spectrometers at the High Flux 
    Isotope Reactor at Oak Ridge National Laboratory.” [18]

Useful Links and Resources
    The Spice website includes introductions, user guides, downloads, and more.

multiphonon
```````````````````````````````

Overview
    “Powder spectra measured by inelastic neutron spectrometers provide information such as phonon 
    density of states (DOS), a fundamental property of a solid. The measured spectra, however, are 
    two-dimensional in axes of Q (momentum transfer) and E (energy transfer). This code converts a 
    S(Q,E) INS spectrum to DOS.” [19]

Useful Links and Resources
    Documentation, github, examples

