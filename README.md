# motorAcs
EPICS motor drivers for the following [Advanced Control Systems Corporation](http://www.acsmotion.com) controllers: MCB-4B

[![Build Status](https://github.com/epics-motor/motorAcs/actions/workflows/ci-scripts-build.yml/badge.svg)](https://github.com/epics-motor/motorAcs/actions/workflows/ci-scripts-build.yml)
<!--[![Build Status](https://travis-ci.org/epics-motor/motorAcs.png)](https://travis-ci.org/epics-motor/motorAcs)-->

motorAcs is a submodule of [motor](https://github.com/epics-modules/motor).  When motorAcs is built in the ``motor/modules`` directory, no manual configuration is needed.

motorAcs can also be built outside of motor by copying it's ``EXAMPLE_RELEASE.local`` file to ``RELEASE.local`` and defining the paths to ``MOTOR`` and itself.

motorAcs contains an example IOC that is built if ``CONFIG_SITE.local`` sets ``BUILD_IOCS = YES``.  The example IOC can be built outside of driver module.
