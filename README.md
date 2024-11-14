# AR App Development Showcase

This project showcases the development of an AR application using the Unity Engine version 6. It serves as a comprehensive guide for building AR experiences, demonstrating key features such as face tracking, image tracking, and plane detection. Whether you're targeting iOS or Android platforms, this project provides step-by-step instructions and essential dependencies to get you started on your AR development journey.

## Dependencies

This project relies on the following dependencies:

- **Unity AR Foundation**: Provides a framework for building AR applications.
- **ARKit XR Plugin**: Required for AR functionality on iOS devices.
- **ARCore XR Plugin**: Required for AR functionality on Android devices.
- **XR Plug-in Management**: Manages the loading of XR plugins and provides a unified interface for configuring and managing XR settings across different platforms.
- **XR Simulation Environments**: Allows testing and development of AR applications within a simulated environment, reducing the need for physical devices during the initial stages of development.

## Scenes Overview

This project includes the following scenes, each demonstrating a specific AR feature:

### 1. Face Tracking Scene
- **Description**: This scene utilizes the front camera to detect and track facial features.
- **How it works**: When the app is launched, the AR Foundation framework processes the camera feed to identify and track facial landmarks. A green mask is then overlaid on the detected face to visualize the tracking.

### 2. Image Tracking Scene
- **Description**: This scene demonstrates the ability to recognize and track 2D images in the environment.
- **How it works**: The AR Foundation framework scans the environment for predefined images. Once an image is detected, the app overlays digital content on top of it, maintaining alignment as the image moves or the camera perspective changes.

### 3. Plane Detection Scene
- **Description**: This scene showcases the detection and tracking of horizontal and vertical planes in the environment.
- **How it works**: The AR Foundation framework analyzes the camera feed to identify flat surfaces. Detected planes are visualized with a grid pattern, allowing users to place virtual objects on these surfaces.

Each scene is designed to be a standalone demonstration of a specific AR capability, providing a clear and focused example of how to implement these features in your own AR projects.


## Instructions for iOS Platform

1.Open the project in Unity version 6.0.

2.Navigate to "File" > "Build Settings."

3.Select the "iOS" platform.

4.Click the "Player Settings" button.

5.Under "Other Settings," change the "Bundle Identifier" to your desired app name.

6.Exit the "Project Settings" window.

7.Click the "Build And Run" button.

8.Xcode might prompt you to log in with your Apple Developer account for physical device deployment. Follow the guide at https://developer.apple.com/help/account/get-started/sign-in-to-your-developer-account/ to log in and install the necessary certificates.

9.Enable "Automatically manage signing" and ensure the correct team name is selected for app signing. Refer to https://developer.apple.com/documentation/xcode/adding-capabilities-to-your-app/ for more details.

10.Choose your target iPhone (physical device) from the available options.

11.Run the app.

## Instructions for Android Platform

1. Enable developer mode on your Phone then connect to your laptop or pc

2. You should see the device by running `adb devices` on the terminal window.

3. Open project with Unity.

4. Navigate to "File" > "Build Settings."

5. Press on "Build and run" button to run the app on your phone

Notes: Do not enable Occulus provider in `XR Plug-in Management` because the android phone doesn't support.

## Official Unity Documentation and Course

For further learning and detailed documentation, refer to the following resources:

- **Unity AR Foundation Documentation**: [Unity AR Foundation Documentation](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@latest)
- **Unity Learn - AR Development Pathway**: [Unity Learn AR Development Pathway](https://learn.unity.com/pathway/mobile-ar-development)


These resources provide comprehensive guides, tutorials, and best practices for developing AR applications using Unity.

