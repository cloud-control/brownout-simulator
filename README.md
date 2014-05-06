Brownout Replica Controller Simulator
=====================================

The aim of this simulator is allow quick testing of new brownout replica controller.
More information about brownout can be found in the following article:

> Cristian Klein, Martina Maggio, Karl-Erik Årzén, Francisco Hernández-Rodriguez,
> "Brownout: Building More Robust Cloud Applications", ICSE, 2014

A pre-print can be downloaded [here](http://www8.cs.umu.se/~cklein/publications/icse2014-preprint.pdf).

Abstract
--------

> Self-adaptation is a first class concern for cloud applications, which should be able to withstand diverse runtime changes. Variations are simultaneously happening both at the cloud infrastructure level - for example hardware failures - and at the user workload level - flash crowds. However, robustly withstanding extreme variability, requires costly hardware over-provisioning.
>
> In this paper, we introduce a self-adaptation programming paradigm called brownout. Using this paradigm, applications can be designed to robustly withstand unpredictable runtime variations, without over-provisioning. The paradigm is based on optional code that can be dynamically deactivated through decisions based on control theory.
>
> We modified two popular web application prototypes - RUBiS and RUBBoS - with less than 170 lines of code, to make them brownout-compliant. Experiments show that brownout self-adaptation dramatically improves the ability to withstand flash-crowds and hardware failures.

Usage
-----

To conduct the experiments, we used Ubuntu 12.04.2 LTS. Other software has been installed from the official repositories, specifically:

* Python
* Numpy

Installing this software on top of Ubuntu can be achieved using the following commands:

    sudo apt-get install python python-numpy

For questions or comments, please contact Cristian Klein <firstname.lastname@cs.umu.se>.
