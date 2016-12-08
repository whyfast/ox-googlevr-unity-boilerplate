# ox-googlevr-unity-boilerplate

A boilerplate to quickly start making VR content in Unity for Android and iOS devices.

Included plugins:

* GoogleVR SDK for Unity v1.10.0, Dec 6 2016. Supports Android Cardboard, Android Daydream, and iOS Cardboard. https://github.com/googlevr/gvr-unity-sdk

## How to play

1. Install the latest versions of Unity and Android Studio.
2. Open the git repository as a project with Unity.
3. Open the default scene located in `Assets/Scenes/`.
4. Preview the scene using the Unity player (CTRL+P)
5. Go to `File->Build Settings` and switch the build platform to Android.
6. Inspect the `Player Settings` and fill in a custom `Company Name`, `Product Name` and `Bundle Identifier`.
7. Connect an Android device setup for use with GoogleVR as a USB Debugging device.
8. Build and run the project to `Build/demo.apk` and it should play on the connected Android device.
