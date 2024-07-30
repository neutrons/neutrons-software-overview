Spectroscopy - Chemical Spectroscopy Group
==================================

.. _spectroscopy_chemical:

Overview
-----------------------------------
The subject matter for the Chemical Spectroscopy Group is vibrational or 
diffusive dynamics, which often attracts scientists with a biology or chemistry 
background. However, technically, what the two instruments (VISION & BASIS) 
measure are very different, and consequently the data analysis workflows 
are also different.

Data Reduction Process
-----------------------------------
At BASIS, most users are assisted by the instrument scientists to reduce 
the data. There are existing algorithms in Mantid and experienced users 
can easily reduce the data by themselves. At VISION, all data is reduced 
automatically. These are python scripts that are view for anyone to inspect 
at analysis.sns.gov. Some of the post-reduction operations include merging 
the data that is saved hour by hour and smoothing. For the NSE instrument 
(part of the SANS & Spin Echo Group), which is a very different technique 
than all the other instruments, the reduction software that is used is DrSpine.

At VISION, all data is reduced automatically. These are python scripts that 
are view for anyone to inspect at analysis.sns.gov. Some of the post-reduction 
operations include merging the data that is saved hour by hour and smoothing.

For the NSE instrument (part of the SANS & Spin Echo Group), which is a very 
different technique than all the other instruments, the reduction software 
that is used is DrSpine.

Data Reduction Software
-----------------------------------

.. csv-table:: Configuration options
   :header-rows: 1

   "Name", "Overview", "Useful Links and Resources"
   "Mantid", "The Mantid project provides a framework that supports high-performance computing and visualization of scientific data. Mantid has been created to manipulate and analyze Neutron and Muon scattering data but could be applied to many other techniques (`Mantid Contributors <https://mantidproject.org/Mantid_About.html>`_).", "The `Mantid website <https://www.mantidproject.org/>`_ includes downloads, tutorials, user documentation, developer documentation, and more."
   "DrSPINE", "DrSPINE is a software package that performs data reduction and analysis for reactor and pulsed source based Neutron Spin Echo experiments (`DrSPINE Contributors <https://jugit.fz-juelich.de/nse/drspine/-/tree/pztest>`_).", "The `Gitlab <https://jugit.fz-juelich.de/nse/drspine/-/tree/pztest>`_ includes manuals, guides, source code, and papers."

Data Analysis Process
-----------------------------------

Spectroscopy investigates interactions, while, for example, 
Diffraction investigates how atoms are arranged. Interactions 
are more complicated than structure and, for example, a magnetism 
perspective may be relevant.

Data Analysis Software
-----------------------------------
There are lots of software packages that can be used, it is ultimately the 
user’s choice. The data is usually a 1-dimensional spectrum. Oclimax is one 
example of software that is being used. Some of the main functions include 
analyzing lattice dynamics, phonon calculations.

Oclimax
```````````````````````````````
Overview
    “A program for the calculation of inelastic nuclear scattering” (`Cheng, 2018 <https://neutrons.ornl.gov/sites/default/files/2018-NXS_Lecture_YQCheng_2.pdf>`_).

Useful Links and Resources
    `Website <https://sites.google.com/site/ornliceman/oclimax>`_. An introduction, examples, and installation can be found in this `presentation <https://neutrons.ornl.gov/sites/default/files/2018-NXS_Lecture_YQCheng_2.pdf>`_.

JScatter
```````````````````````````````

Overview
    “Jscatter is a python package that provides useful models for neutron 
    and X-ray scattering form factors, structure factors, and dynamic 
    models (quasi elastic neutron scattering) and other topics” (`JScatter Contributors <https://pypi.org/project/jscatter/>`_).

Useful Links and Resources
    The `website <https://pypi.org/project/jscatter/>`_ includes guides, documentation, examples, installation, and more.
