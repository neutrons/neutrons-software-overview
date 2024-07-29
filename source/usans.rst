<<<<<<< HEAD
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

USANSRED
```````````````````````````````
Useful Links and Resources
* `Documentation <https://usansred.readthedocs.io/en/latest/>`_
* `Github <https://github.com/neutrons/usansred>`_
* `ORNL Source Code <https://code.ornl.gov/rys/usans-reduction/>`_

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
There is software that is reaching the end of its lifecycle such IRENA, which is a
suite of Igor Pro. However, SASView is the industry standard for data analysis with
SANS instruments. You can hook SASView with Tensorflow or Pytorch, but there is
no known documentation on this.


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

=======
Small Angle Neutron Scattering - Ultra Small Angle Neutron Scattering (USANS)
==================================

Overview
-----------------------------------
USANS users are focused on .



Data Reduction Process
-----------------------------------
They currently use two different scripts, drtsans and USANSRED. 

Data Reduction Software
-----------------------------------
drtsans
```````````````````````````````
Overview
    “Instrument scientists can calibrate instruments and reduce
    large quantities of datasets. Users can correct the collected data
    with dark current subtraction and normalization by neutron
    flux, detector sensitivity, solid angle subtended by the detectors,
    and scaling to absolute units.” [26]

USANSRED
```````````````````````````````
Overview
    USANSRED is branched off from USANSDATA to be the data reduction section of the code.

.. list-table:: USANS Reduction Software Links
   :widths:  25 25 25 25 25 25
   :header-rows: 1

   * - Software
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language
   * - drtsans
     - `Yes <https://drtsans.readthedocs.io/en/latest/>`_
     - No
     - `Yes <https://drtsans.readthedocs.io/en/latest/>`_
     - `Yes <https://www.sciencedirect.com/science/article/pii/S2352711022000681>`_
     - Python
   * - USANSRED
     - `Yes <https://usansred.readthedocs.io/>`_
     - `Yes <https://usansred.readthedocs.io/en/latest/>`_
     - `Yes <https://github.com/neutrons/usansred>`_
     - No
     - Python

Data Analysis Software
----------------------------------
USANSDATA
```````````````````````````````
Overview
    USANSDATA is 

.. list-table:: USANS Analysis Software Links
   :widths: 25 25 25 25 25 25
   :header-rows: 1

   * - Software
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language
   * - USANSDATA
     - No
     - `Yes <https://code.ornl.gov/rys/usans-reduction/>`_
     - `Yes <https://code.ornl.gov/rys/usans-reduction/>`_
     - No
     - Python

>>>>>>> e8bccebfacf1f131ce5ab514eec5b91214dbea52
