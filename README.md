# Mars Induction Explorer

Unity Prototype for GeoPlasma development

This project is built using Unity ver 2020.3.17f1 - the full project can be downloaded here:

[Mars_Explorer_DTC_001](https://argos.vu/DTC_MARS/Mars_Explorer_DTC_OS_001.zip)

A PC/VR version (Developed on the Quest2) can be downloaded here:

[Mars_Explorer_DTC_EXE](https://argos.vu/DTC_MARS/Mars_Explorer_DTC_EXE.zip)

# MARS VR ASSEMBLY

![MARS VR ASSEMBLY](https://argos.vu/wp-content/uploads/2021/10/XR2.png)

The Root Transform for the Mars assembly is located on "MARS_ORIGIN" as shown above. The moons Phobos and Deimos are children of their "ROTA" transforms respectively. 

"MARS ROTATION BASE" is the root and rotationally controlled transform for the Mars surfaces.

"MARS GEO ZOOM CONTROL" is event processor base that handles user interactions with the planet and initiates all navigation from the "Planet View"
to the surface.

"UI AND SURFACE BUTTONS" contains the North Pole UI interactions as well as the animated Surface buttons which allow the user to travel between the "Planet View" and the surface.

"MAVEN AURORA" contains the auroral imagery composited from the MAVEN UV mission as presented at the DTC conference. 

# XR RIG

![XR_RIG](https://argos.vu/wp-content/uploads/2021/10/XR1.png)

The XR Rig can be located in the project hierarchy as shown above. Orientation and Position of the Rig is adjusted by the user

using the "A" button on the right controller.

(Spherical Harmonics Reference - [Spherical Harmonics](https://argos.vu/wp-content/uploads/2021/10/Chapter4_multipole.pdf))

![Spherical Harmonics img](https://argos.vu/wp-content/uploads/2021/07/Pou-768x476-1.png)

(Spherical Harmonics Reference - [Spherical Harmonics](https://argos.vu/wp-content/uploads/2021/10/Chapter4_multipole.pdf))

![Diocotron img](https://argos.vu/wp-content/uploads/2021/10/3-Figure3-1.png)


(Diocotron Instability Reference - [Diocotron Instability](https://www.plasma-universe.com/diocotron-instability/))

(Winston H. Bostick on Plasmoids - [Bostick on Plasmoids](https://becomingborealis.com/bostick-plasmoids/))
