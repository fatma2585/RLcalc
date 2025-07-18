# RLcalcu  (Radio Loudness Calculator)
[![Made with NumPy](https://img.shields.io/badge/Made%20with-NumPy-blue.svg)](https://numpy.org/)
[![PyPI version](https://badge.fury.io/py/bhml.svg)](https://pypi.org/project/bhml/)
[![image](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![image alt](https://github.com/fatma2585/RLcalc/blob/main/CygA-Color_lo.jpg)


## Introduction

This package used to calcualte the Radio Loudness paramater of galaxies or Quasars, whcih is the radio between the radio flux to optical flux.


## Motivation
We created htis package to add the radio contribution to the galalxies or qausars study in a comrehensive manner, So that it is user friendly even with no previous experience in radio astronomy. The package makes units conversion also the conversion from 20cm band to 6cm band assuming a specific radio spectral slope. In radio astronomy, it is conventional that this slope = - 0.5 for qusars, based on many servay studies e.g DR7 Qusars calalog of 107,000 sample shows a great consistancy with this slope.
However, we keep it as a free paramter so the user could adjusted based on their studies.




## Installation

The package is installable on Python 3.x and can be installed using:

```pip install RLcalcu```

# How to cite



## Use Example and Description of Function


```
# To calculate the Radio Loudness paramater:

from RL_calcu import RLoud
R = RLoud(Z,R20CM,L2500,R_slope=-0.5)


# To calculate the Radio Lumionsity:

from RL_calcu import RLum
Lum = RLum(Z,R20CM,R_slope=-0.5)

```
