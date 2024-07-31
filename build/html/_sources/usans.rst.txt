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

.. csv-table:: Table of Commonly Used Reduction Software
   :header-rows: 1

   "Name", "Overview", "Useful Links and Resources"
   "drt-sans", "Instrument scientists can calibrate instruments and reduce large quantities of datasets. Users can correct the collected data with dark current subtraction and normalization by neutron flux, detector sensitivity, solid angle subtended by the detectors, and scaling to absolute units. Lastly, conversion from time-of-flight and/or wavelength to 1D or 2D momentum to prepare for analysis (`drt-sans Contributors <https://www.osti.gov/biblio/1839359>`_).", "`Documentation <https://drtsans.readthedocs.io/en/latest/>`_, `Paper <https://www.sciencedirect.com/science/article/pii/S2352711022000681>`_, `Source Code <https://code.ornl.gov/sns-hfir-scse/sans/sans-backend>`_"

Data Analysis Process
-----------------------------------
There is software that is reaching the end of its lifecycle such IRENA, which is a
suite of Igor Pro. However, SASView is the industry standard for data analysis with
SANS instruments. You can hook SASView with Tensorflow or Pytorch, but there is
no known documentation on this.


Data Analysis Software
-----------------------------------

.. csv-table:: Table of Commonly Used Analysis Software
   :header-rows: 1

   "Name", "Overview", "Useful Links and Resources"
   "SasView", "The aim of the SasView project is to provide open source, collaboratively developed software for the analysis of any small angle scattering data (`SasView Contributors <https://www.sasview.org/about/>`_).", "`Github <https://github.com/SasView/sasview>`_. The `SasView website <https://www.sasview.org/>`_ includes documentation, about, downloads, tutorials."
   "Irena", "Irena is data manipulations and analysis toolbox for small-angle scattering (SAXS, SANS, USAXS, USANS) data. It is mostly used for analysis of data in materials science, chemistry, polymers, metallurgy, physics, and other systems of typically solid or liquid samples. It addresses complex systems with size distributions, hierarchical structures, diffraction peaks, etc. (`Irena Contributors <https://usaxs.xray.aps.anl.gov/software/irena>`_).", "The `AGL website <https://usaxs.xray.aps.anl.gov/software/irena>`_ includes downloads, documentation, user info, source code, video tutorials, and more."
