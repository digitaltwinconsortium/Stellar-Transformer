# Mars Induction Explorer
Open-Source Virtual Reality Initiative 'Mars Induction Explorer' is the first composite Digital Twin component of the larger Stellar Transformer project with plans to map Digital Twins of our entire solar system capturing long wavelength electromagnetic solar induction effects on all the planets.

Unity Prototype for GeoPlasma development

This project is built using Unity ver 2020.3.17f1 - the full project can be downloaded here:

[Mars_Explorer_DTC_001](https://argos.vu/DTC_MARS/Mars_Explorer_DTC_OS_001.zip)

A PC/VR version (Developed on the Quest2) can be downloaded here:

[Mars_Explorer_DTC_EXE](https://argos.vu/DTC_MARS/Mars_Explorer_DTC_EXE.zip)

[![DTC_VID_IMG](https://argos.vu/wp-content/uploads/2021/10/DTC_VIDEOS.png)](https://youtu.be/fS4WjpeI61U)

([Presentation at Digital Twin Consortium Q3 - Presentation Video](https://youtu.be/fS4WjpeI61U))

[![DTC_CONF_IMG](https://argos.vu/wp-content/uploads/2021/10/DTC_SMALL.png)](https://www.digitaltwinconsortium.org/member-meeting-q3/index.htm)

([Conference Highlights and Participants can be viewed here - Digital Twin Conference Q3](https://www.digitaltwinconsortium.org/member-meeting-q3/index.htm))

# MARS VR ASSEMBLY

![MARS VR ASSEMBLY](https://argos.vu/wp-content/uploads/2021/10/XR2.png)

The Root Transform for the Mars assembly is located on "MARS_ORIGIN" as shown above. The moons Phobos and Deimos are children of their "ROTA" transforms respectively. 

"MARS ROTATION BASE" is the root and rotationally controlled transform for the Mars surfaces.

"MARS GEO ZOOM CONTROL" is the event processor base that handles user interactions with the planet and initiates all navigation from the "Planet View"
to the surface.

"UI AND SURFACE BUTTONS" contains the North Pole UI interactions as well as the animated Surface buttons which allow the user to travel between the "Planet View" and the surface.

"MAVEN AURORA" contains the auroral imagery composited from the MAVEN UV mission as presented at the DTC conference. 

# XR RIG

![XR_RIG](https://argos.vu/wp-content/uploads/2021/10/XR1.png)

The XR Rig can be located in the project hierarchy as shown above. Orientation and Position of the Rig is adjusted by the user

using the "A" button on the right controller.

[![Spherical Harmonics img](https://argos.vu/wp-content/uploads/2021/07/Pou-768x476-1.png)](https://argos.vu/wp-content/uploads/2021/10/Chapter4_multipole.pdf)

(Spherical Harmonics Reference - [Spherical Harmonics](https://argos.vu/wp-content/uploads/2021/10/Chapter4_multipole.pdf))

[![Octahedral img](https://argos.vu/wp-content/uploads/2021/10/Octahedral_2.png)](https://argos.vu/wp-content/uploads/2021/10/Octahedral_Harmonics.pdf))

(Octahedral Symetries - [On spherical harmonics possessing octahedral symmetry](https://argos.vu/wp-content/uploads/2021/10/Octahedral_Harmonics.pdf))

[![Diocotron img](https://argos.vu/wp-content/uploads/2021/10/3-Figure3-1.png)](https://www.plasma-universe.com/diocotron-instability/)

(Diocotron Instability Reference - [Diocotron Instability](https://www.plasma-universe.com/diocotron-instability/))

(Winston H. Bostick on Plasmoids - [Bostick on Plasmoids](https://becomingborealis.com/bostick-plasmoids/))
