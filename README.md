# AR Gym Card Project

Welcome to the AR Gym Card Project! This project uses Unity to create an augmented reality (AR) experience for gym cards, allowing users to view and interact with digital gym cards using their mobile devices.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Unity Hub installed.
- Unity Editor version 2020.3 or later installed.
- Android or iOS device for testing.
- AR Foundation, ARCore XR Plugin (for Android), ARKit XR Plugin (for iOS), and Vuforia Engine installed from Unity Package Manager.

## Getting Started

### Cloning the Repository

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/ayushanand2003/ARGYMCARD

### Opening the Project

1. Open Unity Hub.
2. Click on the "Add" button.
3. Navigate to the cloned repository folder and select it.
4. Click "Select Folder" to add the project to Unity Hub.
5. Click on the project to open it in Unity Editor.

### Setting Up the Project

1. Open the Unity project and go to `File > Build Settings`.
2. Select your target platform (Android or iOS).
3. Click on "Switch Platform" to switch to the desired platform.

### Importing AR Foundation and Plugins

1. Open the Package Manager (`Window > Package Manager`).
2. Search for "AR Foundation" and click "Install".
3. For Android:
    - Search for "ARCore XR Plugin" and click "Install".
4. For iOS:
    - Search for "ARKit XR Plugin" and click "Install".

### Importing Vuforia Engine

1. Open the Package Manager (`Window > Package Manager`).
2. Click on the "+" button at the top left and select "Add package from git URL".
3. Enter the following URL: `https://github.com/Unity-Technologies/com.unity.xr.vuforia.git`
4. Click "Add" to install the Vuforia Engine.

### Configuring AR and Vuforia Settings

1. Go to `Edit > Project Settings`.
2. Select "XR Plug-in Management".
3. For Android:
    - Check "ARCore" under the Android tab.
4. For iOS:
    - Check "ARKit" under the iOS tab.
5. Go to `Window > Vuforia Configuration`.
6. Enter your Vuforia license key (you can get it from the [Vuforia Developer Portal](https://developer.vuforia.com/)).

### Building the Project

1. Open the Build Settings (`File > Build Settings`).
2. Add your main scene to the "Scenes in Build" by clicking "Add Open Scenes".
3. Connect your mobile device to your computer.
4. For Android:
    - Select your connected device from the "Run Device" dropdown.
    - Click on "Build and Run".
5. For iOS:
    - Open Xcode and connect your iOS device.
    - Click on "Build".
    - Follow the instructions to deploy the app to your device via Xcode.

### Running the Project

1. After the build is complete, the app will launch on your mobile device.
2. Point your device’s camera at the gym card markers to see the AR content.
3. Interact with the AR elements as needed.

## Troubleshooting

- **Build Errors**: Ensure all required packages are installed and the correct platform is selected in the Build Settings.
- **AR Not Working**: Make sure the AR Foundation, respective AR plugins (ARCore/ARKit), and Vuforia Engine are properly configured in the Project Settings.
- **Deployment Issues**: Ensure your device is connected properly and you have the necessary drivers installed.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

For any questions or issues, please contact [ayushanand141@gmail.com].

---

Thank you for using the AR Gym Card Project! Enjoy creating amazing AR experiences.
