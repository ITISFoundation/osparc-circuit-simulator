# Quite Universal Circuit Simulator with SPICE

[![Qucs-S Docs](https://img.shields.io/badge/docs-Qucs--S-blue?logo=readthedocs&style=flat)](https://qucs-s-help.readthedocs.io/en/latest/)
[![Ngspice Docs](https://img.shields.io/badge/docs-Ngspice-blue?logo=readthedocs&style=flat)](https://ngspice.sourceforge.io/docs.html)
[![QucsatorRF Docs](https://img.shields.io/badge/docs-QucsatorRF-blue?logo=readthedocs&style=flat)](https://github.com/ra3xdh/qucsator_rf#readme)

![](assets/qucs-header.png)


| Simulator/Service | Docs     | License    | 
| ----------------- | ------------------ | -------- |
| Qucs-S            | [![Qucs-S docs](https://img.shields.io/badge/docs-Qucs--S-blue?logo=readthedocs&style=flat)](https://qucs-s-help.readthedocs.io/en/latest/) | [![Qucs-S: GPL v2](https://img.shields.io/badge/Qucs--S-GPLv2-blue.svg)](https://github.com/ra3xdh/qucs_s/blob/master/COPYING)                     |
| Ngspice           | [![Ngspice](https://img.shields.io/badge/sim-ngspice-orange?logo=ngspice&style=flat)](https://ngspice.sourceforge.io/)                      | [![Ngspice: BSD-3-Clause](https://img.shields.io/badge/Ngspice-BSD%203--Clause-green.svg)](https://github.com/ngspice/ngspice/blob/master/COPYING) |
| QucsatorRF        | [![QucsatorRF](https://img.shields.io/badge/sim-qucsatorRF-yellow?logo=qucs&style=flat)](https://github.com/ra3xdh/qucsator_rf)             | [![Qucsator-RF: GPL v2](https://img.shields.io/badge/Qucsator--RF-GPLv2-red.svg)](https://github.com/ra3xdh/qucsator_rf/blob/master/COPYING)       |
| XYCE              | [![XYCE](https://img.shields.io/badge/sim-xyce-red?logo=xyce&style=flat)](https://xyce.sandia.gov/)                                         |                                                                                                                                                    |
| SpiceOpus         | [![SpiceOpus](https://img.shields.io/badge/sim-spiceopus-purple?logo=spice&style=flat)](http://spiceopus.si/)                               |                                                                                                                                                    |

|Services         |                              |
| ------------------- | ------------- |
| Docker Registry Web | [![Docker Registry Web](https://img.shields.io/badge/registry-osparc--services--circuit--simulator--web-green?logo=docker&style=flat)](https://registry.speag.com/harbor/projects/6/repositories/osparc-services-circuit-simulator%2Fmain%2Fcircuit-simulator-web) |  |
| Docker Registry App | [![Docker Registry App](https://img.shields.io/badge/registry-osparc--services--circuit--simulator--app-blue?logo=docker&style=flat)](https://registry.speag.com/harbor/projects/6/repositories/osparc-services-circuit-simulator%2Fmain%2Fcircuit-simulator-app)  |  |



**Quite Universal Circuit Simulator with SPICE** ([Qucs-S]), is an *open-source* circuit simulation frontend based on [Qucs](https://qucs.github.io/) with added [SPICE](https://en.wikipedia.org/wiki/SPICE) support. It provides a Qt6 GUI and is shipped with the following **simulation kernels**:

* [Ngspice](https://ngspice.sourceforge.io/): mixed-signal simulator, compatible with most industrial SPICE models, with strong performance and postprocessing tools.
* [QucsatorRF](https://github.com/ra3xdh/qucsator_rf): RF and microwave circuit simulator with models for microstrip lines and waveguides (not SPICE-compatible; limited for general-purpose use).


[Qucs-S]: https://ra3xdh.github.io/
[Qucs]: https://qucs.github.io/
