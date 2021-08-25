# AR-3DObjectInteraction-2020.1
 AR app to RePosition, ReScale and Rotate a 3D object

# Augmented Reality Challenge
- Create an AR-App using AR Foundation with any 3D model that can be placed without tracking marker
(like QR code) on automatically detected surfaces in real life.
- Add functionality for re-positioning, scaling, and rotating the 3D model.
- Include ambient light and reflections from the smartphone camera that influences the reflections and
color of the material of the virtual 3D object in a realistic way.

# Overview
This is an AR app that can be tested on Android devices but is also ready to be deployed to iOS devices.
I created the capability to Instantiate a 3D object in a real environment.
It might be:
RePositioned (With tap+hold) on a different position of the real environment. 
Rotated (tap+hold on the model and rotate over the axis).
ReScaled (with pinch in/out).
The app also receives the environment light and makes reflections that influence the reflections and color of the material of the 3D object in a realistic way. 

# Project Timeline

The entire project tooks around 12hs split in 4 days. All process went through:
# Research & Investigation
Looking for information and latest updates related to Unity AR foundation.
# Project Setup
For this attempt I use Unity 2020.1 in addition to AR Foundation 3.1.16 ARCore 3.1.18 and ARKit 3.1.18
As a rough test this project could be also iterated over Unity 2019.2 version.
# First Prototype
As a starting point my goal was to instantiate an object with a markerless approach and iterate over.
ARPlacement script.
# Second Prototype
As an iteration I add the capability to rePosition, Rotate and ReScale the 3D object, using Lean Touch from Asset Store.
LeanDragTranslate, LeanPinshScale and LeanTwistRotateAxis attached to the 3D model.
# Third Prototype
Once I had the capability to instantie the 3D model and interact with his transform component. I added an Environment Probe Manager to the AR Session Origin in addition to influencing the reflections and color of the 3D object in a realistic way.
