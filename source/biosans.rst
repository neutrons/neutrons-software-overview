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


.. list-table:: BIO-SANS Data Reduction Software Links
   :widths: 25 25 25 25 25 25 25
   :header-rows: 1

   * - Software
     - Description
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language
   * - Mantid
     - The Mantid project provides a framework that supports high-performance computing and visualization of scientific data. Mantid has been created to manipulate 
       and analyze Neutron and Muon scattering data but could be applied to many other techniques (`Mantid Contributors <https://mantidproject.org/Mantid_About.html>`_).
     - `Website <https://developer.mantidproject.org/>`_
     - `Docs <https://docs.mantidproject.org/nightly/>`_
     - `GitHub <https://github.com/mantidproject/mantid>`_
     - `Paper <https://ieeexplore.ieee.org/document/9377836>`_
     - C++ and Python
   * - drtSANS
     - Instrument scientists can calibrate instruments and reduce large quantities of datasets. Users can correct the collected data with dark current subtraction and normalization by neutron flux, detector sensitivity, solid angle subtended by the detectors, and scaling to absolute units (`drt-sans Contributors <https://www.osti.gov/biblio/1839359>`_).
     - `Read the docs <https://drtsans.readthedocs.io/en/latest/>`_
     - --
     - `Code <https://code.ornl.gov/sns-hfir-scse/sans/sans-backend>`_
     - `Paper <https://www.sciencedirect.com/science/article/pii/S2352711022000681>`_
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

.. list-table:: BIO-SANS Data Analysis Software Links
   :widths: 25 25 25 25 25 25 25 
   :header-rows: 1

   * - Software
     - Description
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language
   * - ATSAS
     - The ATSAS software suite encompasses a number of programs for the processing, visualization, analysis and modelling of small-angle scattering data, with a focus on the data measured from biological macromolecules (`ATSAS Paper <https://pubmed.ncbi.nlm.nih.gov/33833657/>`_).
     - --
     - `Maunals <https://www.embl-hamburg.de/biosaxs/manuals/>`_
     - `Website <https://www.embl-hamburg.de/biosaxs/software.html>`_
     - `Paper <https://journals.iucr.org/j/issues/2021/01/00/ge5081/index.html>`_
     - --
   * - BIOXTAS RAW
     - BioXTAS RAW is a GUI based, free, open-source Python program for reduction and analysis of small-angle X-ray solution scattering (SAXS) data. The software is designed for biological SAXS data (`BioXTAS RAW Contributors <https://bioxtas-raw.readthedocs.io/en/latest/>`_).
     - `Read the docs <https://bioxtas-raw.readthedocs.io>`_
     - `Tutorial <https://bioxtas-raw.readthedocs.io/en/latest/tutorial.html>`_
     - `GitHub <https://github.com/jbhopkins/bioxtasraw>`_
     - `Paper <https://journals.iucr.org/paper?S0021889809023863>`_
     - Python
   * - SasView
     - The aim of the SasView project is to provide open source, collaboratively developed software for the analysis of any small angle scattering data (`SasView Contributors <https://www.sasview.org/about/>`_).
     - `Documentation <https://www.sasview.org/documentation>`_
     - `Tutorial <https://www.sasview.org/documentation>`_
     - `GitHub <https://github.com/SasView/sasview>`_
     - --
     - Python
   * - IRENA (IgorPro)
     - IgorPro is an interactive software environment for experimentation with scientific and engineering data. Igor provides many analysis capabilities, including curve fitting, peak analysis, signal processing and statistics, and much more (`WaveMetrics <https://www.wavemetrics.com/products/igorpro>`_).
     - `Website <https://usaxs.xray.aps.anl.gov/software/irena>`_
     - `Read the docs <http://saxs-igorcodedocs.readthedocs.io/>`_
     - `GitHub <https://github.com/jilavsky/SAXS_IgorCode>`_
     - `Paper <https://journals.iucr.org/paper?S0021889809002222>`_
     - IgorPro
