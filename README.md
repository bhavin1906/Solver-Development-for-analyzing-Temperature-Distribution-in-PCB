# Solver-Development-for-analyzing-Temperature-Distribution-in-PCB
Built a custom finite volume solver in MATLAB to model transient heat conduction in a multi-material PCB domain consisting of FR4 (anisotropic), copper conductor, and heat-generating resistor, incorporating realistic boundary and contact conditions 


Employed an explicit Euler scheme for time advancement, coupled with spatial discretization of anisotropic thermal conductivity — carefully chosen to balance computational cost and stability criteria via Fourier number-based Δt control 


Simulated 30 seconds of thermal evolution with over 30 million iterations, analyzing temperature distribution under varying heat generation rates and identifying glass transition threshold of FR4 (403K) for reliability prediction


Verified model integrity through grid and time independence studies (MSE-based), and validated adiabatic and convective boundary behavior by examining gradient-aligned temperature contours and edge dissipation paths


Captured key thermal transport behavior such as heat stagnation zones, contact resistance effects, and anisotropic lateral conduction, highlighting proficiency in physical modeling, solver implementation, and interpretation of thermal transport in electronics
