# Design challenge
Challenge to interview for the computational engineering position at https://job-boards.greenhouse.io/czbiohubchicago/jobs/4545453005?gh_src=f5309c261us 

Given a target object (left panel) - in this case representing an in-vitro human tissue - with a defined geometry, we seek to develop a 2D tesselation (middle panel) which can wrap the target object with as little gaps as possible (right panel). This process represents inverse design of microfabricated devices which are typically created on flat 2D wafers and then assembled with tissues. The wrapping can occur spontaneously via internal strains, gravity, or external forces - any approach is acceptable. Open source solutions will be preferred. Please submit a summary figure of the computationally designed 2D-motif to csaba.forro@czbiohub.org

<p align="center">
  <img src="https://github.com/sciforro/challenge/blob/main/Tobj1.png" width="300" title="Target">
  <img src="https://github.com/sciforro/challenge/blob/main/Tobj2.png" width="300" title="2D object">
  <img src="https://github.com/sciforro/challenge/blob/main/Tobj3.png" width="300" title="Wrapping">
</p>

Scales:
- Diameter of tesselation : 1-5 centimeters
- Young Modulus range of tesselation material: 100 MPa - 2GPa
- Thickness of tesselation : under 50 microns

Some publications for inspiration:
- https://www.science.org/doi/10.1126/science.adf3824
- https://dl.acm.org/doi/pdf/10.1145/3197517.3201373
- https://dl.acm.org/doi/pdf/10.1145/3450626.3459789
- https://dl.acm.org/doi/10.1145/3528223.3530089
- https://dl.acm.org/doi/pdf/10.1145/3618396
