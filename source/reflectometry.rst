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
Each of these instruments have their own reduction software. For MAGREF, the
software is QuickNXS and for LIQREF, the software is RefRed.

.. list-table:: Reflectometry Data Reduction Software Links
   :widths: 15 25 13 11 10 15
   :header-rows: 1

   * - Software
     - Description
     - Documentation
     - User Guide
     - Source Code
     - Coding Language
   * - MagnetismReflectometer
     - Auto reduction Script For the Magnetic Reflectometer
     - `Read the docs <https://mr-reduction.readthedocs.io>`_
     - --
     - `GitHub <https://github.com/neutrons/MagnetismReflectometer>`_
     - Python
   * - QuickNXS
     - Software For the Magnetic Reflectometer
     - --
     - `Manual <https://sns.gov/sites/default/files/Magnetism-Reflectometer-Data-Reduction-Manual.pdf>`_
     - `GitHub <https://github.com/aglavic/quicknxs>`_
     - Python
   * - LiquidsReflectometer
     - Auto reduction Script For the Liquid Reflectometer
     - --
     - --
     - `GitHub <https://github.com/neutrons/LiquidsReflectometer>`_
     - Python
   * - RefRed
     - Data Reduction Software for the Liquids Reflectometer at the Spallation Neutron Source at Oak Ridge National Laboratory” (`RefRed Contributors <https://github.com/neutrons/RefRed>`_).
     - --
     - --
     - `GitHub <https://github.com/neutrons/RefRed>`_
     - Python


Data Analysis Software
-----------------------------------
.. list-table:: Reflectometry Data Analysis Software Links
   :widths: 8 25 13 11 10 8 15
   :header-rows: 1

   * - Software
     - Description
     - Documentation
     - User Guide
     - Source Code
     - Paper
     - Coding Language
   * - Refl1D
     - Refl1D is a program for analyzing 1D reflectometry measurements made with X-ray and neutron beamlines. The 1-D models give the depth profile for material scattering density composed of a mixture of flat and continuously varying freeform layers. With polarized neutron measurements, scientists can study the sub-surface structure of magnetic samples. The architecture supports the addition of specialized layer types such as models for the density distribution of polymer brushes, and volume space modeling for proteins in bio-membranes (`Refl1D Contributors <https://github.com/reflectometry/refl1d>`_).
     - `Read the docs <https://refl1d.readthedocs.io/en/latest/>`_
     - `Tutorial <https://refl1d.readthedocs.io/en/latest/tutorial/index.html>`_
     - `GitHub <https://github.com/reflectometry/refl1d>`_
     - --
     - Python
   * - Refnx
     - refnx is a flexible, powerful, Python package for generalised curvefitting analysis, specifically neutron and X-ray reflectometry data (`Refnx Contributors <https://refnx.readthedocs.io/en/latest/>`_).
     - `Read the docs <https://refnx.readthedocs.io/en/latest/index.html>`_
     - `Getting Started <https://refnx.readthedocs.io/en/latest/getting_started.html>`_
     - `GitHub <https://github.com/refnx/refnx/tree/main>`_
     - --
     - Python
   * - Genx
     - GenX is a versatile program using the differential evolution algorithm for fitting, primarily, X-ray and neutron reflectivity data, lately also surface x-ray diffraction data (`GenX Contributors <https://aglavic.github.io/genx/>`_).
     - `Documentation <https://aglavic.github.io/genx/doc/>`_
     - `How to use <https://aglavic.github.io/genx/howtouse.html>`_
     - `GitHub <https://github.com/aglavic/genx>`_
     - `Paper <https://journals.iucr.org/j/issues/2022/04/00/ge5118/index.html>`_
     - Python
