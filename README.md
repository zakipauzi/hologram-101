# Origami App - Microsoft Academy 101

This app demonstrates core Windows Mixed Reality features on HoloLens including
gaze, gestures, voice input, spatial sound and spatial mapping. A 3D hologram of an origami
setup is placed in front of the user. The user will be able to interact with the model through
the following:

* Gaze: The cursor follows your gaze and lands on object for you to interact with it.
* Gesture: Do an air gesture on the floating balls to make it fall.
* Voice Input: You can also say "Drop Sphere" to make the balls drop. You can also say "Reset World"
to reset the model to original position.
* Spatial Sound: The background music comes from the object through spatial sound.
* Spatial Mapping: You can see the room mapped out in white triangles.


## Getting Started

### Prerequisites

* Unity 2017.3.1p4
* Microsoft Visual Studio 2017


## Building the Project

* Clone this repository into your local machine. This repository only contains "Assets" and "Project Settings"
* Open Unity, and load files as new project
* Open the Scene "Main"
* Go to File > Build settings
* Add Open Scenes into the Windows
* Select Universal Windows Platform on the left and click "Switch PLatform"
* Ensure "Unity C# Projects" is ticked
* Click on Build
* In the root folder, create a folder called "App" and build the solution there.


## Deployment

Deployment should be done from its solution file in App folder.

* After the build, open the solution in the App folder in Visual Studio
* Open the "hologram-101.sln in Visual Studio 2017
* Select "Release" and "x86" from the top bar

### Using HoloLens Emulator

Install the HoloLens Emulator before deploying the app. When installed, the emulator can
be executed from the drop-down list (default: Local Machine).

### Using HoloLens Device

Ensure HoloLens is connected to the same network as the machine that you are deploying from.
Under the debug settings for Remote Machine, key in the IP address of the HoloLens, which can
be found in the Settings of the HoloLens, under "Network & Internet > Advanced Settings".

If app has been deployed before, you can automatically launch the app from the HoloLens.


## Authors

* **Zaki Pauzi** - *Initial work* - [ZakiPauzi](https://github.com/zakipauzi)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
