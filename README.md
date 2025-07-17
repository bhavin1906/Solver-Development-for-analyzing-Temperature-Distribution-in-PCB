# Solver-Development-for-analyzing-Temperature-Distribution-in-PCB
Built a custom finite volume solver in MATLAB to model transient heat conduction in a multi-material PCB domain consisting of FR4 (anisotropic), copper conductor, and heat-generating resistor, incorporating realistic boundary and contact conditions 


Employed an explicit Euler scheme for time advancement, coupled with spatial discretization of anisotropic thermal conductivity — carefully chosen to balance computational cost and stability criteria via Fourier number-based Δt control  
