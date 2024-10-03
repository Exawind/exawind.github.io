========================
 ExaWind Software Stack
========================

This website is in active development; further details are in the process of being added.

Open-source tools
-----------------

AMR-Wind:
`Repository <https://github.com/Exawind/amr-wind>`__ |
`Documentation <https://exawind.github.io/amr-wind>`__

.. collapse:: Description

    A massively parallel, block-structured adaptive-mesh, incompressible flow solver
    for wind turbine and wind farm simulations. The solver is built on top of the AMReX library.
    The primary applications for AMR-Wind are: performing large-eddy simulations (LES) of
    atmospheric boundary layer (ABL) flows, simulating wind farm turbine-wake interactions using
    actuator disk or actuator line models for turbines, and as a background solver when coupled
    with a near-body solver (e.g., Nalu-Wind) with overset methodology to perform blade-resolved
    simulations of multiple wind turbines within a wind farm. For offshore applications, the
    ability to model the air-sea interaction effects and its impact on the ABL characteristics is
    another focus for the code development effort.

|

Nalu-Wind:
`Repository <https://github.com/Exawind/nalu-wind>`__
`Documentation <https://exawind.github.io/nalu-wind>`__

ExaWind driver:
`Repository <https://github.com/Exawind/exawind-driver>`__

ExaWind benchmarks:
`Repository <https://github.com/Exawind/exawind-benchmarks>`__
`Website <https://exawind.github.io/exawind-benchmarks>`__

AMR-Wind frontend:
`Repository <https://github.com/Exawind/amr-wind-frontend>`__
`Documentation <https://github.com/Exawind/amr-wind-frontend/blob/main/docs/README.md>`__

ExaWind manager:
`Repository <https://github.com/Exawind/exawind-manager>`__