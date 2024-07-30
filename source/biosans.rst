Small Angle Neutron Scattering - BIO-SANS
==================================

.. _biosans:

Overview
-----------------------------------
Bio-SANS users are focused on Biology and biomaterials.

Data Reduction Process
-----------------------------------
They currently use jupyter scripts. Mantid is another way
to do the reduction. The staff at ORNL use DRT-SANS to reduce the data.

Data Reduction Software
-----------------------------------

Mantid
`````````````````````
Overview
    “The Mantid project provides a framework that supports high-
    performance computing and visualization of scientific data.
    Mantid has been created to manipulate and analyze Neutron
    and Muon scattering data but could be applied to many other
    techniques” (`Mantid Contributors <https://mantidproject.org/Mantid_About.html>`_).

Useful Links and Resources
* The Mantid `website <https://www.mantidproject.org/>`_ includes downloads, tutorials, user documentation, developer documentation, and more.

drt-sans
`````````````````````
Overview
    “Instrument scientists can calibrate instruments and reduce
    large quantities of datasets. Users can correct the collected data
    with dark current subtraction and normalization by neutron
    flux, detector sensitivity, solid angle subtended by the detectors,
    and scaling to absolute units.” [26]

Useful Links and Resources
    * `Documentation <https://drtsans.readthedocs.io/en/latest/>`_
    * `paper <https://www.sciencedirect.com/science/article/pii/S2352711022000681>`_
    * `source code <https://drtsans.readthedocs.io/en/latest/>`
.. list-table:: BIO-SANS Data Reduction Software Links
   :widths: 25 25 25 25 25 25
   :header-rows: 1

   * - Software
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language
   * - Mantid
     - `Yes <https://developer.mantidproject.org/>`_
     - `Yes <https://docs.mantidproject.org/nightly/>`_
     - `Yes <https://github.com/mantidproject/mantid>`_
     - `Yes <https://ieeexplore.ieee.org/document/9377836>`_
     - C++ and Python
   * - drtSANS
     - `Yes <https://drtsans.readthedocs.io/en/latest/>`_
     - No
     - `Yes <https://drtsans.readthedocs.io/en/latest/>`_
     - `Yes <https://www.sciencedirect.com/science/article/pii/S2352711022000681>`_
     - Python
Data Analysis Process
-----------------------------------
A large proportion of users are dependent on the instrument scientists to do the
analysis for them. There are a lot of software that can be used. A few examples are
ATSAS, BioXTAS RAW, SasView, and Igor. ATSAS is a biological databank.
BIOXTAS RAW can do Guinier analysis. SasView is used for shape-dependent
analysis. Igor has a higher learning curve but is well-established in the field.

Data Analysis Software
-----------------------------------

ATSAS
```````````````````````````````
Overview
    “The ATSAS software suite encompasses a number of
    programs for the processing, visualization, analysis and
    modelling of small-angle scattering data, with a focus
    on the data measured from biological macromolecules” (`ATSAS Paper <https://pubmed.ncbi.nlm.nih.gov/33833657/>`_).

Useful Links and Resources
    The `EMBL Hamburg website <https://www.embl-hamburg.de/biosaxs/software.html>`_ has
    downloads, tutorials, manuals, a paper, and more.

BioXTAS RAW
```````````````````````````````
Overview
    “BioXTAS RAW is a GUI based, free, open-source
    Python program for reduction and analysis of small-
    angle X-ray solution scattering (SAXS) data. The
    software is designed for biological SAXS data” (`BioXTAS RAW Contributors <https://bioxtas-raw.readthedocs.io/en/latest/>`_).

Useful Links and Resources
    The `BioXTAS website <https://bioxtas-raw.readthedocs.io/en/latest/>`_ has
    installation, tutorials, manuals,
    documentation, and more.

SasView
```````````````````````````````
Overview
    “The aim of the SasView project is to provide open source, 
    collaboratively developed software for the analysis of any 
    small angle scattering data” (`SasView Contributors <https://www.sasview.org/about/>`_).
Useful Links and Resources
    * `Github <https://github.com/SasView/sasview>`_
    * The SasView `website <https://www.sasview.org/>`_ includes documentation, about, downloads, tutorials.

IgorPro
```````````````````````````````
Overview
    “IgorPro is an interactive software environment for
    experimentation with scientific and engineering data. Igor
    provides many analysis capabilities, including curve fitting,
    peak analysis, signal processing and statistics, and much
    more” (`WaveMetrics <https://www.wavemetrics.com/products/igorpro>`_).

Useful Links and Resources
    * The WaveMetrics `website <https://www.wavemetrics.com/>`_ includes downloads, case studies, manuals, and more.




.. list-table:: BIO-SANS Data Analysis Software Links
   :widths: 25 25 25 25 25 25
   :header-rows: 1

   * - Software
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language
   * - ATSAS
     - No
     - `Yes <https://www.embl-hamburg.de/biosaxs/courses/>`_
     - `Yes <https://www.embl-hamburg.de/biosaxs/software.html>`_
     - `Yes <https://journals.iucr.org/j/issues/2021/01/00/ge5081/index.html>`_
     - Unknown
   * - BIOXTAS RAW
     - `Yes <https://bioxtas-raw.readthedocs.io>`_
     - `Yes <https://bioxtas-raw.readthedocs.io/en/latest/tutorial.html>`_
     - `Yes <https://github.com/jbhopkins/bioxtasraw>`_
     - `Yes <https://journals.iucr.org/paper?S0021889809023863>`_
     - Python
   * - SasView
     - `Yes <https://www.sasview.org/documentation>`_
     - `Yes <https://www.sasview.org/documentation>`_
     - `Yes <https://github.com/SasView/sasview>`_
     - No
     - Python
   * - IRENA
     - `Yes <https://usaxs.xray.aps.anl.gov/software/irena>`_
     - `Yes <http://saxs-igorcodedocs.readthedocs.io/>`_
     - `Yes <https://github.com/jilavsky/SAXS_IgorCode>`_
     - `Yes <https://journals.iucr.org/paper?S0021889809002222>`_
     - IgorPro
