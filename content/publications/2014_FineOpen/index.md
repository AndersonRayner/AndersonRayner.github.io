---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Modelling Propellers in FINE/Open using OpenLabs"
authors: 
- Matthew Anderson
- KC Wong
- Patrick Hendrick
date: 2014-01-01

publication_types: 
  - paper-conference

publication: "Fourth Australasian Unmanned Systems Conference"

tags:
- uas
- cfd

featured: false

image:
  caption: ""
  focal_point: "smart"
  preview_only: false

projects:
- cfd

---

With the prolific rise of unmanned aerial vehices (UAVs), interest is increasingly growing in optimising airframes to improve flight characterisitcs. Tools such as computational fluid dynamics (CFD) can be used to optimise the shape of UAV frames by giving a detailed understanding of how the flow interacts with the vehicle. The effects of the frame on the propellers (and vice versa) can be a dominant flow feature, especially for multirotors, however fully modelling propellers in CFD is a very involved task requiring intensive computational power.

Actuator and blade element disks provide a simple way of modelling the effects of a propeller in CFD by artificially applying a force into the domain, emulating the time-averaged effect of the propeller to reduce the computational requirements.

This paper presents an actuator disk model with three different loading profiles and a blade element disk model with two methods of calculating the thrust and the torque of the propeller. These models are implemented in FINE/Open using OpenLabs. The effect of using the differing models is shown, with results matching well with other implementations presented in literature.
