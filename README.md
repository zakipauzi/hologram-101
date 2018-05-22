# Origami App

This app demonstrates core Windows Mixed Reality features on HoloLens including
gaze, gestures, voice input, spatial sound and spatial mapping.

## Getting Started

Clone the repository into your local machine.
For deployment, go to App folder and open Origami.sln in Visual Studio.

### Prerequisites

For editing purposes: Unity 2017.3.1p4, Microsoft Visual Studio 2017
For deployment purposes: Microsoft Visual Studio 2017

## Deployment

Deployment should be done from its solution file in App folder. Select "Release" and
"x86" from the top bar.

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
