Introduction
==================================

.. _introduction:

What is data reduction?
-----------------------------------

The overall purpose of Data Reduction is to remove instrument-specific artifacts. 
Another definition is “the transformation of a dataset collected from an instrument 
into a dataset in physical units” `[1]`_. A way to think about raw data and reduced 
data is that “raw data is instrument-specific (requires knowledge of detector geometry, 
motor positions, etc.)” while “reduced data is proportional to the neutron scattering 
cross-section from the sample expressed in terms of physically meaningful variables 
(e.g., momentum transfer, energy)” [5]. For spectroscopy, although the format and 
organization of spectroscopy data are generally dependent on the instrument, 
“the goal of reduction is to produce a quantity (the double differential scattering 
cross section) which is (almost) independent of the instrument [6]. Other considerations 
that are made are the “sample itself and on the strength of the interactions between 
the neutrons and the sample’s constituent elements” [6].

.. _[1]: http://sphinx-doc.org

Definitions of Data Reduction are also defined by each instrument category at ORNL below:

Direct Geometry (CNCS, HYSPEC, SEQUOIA, ARCS)
```````````````````````````````
Data Reduction Definition
    “For direct geometry spectrometers and BASIS, data reduction transforms collected data 
    from time-of-flight events into S(Q,ω)… The four direct geometry spectrometers use Mantid 
    to perform mostly automatic reduction to S(detector,ω) – the transformation to S(Q,ω) is 
    performed manually in either MSlice, Horace, or Mantid. ” [7]

Triple-Axis (CTAX, PTAX, TAX, & VERITAS)
```````````````````````````````
Data Reduction Definition
    “For the triple-axis spectrometers, the data collected is already in the appropriate S(Q,ω) 
    form assuming counts were collected to a fixed incident beam monitor and only small, simple 
    corrections are required (like accounting for higher order contamination in the beam monitor).” [7]

Chemical Spectroscopy (VISION, BASIS)
```````````````````````````````
Data Reduction Definition
    “For VISION, the double-focusing analyzers integrate the intensity over a range of scattering angle 
    (or Q), thus the product of reduction is S(ω)… The automatic reduction at BASIS uses Mantid to directly 
    obtain S(Q,ω) with default Q and energy binning. At VISION, two S(ω) spectra corresponding to the 
    backscattering banks (120-150 degree) and forward scattering banks (30-60 degree) are automatically 
    produced with Mantid.” [7]

Spin Echo (NSE)
```````````````````````````````
Data Reduction Definition
    “DrSPINE (Data Reduction for SPIN Echo experiments) enables the reduction of neutron spin 
    echo data produced at both reactor and pulsed neutron sources.” [7]

