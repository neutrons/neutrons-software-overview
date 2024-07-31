.. _reflectometry:

Reflectometry
===============================

Overview
-----------------------------------
The Reflectometry Group focuses on probing thin structures through the use of 
neutrons’ refractive properties and can help identify the composition of the
sample. There are two types of reflectometry instruments housed at ORNL,
magnetic and liquid reflectometers.

Data Reduction Process
-----------------------------------
The data reduction is automatically  reduced by an instrument specific script 
or by using an instrument specific software. 


Data Reduction Software
-----------------------------------

MagnetismReflectometer (Auto reduction Script For the Magnetic Reflectometer)
```````````````````````````````
Useful Links and Resources
    There is a repository by the same name for the script with links to its
    documentation.


QuickNXS (Software For the Magnetic Reflectometer)
```````````````````````````````
Useful Links and Resources
   The instrument's user guidance page has a link for an old guide to the 
   software. 


LiquidsReflectometer (Auto reduction Script For the Liquid Reflectometer)
```````````````````````````````

RefRed (Software For the Liquid Reflectometer)
```````````````````````````````  


Data Analysis Software
-----------------------------------

Refl1D (Software For both Reflectometers)
```````````````````````````````
Useful Links and Resources
    There is a repository by the same name for the software with links to its
    documentation.

Refnx
```````````````````````````````
Useful Links and Resources
    There is a repository by the same name for the software with links to its
    documentation.   

Genx (Software For the Magnetic Reflectometer)
```````````````````````````````
Useful Links and Resources
    There is a repository by the same name for the software with links to
    documentation, tutorials, and frequently asked questions.

Data Reduction Software
-----------------------------------
Each of these instruments have their own reduction software. For MAGREF, the
software is QuickNXS and for LIQREF, the software is RefRed.

RefRed
```````````````````````````````
Overview
    “Data Reduction Software for the Liquids Reflectometer at the
    Spallation Neutron Source at Oak Ridge National Laboratory” (`RefRed Contributors <https://github.com/neutrons/RefRed>`_).

Useful Links and Resources
    `Source code <https://github.com/neutrons/RefRed>`_.

.. list-table:: Reflectometry Data Reduction Software Links
   :widths: 25 25 25 25  25
   :header-rows: 1

   * - Software
     - Documentation
     - User Guide
     - Source Code
     - Coding Language
   * - MagnetismReflectometer
     - `Yes <https://mr-reduction.readthedocs.io>`_
     - No
     - `Yes <https://github.com/neutrons/MagnetismReflectometer>`_
     - Python
   * - QuickNXS
     - No
     - `Yes <https://sns.gov/sites/default/files/Magnetism-Reflectometer-Data-Reduction-Manual.pdf>`_
     - `Yes <https://github.com/aglavic/quicknxs>`_
     - Python
   * - LiquidsReflectometer
     - No
     - No
     - `Yes <https://github.com/neutrons/LiquidsReflectometer>`_
     - Python
   * - RefRed
     - No
     - No
     - `Yes <https://github.com/neutrons/RefRed>`_
     - Python


Data Analysis Software
-----------------------------------

.. csv-table:: Table of Commonly Used Analysis Software
   :header-rows: 1

   "Name", "Overview", "Useful Links and Resources"
   "Refl1D", "Refl1D is a program for analyzing 1D reflectometry measurements made with X-ray and neutron beamlines. The 1-D models give the depth profile for material scattering density composed of a mixture of flat and continuously varying freeform layers. With polarized neutron measurements, scientists can study the sub-surface structure of magnetic samples. The architecture supports the addition of specialized layer types such as models for the density distribution of polymer brushes, and volume space modeling for proteins in bio-membranes (`Refl1D Contributors <https://github.com/reflectometry/refl1d>`_).", "`Github <https://github.com/reflectometry/refl1d>`, `Documentation <https://refl1d.readthedocs.io/en/latest/>`_ includes getting started, tutorials, user guide, and documentation."
   "GenX", "GenX is a versatile program using the differential evolution algorithm for fitting, primarily, X-ray and neutron reflectivity data, lately also surface x-ray diffraction data (`GenX Contributors <https://aglavic.github.io/genx/>`_).", "The `GenX website <https://aglavic.github.io/genx/>`_ includes source code, downloads, publications, how to, and more."
   "refnx", "refnx is a flexible, powerful, Python package for generalised curvefitting analysis, specifically neutron and X-ray reflectometry data (`Refnx Contributors <https://refnx.readthedocs.io/en/latest/>`_).", "The `refnx website <https://refnx.readthedocs.io/en/latest/>`_ includes installation, getting started, examples, API reference, and source code."