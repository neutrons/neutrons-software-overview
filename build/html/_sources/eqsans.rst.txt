Small Angle Neutron Scattering - EQ-SANS
==================================

.. _eqsans:

Overview
-----------------------------------
Small Angle Neutron Scattering (SANS) is used to 
measure structures in virtually any material, ranging 
from dilute solutions to dense solids over length scales 
from 1 to >100 nm  (`ORNL, n.d. <https://neutrons.ornl.gov/suites/small-angle-neutron-scattering>`_).

Data Reduction Process
-----------------------------------
Data reduction is performed in various ways: entirely by the instrument
scientists, jointly with users, or independently by users after an initial demonstration.
Data is reduced mainly using scripts. The software package that is used is
typically DRT-SANS.

Data Reduction Software
-----------------------------------

drt-sans
```````````````````````````````
Overview
    “Instrument scientists can calibrate instruments and reduce large
    quantities of datasets. Users can correct the collected data with dark
    current subtraction and normalization by neutron flux, detector
    sensitivity, solid angle subtended by the detectors, and scaling to
    absolute units. Lastly, conversion from time-of-flight and/or
    wavelength to 1D or 2D momentum to prepare for analysis” (`drt-sans Contributors <https://www.osti.gov/biblio/1839359>`_).

Useful Links and Resources
    * `Documentation <https://drtsans.readthedocs.io/en/latest/>`_
    * `Paper <https://www.sciencedirect.com/science/article/pii/S2352711022000681>`_
    * `Source Code <https://code.ornl.gov/sns-hfir-scse/sans/sans-backend>`_

Data Analysis Process
-----------------------------------
    SasView, RAW, Igor Pro, and customer software are typically used to analyze the
    data. Occasionally Jupyter notebooks or Origin is used. Grasp also used to be 
    used because of its reputation for being intuitive, capable, and easy to use.

Data Analysis Software
-----------------------------------

SasView
```````````````````````````````
Overview
    “The aim of the SasView project is to provide open source, 
    collaboratively developed software for the analysis of any 
    small angle scattering data” (`SasView Contributors <https://www.sasview.org/about/>`_).
Useful Links and Resources
    * `Github <https://github.com/SasView/sasview>`_
    * The SasView `website <https://www.sasview.org/>`_ includes documentation, about, downloads, tutorials.

Irena
```````````````````````````````
Overview
    “Irena is data manipulations and analysis toolbox for small-
    angle scattering (SAXS, SANS, USAXS, USANS) data. It is
    mostly used for analysis of data in materials science,
    chemistry, polymers, metallurgy, physics, and other systems
    of typically solid or liquid samples. It addresses complex
    systems with size distributions, hierarchical structures,
    diffraction peaks, etc.” (`Irena Contributors <https://usaxs.xray.aps.anl.gov/software/irena>`_).
Useful Links and Resources
    The AGL `website <https://usaxs.xray.aps.anl.gov/software/irena>`_ includes downloads, documentation, user info, source code, video tutorials, and more.


BioXTAS RAW
```````````````````````````````
Overview
    “BioXTAS RAW is a GUI based, free, open-source Python
    program for reduction and analysis of small-angle X-ray
    solution scattering (SAXS) data. The software is designed
    for biological SAXS data” (`BioXTAS Raw Contrubtors <https://bioxtas-raw.readthedocs.io/en/latest/>`_).
Useful Links and Resources
    The BioXTAS `website <https://bioxtas-raw.readthedocs.io/en/latest/>`_ has installation, tutorials, manuals, documentation, and more.

IgorPro
```````````````````````````````
Overview
    “IgorPro is an interactive software environment for
    experimentation with scientific and engineering data. Igor
    provides many analysis capabilities, including curve fitting,
    peak analysis, signal processing and statistics, and much
    more” (`WaveMetrics <https://www.wavemetrics.com/products/igorpro>`_).

Useful Links and Resources
    The WaveMetrics `website <https://www.wavemetrics.com/>`_ includes downloads, case studies, manuals, and more.

Origin/OriginPro
```````````````````````````````
Overview
    “Origin is a powerful data analysis and publication-quality
    graphing software, tailored to the needs of scientists and
    engineers. OriginPro offers features such as Peak Fitting,
    Surface Fitting, Statistics, Signal Processing and Image
    Handling” (`OriginLab <https://www.originlab.com/doc/en/User-Guide/GSB-Intro>`_).
Useful Links and Resources
    The OriginLab `website <https://www.originlab.com/>`_ includes links to tutorials, list of apps, showcase, documentation, and more.

Grasp
```````````````````````````````
Overview
    “’GRASP’ is a Matlab script application designed for the
    graphical inspection, analysis and reduction of multi-
    detector data produced by the Small-Angle Neutron
    Scattering (SANS) instruments of the Institut Laue-Langevin (ILL)” (`Grasp Contributors <https://www.ill.eu/users/support-labs-infrastructure/software-scientific-tools/grasp>`_).
Useful Links and Resources
    The ILL `website <https://www.ill.eu/users/support-labs-infrastructure/software-scientific-tools/grasp>`_ includes key features, downloads, documentation, example data, and more.

