Spectroscopy - Direct-Geometry and Triple-Axis Group
==================================

.. _spectroscopy_dg_ta:

Data Reduction Process
-----------------------------------
For direct geometry instruments (CNCS, HYSPEC, SEQUIOA, ARCS), 
data is reduced using auto-reduction. These are scripts using mantid. 
These custom scripts live in the instrument computer, where everyone 
has access to them.

For triple-axis (CTAX, PTAX, TAX, VERITAS), data is already reduced. 
The program to visualize these results is Graffiti, which is a part 
of Spice. Graffiti’s underlying software is Labview. Dave, Shiver, 
Horace are all used for reduction or visualization. Visualization 
is important for single crystal, 3D structure.

Data Reduction Software
-----------------------------------

.. list-table:: Chemical Spectroscopy Data Reduction Software Links
   :widths: 8 25 13 11 10 8 15
   :header-rows: 1

   * - Software
     - Description
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language/ Technologies
   * - Mantid
     - "The Mantid project provides a framework that supports high-performance computing and visualization of scientific data. Mantid has been created to manipulate and analyze Neutron and Muon scattering data but could be applied to many other techniques" (`Mantid Contributors <https://mantidproject.org/Mantid_About.html>`_).
     - `Website <https://developer.mantidproject.org/>`_
     - `Docs <https://docs.mantidproject.org/nightly/>`_
     - `GitHub <https://github.com/mantidproject/mantid>`_
     - `Paper <https://ieeexplore.ieee.org/document/9377836>`_
     - C++ and Python
   * - DrSPINE
     - "DrSPINE is a software package that performs data reduction and analysis for reactor and pulsed source based Neutron Spin Echo experiments (`DrSPINE Contributors <https://jugit.fz-juelich.de/nse/drspine/-/tree/pztest>`_)."
     - `Command Guide <https://www.osti.gov/biblio/1883898/>`_
     - `Manual <https://jugit.fz-juelich.de/nse/drspine/-/wikis/manual>`_
     - `Gitlab <https://jugit.fz-juelich.de/nse/drspine/-/tree/pztest>`_
     - `Paper <https://journals.iucr.org/j/issues/2019/05/00/po5149/index.html>`_

     - Fortran & Roff
Data Analysis Process
-----------------------------------

Spectroscopy investigates interactions, while, for example, 
Diffraction investigates how atoms are arranged. Interactions 
are more complicated than structure and, for example, a magnetism 
perspective may be relevant.

Data Analysis Software
----------------------------------- 

.. list-table:: Direct-Geometry and Triple-Axis Data Analysis Software Links
   :widths: 8 25 13 11 10 8 15
   :header-rows: 1

   * - Software
     - Description
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language/ Technologies
   * - Dave
     - "The main objective of DAVE is to provide a user friendly tool for scientists involved in neutron scattering research to quickly reduce, visualize and interpret their data (NIST Center for Neutron Research, 2010)."
     - `Website <https://ncnr.nist.gov/dave/documentation.html>`_
     - --
     - `Website <https://ncnr.nist.gov/dave/download.html>`_
     - `Paper <https://nvlpubs.nist.gov/nistpubs/jres/114/6/V114.N06.A04.pdf>`_
     -  Tcl/Tk & Octave
   * - Shiver
     - "Tool (desktop application) for allowing the examination of Time of Flightchat (ToF) inelastic neutron data, from single crystal, direct geometry experiments (Shiver Contributors)."
     - `Read the docs <https://shiver.readthedocs.io/en/latest/>`_
     - `Guide <https://neutrons.github.io/Shiver/>`_
     - `GitHub <https://github.com/neutrons/Shiver>`_
     - --
     - Python
   * - Horace
     - "Horace is a suite of programs for the visualization and analysis of large datasets from time-of-flight neutron inelastic scattering spectrometers (Horace Contributors)."
     - `GitHub page <https://pace-neutrons.github.io/Horace/v3.6.4/>`_
     - `Guide <https://pace-neutrons.github.io/Horace/v3.6.4/User_guide.html>`_
     - `GitHub <https://github.com/pace-neutrons/Horace>`_
     - `Paper <https://www.sciencedirect.com/science/article/pii/S016890021630777X>`_
     - Matlab
   * - SpinW
     - "SpinW is a MATLAB, Python, and C++ library that can plot and numerically simulate magnetic structures and excitations of given spin Hamiltonian using classical Monte Carlo simulation and linear spin wave theory (SpinW Contributors)."
     - `Website <https://spinw.org/>`_
     - `Tutorial <https://spinw.org/tutorials/>`_
     - `GitHub <https://github.com/spinw/SpinW>`_
     - --
     - Matlab
   * - Sunny
     - "Sunny is a Julia package for modeling atomic-scale magnetism. It provides powerful tools to study equilibrium and non-equilibrium magnetic phenomena. In particular, it allows estimation of dynamical structure factor intensities, S(q,w), to support quantitative modeling of experimental scattering data (Sunny Contributors)."
     - `GitHub page <https://sunnysuite.github.io/Sunny.jl/dev/index.html>`_
     - `Guide <https://github.com/SunnySuite/Sunny.jl/wiki/Getting-started-with-Julia>`_
     - `GitHub <https://github.com/SunnySuite/Sunny.jl>`_
     - --
     - Julia
   * - Phonopy
     - "Phono3py is another open source package for phonon-phonon interaction and lattice thermal conductivity calculations (Phono3py Contributors)."
     - `GitHub page <https://phonopy.github.io/phonopy/index.html>`_
     - --
     - `GitHub <https://github.com/phonopy/phono3py>`_
     - --
     - Python
   * - GSAS-II
     - "GSAS-II is used to analyze all types of x-ray and neutron diffraction data, including single-crystal, powder, constant-wavelength, pink-beam and time-of-flight, lab, synchrotron, spallation and reactor sources, including Rietveld analysis (GSAS-II Contributors)."
     - `Read the docs <https://gsas-ii.readthedocs.io/en/latest/>`_
     - `Guide <https://advancedphotonsource.github.io/GSAS-II-tutorials/tutorials.html>`_
     - `GitHub <https://github.com/AdvancedPhotonSource/GSAS-II>`_
     - --
     - Python
   * - Spice/Graffiti
     - "SPICE is a LabVIEW based program designed for control of neutron scattering instruments. Currently, SPICE is being used on the HB1 and HB3 triple-axis spectrometers at the High Flux Isotope Reactor at Oak Ridge National Laboratory (Spice Contributors)."
     - `Documentation <https://neutron.ornl.gov/spice/User_Downloads.html>`_
     - `How to <https://neutron.ornl.gov/spice/#Howto>`_
     - `Downloads <https://neutron.ornl.gov/spice/User_Downloads.html>`_
     - --
     - LabView, Matlab
   * - Multiphonon
     - "Powder spectra measured by inelastic neutron spectrometers provide information such as phonon density of states (DOS), a fundamental property of a solid. The measured spectra, however, are two-dimensional in axes of Q (momentum transfer) and E (energy transfer). This code converts a S(Q,E) INS spectrum to DOS (Multiphonon Contributors)."
     - `Read the docs <https://multiphonon.readthedocs.io/en/latest/index.html>`_
     - --
     - `Github <https://github.com/neutrons/multiphonon>`_
     - --
     - Python
