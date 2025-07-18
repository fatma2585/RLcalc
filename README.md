# RLcalcu  (Radio Loudness Calculator)
[![Made with NumPy](https://img.shields.io/badge/Made%20with-NumPy-blue.svg)](https://numpy.org/)
[![PyPI version](https://badge.fury.io/py/bhml.svg)](https://pypi.org/project/bhml/)
[![image](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![image alt](https://github.com/fatma2585/RLcalc/blob/main/CygA-Color_lo.jpg)


## Introduction

This package is used to calculate the Radio Loudness parameter and radio luminosity in different reference frames for the radio fluxes of quasars. The radio loudness parameter is defined as the ratio between the radio flux and optical flux [R = (f_6cm/f_2500A)].


## Motivation
We created this package to add the radio contribution to the galaxies or quasars study in a comprehensive manner, so that it is user-friendly even with no previous experience in radio astronomy. The package makes unit conversion, as well as the conversion from 20cm band to 6cm band, assuming a specific radio spectral slope. In radio astronomy, it is conventional that this slope = - 0.5 for quasars, based on many servay studies, e.g, the DR7 Quasars catalog of 107,000 samples shows a great consistency with this slope.
However, we keep it as a free parameter so the user can adjust based on their studies.




## Installation

The package is installable on Python 3.x and can be installed using:

```pip install RLcalcu```

# How to cite



## Use Example and Description of Function


```
# To calculate the Radio Loudness paramater:

from RLcalc import RLoud
R = RLoud(Z,R20CM,L2500,R_slope=-0.5)


# To calculate the Radio Lumionsity:

from RLcalc import RLum
Lum = RLum(Z,R20CM,R_slope=-0.5)

```
