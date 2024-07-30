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

.. csv-table:: Configuration options
   :header-rows: 1

    Name, Description, Useful Links and Resources
    ``jupyter_execute_default_kernel``,"The default kernel to launch when executing code in ``jupyter-execute`` directives. Default to ``python3``."
    ``render_priority_html``,"The priority of different output mimetypes for displaying in HTML output. Mimetypes earlier in the data priority list are preferred over later ones. This is relevant if a code cell produces an output that has several possible representations (e.g. description text or an image). Please open an issue if you find a mimetype that isn't supported, but should be. Default to ``['application/vnd.jupyter.widget-view+json', 'text/html', 'image/svg+xml', 'image/png', 'image/jpeg', 'text/latex', 'text/plain']``."
    ``render_priority_latex``,"Same as ``render_priority_html``, but for latex. The default is ``['image/svg+xml', 'image/png', 'image/jpeg', 'text/latex', 'text/plain']``."
    ``jupyter_execute_kwargs``,"Keyword arguments to pass to ``nbconvert.preprocessors.execute.executenb``, which controls how code cells are executed. The default is ``{'timeout':-1, 'allow_errors': True)``."
    ``jupyter_sphinx_linenos``,"Whether to show line numbering in all ``jupyter-execute`` sources."
    ``jupyter_sphinx_continue_linenos``,"Whether to continue line numbering from previous cell in all ``jupyter-execute`` sources."

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

Data Analysis Software
-----------------------------------

Refl1D
```````````````````````````````
Overview
```````````````````````````````
“Refl1D is a program for analyzing 1D reflectometry
measurements made with X-ray and neutron beamlines. The
1-D models give the depth profile for material scattering
density composed of a mixture of flat and continuously
varying freeform layers. With polarized neutron
measurements, scientists can study the sub-surface structure
of magnetic samples. The architecture supports the addition
of specialized layer types such as models for the density
distribution of polymer brushes, and volume space modeling
for proteins in bio-membranes” (`Refl1D Contributors <https://github.com/reflectometry/refl1d>`_).



Useful Links and Resources
```````````````````````````````
* `Github <https://github.com/reflectometry/refl1d>`_
* `Documentation <https://refl1d.readthedocs.io/en/latest/>`_ includes getting started, tutorials, user guide, and documentation.

GenX
```````````````````````````````
Overview
```````````````````````````````
“GenX is a versatile program using the differential evolution
algorithm for fitting, primarily, X-ray and neutron reflectivity
data, lately also surface x-ray diffraction data” (`GenX Contributors <https://aglavic.github.io/genx/>`_).

Useful Links and Resources
```````````````````````````````
The GenX `website <https://aglavic.github.io/genx/>`_ includes source code, downloads, publications, how to, and more.

refnx
```````````````````````````````
Overview
```````````````````````````````
“refnx is a flexible, powerful, Python package for generalised
curvefitting analysis, specifically neutron and X-ray
reflectometry data" (`Refnx Contributors <https://refnx.readthedocs.io/en/latest/>`_).

Useful Links and Resources
```````````````````````````````
The `refnx website <https://refnx.readthedocs.io/en/latest/>`_ includes installation, getting started, examples, API reference, and source code.

