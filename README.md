# artificial-rotors

Artificial force rotations for fast sampling of the rotational energy profiles of molecular systems by structure optimization and molecular dynamics. Based on Atomic Simulation Environment.

# How it works

To enhance sampling of the rare rotational events in molecular systems a slight artificial force is applied to the atoms to sample the rotational degrees of freedom of components in molecules.

<img src="https://github.com/chem-gp/artificial-rotors/assets/25351170/d8a43168-63fa-4c1a-8c7a-f1a96fc2a4cf" alt="drawing" width="50%"/>


# Showcase

Below we illustrate the use case of `artificial-rotors` on example of a molecular crystal system (see the [publication](https://pubs.acs.org/doi/full/10.1021/jacs.3c08909)).

PBE functional, BFGS optimization with artificial force applied to the carbons of the rings:

https://github.com/chem-gp/artificial-rotors/assets/25351170/54ea7561-01d8-46c9-8c9f-a269a47571e6

Reference:

Jin, M., Kitsu, R., Hammyo, N., Sato-Tomita, A., Mizuno, M., Mikherdov, A.S., Tsitsvero, M., Lyalin, A., Taketsugu, T. and Ito, H., 2023. A Steric-Repulsion-Driven Clutch Stack of Triaryltriazines: Correlated Molecular Rotations and a Thermoresponsive Gearshift in the Crystalline Solid. Journal of the American Chemical Society, 145(50), pp.27512-27520.

https://pubs.acs.org/doi/full/10.1021/jacs.3c08909
