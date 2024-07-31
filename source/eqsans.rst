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

.. csv-table:: Table of Commonly Used Reduction Software
   :header-rows: 1

   "Name", "Overview", "Useful Links and Resources"
   "drt-sans", "Instrument scientists can calibrate instruments and reduce large quantities of datasets. Users can correct the collected data with dark current subtraction and normalization by neutron flux, detector sensitivity, solid angle subtended by the detectors, and scaling to absolute units. Lastly, conversion from time-of-flight and/or wavelength to 1D or 2D momentum to prepare for analysis (`drt-sans Contributors <https://www.osti.gov/biblio/1839359>`_).", "`Documentation <https://drtsans.readthedocs.io/en/latest/>`_, `Paper <https://www.sciencedirect.com/science/article/pii/S2352711022000681>`_, `Source Code <https://code.ornl.gov/sns-hfir-scse/sans/sans-backend>`_"

.. list-table:: EQ-SANS Reduction Software Links
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

Data Analysis Process
-----------------------------------
    SasView, RAW, Igor Pro, and customer software are typically used to analyze the
    data. Occasionally Jupyter notebooks or Origin is used. Grasp also used to be 
    used because of its reputation for being intuitive, capable, and easy to use.

Data Analysis Software
-----------------------------------

.. csv-table:: Table of Commonly Used Analysis Software
   :header-rows: 1

   "Name", "Overview", "Useful Links and Resources"
   "SasView", "The aim of the SasView project is to provide open source, collaboratively developed software for the analysis of any small angle scattering data (`SasView Contributors <https://www.sasview.org/about/>`_).", "`Github <https://github.com/SasView/sasview>`_. The `SasView website <https://www.sasview.org/>`_ includes documentation, about, downloads, tutorials."
   "Irena", "Irena is data manipulations and analysis toolbox for small-angle scattering (SAXS, SANS, USAXS, USANS) data. It is mostly used for analysis of data in materials science, chemistry, polymers, metallurgy, physics, and other systems of typically solid or liquid samples. It addresses complex systems with size distributions, hierarchical structures, diffraction peaks, etc. (`Irena Contributors <https://usaxs.xray.aps.anl.gov/software/irena>`_).", "The `AGL website <https://usaxs.xray.aps.anl.gov/software/irena>`_ includes downloads, documentation, user info, source code, video tutorials, and more."
   "BioXTAS RAW", "BioXTAS RAW is a GUI based, free, open-source Python program for reduction and analysis of small-angle X-ray solution scattering (SAXS) data. The software is designed for biological SAXS data (`BioXTAS RAW Contributors <https://bioxtas-raw.readthedocs.io/en/latest/>`_).", "The `BioXTAS website <https://bioxtas-raw.readthedocs.io/en/latest/>`_ has installation, tutorials, manuals, documentation, and more."
   "IgorPro", "IgorPro is an interactive software environment for experimentation with scientific and engineering data. Igor provides many analysis capabilities, including curve fitting, peak analysis, signal processing and statistics, and much more (`WaveMetrics <https://www.wavemetrics.com/products/igorpro>`_).", "The `WaveMetrics website <https://www.wavemetrics.com/>`_ includes downloads, case studies, manuals, and more."
   "Origin/OriginPro", "Origin is a powerful data analysis and publication-quality graphing software, tailored to the needs of scientists and engineers. OriginPro offers features such as Peak Fitting, Surface Fitting, Statistics, Signal Processing and Image Handling (`OriginLab <https://www.originlab.com/doc/en/User-Guide/GSB-Intro>`_).", "The `OriginLab website <https://www.originlab.com/>`_ includes links to tutorials, list of apps, showcase, documentation, and more."
   "Grasp", "'GRASP' is a Matlab script application designed for the graphical inspection, analysis and reduction of multi-detector data produced by the Small-Angle Neutron Scattering (SANS) instruments of the Institut Laue-Langevin (ILL) (`Grasp Contributors <https://www.ill.eu/users/support-labs-infrastructure/software-scientific-tools/grasp>`_).", "The `ILL website <https://www.ill.eu/users/support-labs-infrastructure/software-scientific-tools/grasp>`_ includes key features, downloads, documentation, example data, and more."

.. list-table:: BIO-SANS Data Analysis Software Links
   :widths: 25 25 25 25 25 25
   :header-rows: 1

   * - Software
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language
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
   * - BIOXTAS RAW
     - `Yes <https://bioxtas-raw.readthedocs.io>`_
     - `Yes <https://bioxtas-raw.readthedocs.io/en/latest/tutorial.html>`_
     - `Yes <https://github.com/jbhopkins/bioxtasraw>`_
     - `Yes <https://journals.iucr.org/paper?S0021889809023863>`_
     - Python
   * - IgorPro
     - No
     - `Yes <https://www.wavemetrics.com/support>`_
     - `Yes <https://www.wavemetrics.com/downloads/current>`_
     - No
     - Igor
   * - Origin
     - `Yes <https://www.originlab.com/doc/>`_
     - `Yes <https://www.originlab.com/doc/User-Guide>`_
     - `Yes <https://www.originlab.com/index.aspx?go=PRODUCTS/Origin>`_
     - No
     - LabTalk
   * - Grasp
     - `Yes <https://www.ill.eu/users/support-labs-infrastructure/software-scientific-tools/grasp>`_
     - `Yes <https://www.ill.eu/fileadmin/user_upload/ILL/3_Users/Scientific_groups/Large_Scale_Structures/Grasp/Download/grasp_manual.pdf>`_
     - `Yes <https://www.ill.eu/users/support-labs-infrastructure/software-scientific-tools/grasp>`_
     - `Yes <https://journals.iucr.org/j/issues/2023/05/00/jl5070/index.html>`_
     - Python
