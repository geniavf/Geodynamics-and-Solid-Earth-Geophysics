**1. Modelling Elastic Thickness of a Subducting Plate**

For this part of the code, the chosen study area is the Kuril-Kamchatka Trench.
This study area offers complex geological phenomenon, because when the bending-induced stress exceeds the lithosphere's yield strength, it becomes an important factor for penetration of faulting trenchward of the outer-rise region.
For this practical, the description of the flexure of a broken plate that estimates the bending plate profile is defined by the bathymetry data from the Kuril-Kamchatka subduction zone trench.
The seafloor bathymetry is obtained from GEBCO.

Lastly, the practical study intends to explore correlations between axial trench relief, axial trench width, and effective elastic plate thickness. 

Assumptions are made to build the model:
a. Lithospheric plate is not infinite; it subsides with age and distance from the ridge axis.
b. Vertical and horizontal loads are applied at the rigin overlying a fluid quarter space.

Equations used:
Flexural rigidity (D):
![image](https://github.com/geniavf/Geodynamics-and-Solid-Earth-Geophysics/assets/159028891/9a73b52d-3c3e-4d76-99ba-d8104b9131e8)

Flexural Parameter (𝛼𝛼):
![image](https://github.com/geniavf/Geodynamics-and-Solid-Earth-Geophysics/assets/159028891/068681c0-7c2f-491d-b1ec-08fc1809e3c9)

Bending of the lithosphere at an ocean trench due to an applied vertical load and bending moment (Stevens, 2023). 
𝑥b is the shallowest point along the bending profile; 𝑥0 is the location where vertical deformation w=0 (Zhang et al., 2019).
![image](https://github.com/geniavf/Geodynamics-and-Solid-Earth-Geophysics/assets/159028891/d3076071-eb6d-4812-ae98-5bfb3d1e4b0e)

Elastic Flexure Model:
![image](https://github.com/geniavf/Geodynamics-and-Solid-Earth-Geophysics/assets/159028891/90ffb1a1-b2ba-4c35-a232-27e924173005)

Plate Elastic Thickness (h):
![image](https://github.com/geniavf/Geodynamics-and-Solid-Earth-Geophysics/assets/159028891/0d0c6cc3-79ff-407d-9a19-9560780921d0)

