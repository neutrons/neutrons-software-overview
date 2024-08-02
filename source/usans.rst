Small Angle Neutron Scattering - USANS
==================================

.. _usans:

Overview
-----------------------------------


Data Reduction Process
-----------------------------------
For USANS, there is the USANS data reduction package. DRT-SANS can also be used.

Data Reduction Software
-----------------------------------

.. list-table:: USANS Reduction Software Links
   :widths: 8 25 13 11 10 8 15
   :header-rows: 1

   * - Software
     - Description
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language/ Technologies
   * - drtsans
     - "Instrument scientists can calibrate instruments and reduce large quantities of datasets. Users can correct the collected data with dark current subtraction and normalization by neutron flux, detector sensitivity, solid angle subtended by the detectors, and scaling to absolute units. Lastly, conversion from time-of-flight and/or wavelength to 1D or 2D momentum to prepare for analysis" (`drt-sans Contributors <https://www.osti.gov/biblio/1839359>`_).
     - `Read the docs <https://drtsans.readthedocs.io/en/latest/>`_
     - --
     - `Code repository <https://code.ornl.gov/sns-hfir-scse/sans/sans-backend>`_
     - `Paper <https://www.sciencedirect.com/science/article/pii/S2352711022000681>`_
     - Python
   * - USANSRED
     - "Backend code for the reduction of USANS data" (`USANSRED Contributors <https://github.com/neutrons/usansred>`_)
     - `Read the docs <https://usansred.readthedocs.io/>`_
     - `Guide <https://usansred.readthedocs.io/en/latest/source/user/reduce.html/>`_
     - `GitHub <https://github.com/neutrons/usansred>`_
     - --
     - Python

Data Analysis Process
-----------------------------------
There is software that is reaching the end of its lifecycle such IRENA, which is a
suite of Igor Pro. However, SASView is the industry standard for data analysis with
SANS instruments. You can hook SASView with Tensorflow or Pytorch, but there is
no known documentation on this.


Data Analysis Software
-----------------------------------

.. list-table:: USANS Analysis Software Links
   :widths: 8 25 13 11 10 8 15
   :header-rows: 1

   * - Software
     - Description
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language/ Technologies
   * - USANSDATA
     - Python script for USANS data reduction / analysis (`USANSDATA Contributors <https://code.ornl.gov/rys/usans-reduction>`_).
     - --
     - `Code repository <https://code.ornl.gov/rys/usans-reduction/>`_
     - `Code repository <https://code.ornl.gov/rys/usans-reduction/>`_
     - --
     - Python
   * - SasView
     - "The aim of the SasView project is to provide open source, collaboratively developed software for the analysis of any small angle scattering data" (`SasView Contributors <https://www.sasview.org/about/>`_).
     - `Website <https://www.sasview.org/documentation>`_
     - `Tutorial <https://www.sasview.org/documentation>`_
     - `GitHub <https://github.com/SasView/sasview>`_
     - --
     - Python
   * - IRENA 
     - "Irena is data manipulations and analysis toolbox for small-angle scattering (SAXS, SANS, USAXS, USANS) data. It is mostly used for analysis of data in materials science, chemistry, polymers, metallurgy, physics, and other systems of typically solid or liquid samples. It addresses complex systems with size distributions, hierarchical structures, diffraction peaks, etc." (`Irena Contributors <https://usaxs.xray.aps.anl.gov/software/irena>`_).
     - `Website <https://usaxs.xray.aps.anl.gov/software/irena>`_
     - `Read the docs <http://saxs-igorcodedocs.readthedocs.io/>`_
     - `GitHub <https://github.com/jilavsky/SAXS_IgorCode>`_
     - `Paper <https://journals.iucr.org/paper?S0021889809002222>`_
     - IgorPro
