# FurnitureTryOut

An Android application that allows users to visualize and try out furniture in their space using augmented reality (AR) technology.

## 🏠 About

FurnitureTryOut is a modern Android application built with Kotlin that helps users visualize how furniture would look in their home before making a purchase. The app leverages AR technology to overlay 3D furniture models onto real-world environments through the device's camera.

## ✨ Features

- **Augmented Reality Furniture Placement**: View furniture in your real space using AR
- **3D Furniture Models**: High-quality 3D models of various furniture pieces
- **Real-time Visualization**: See how furniture fits and looks in your room instantly
- **Interactive Controls**: Rotate, scale, and position furniture models
- **Furniture Catalog**: Browse through a collection of furniture items
- **Save & Share**: Capture screenshots of your AR setup to save or share
- **Material Design**: Modern UI following Material Design guidelines

## 🛠️ Tech Stack

- **Language**: Kotlin
- **Platform**: Android
- **AR Framework**: ARCore (Google's AR platform)
- **3D Rendering**: Sceneform or Filament
- **Architecture**: MVVM (Model-View-ViewModel)
- **UI**: Material Design Components
- **Camera**: CameraX or Camera2 API

## 📱 Screenshots

*Add screenshots of your app here showing:*
- AR furniture placement
- Furniture catalog
- Settings screen
- etc.

## 🚀 Getting Started

### Prerequisites

- Android Studio Arctic Fox or later
- Android device with ARCore support
- Minimum SDK: Android 7.0 (API level 24)
- Target SDK: Android 13 (API level 33)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/KartikBhargava/FurnitureTryOut.git
```

2. Open the project in Android Studio

3. Sync the project with Gradle files

4. Build and run the app on an ARCore-supported device

### ARCore Requirements

Make sure your device supports ARCore. You can check the list of supported devices [here](https://developers.google.com/ar/devices).

## 🏗️ Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/kartik/furnituretryout/
│   │   │   ├── ui/
│   │   │   │   ├── ar/          # AR-related activities and fragments
│   │   │   │   ├── catalog/     # Furniture catalog screens
│   │   │   │   └── main/        # Main activity and navigation
│   │   │   ├── model/           # Data models
│   │   │   ├── repository/      # Data repository classes
│   │   │   ├── viewmodel/       # ViewModel classes
│   │   │   └── utils/           # Utility classes
│   │   ├── res/
│   │   │   ├── layout/          # XML layout files
│   │   │   ├── drawable/        # Images and vector drawables
│   │   │   ├── values/          # Colors, strings, dimensions
│   │   │   └── raw/             # 3D model files (.sfb, .glb)
│   │   └── AndroidManifest.xml
│   └── androidTest/             # Instrumented tests
└── build.gradle                 # App-level Gradle file
```

## 🎯 How to Use

1. **Launch the App**: Open FurnitureTryOut on your ARCore-supported device
2. **Grant Permissions**: Allow camera permissions for AR functionality
3. **Scan Environment**: Point your camera at a flat surface (floor, table, etc.)
4. **Select Furniture**: Choose a furniture item from the catalog
5. **Place & Adjust**: Tap to place the furniture and use gestures to:
   - Move: Drag to reposition
   - Rotate: Twist with two fingers
   - Scale: Pinch to resize
6. **Capture**: Take screenshots to save your AR setup

## 🔧 Configuration

### Adding New Furniture Models

1. Place 3D model files (.sfb or .glb format) in `app/src/main/res/raw/`
2. Add model metadata to the furniture catalog
3. Update the model loading logic in the AR module

### Customizing AR Settings

Modify AR parameters in the configuration files:
- Lighting estimation
- Plane detection sensitivity
- Tracking quality thresholds

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Kartik Bhargava**
- GitHub: [@KartikBhargava](https://github.com/KartikBhargava)
- Portfolio: [kartikbhargava.github.io](https://kartikbhargava.github.io)
- Email: officialkartik07@gmail.com

## 🙏 Acknowledgments

- Google ARCore team for the AR framework
- Material Design team for UI components
- 3D model creators for furniture assets
- Android development community for inspiration

## 📚 Resources

- [ARCore Documentation](https://developers.google.com/ar)
- [Sceneform Documentation](https://developers.google.com/sceneform)
- [Material Design Guidelines](https://material.io/design)
- [Kotlin Documentation](https://kotlinlang.org/docs/)

## 🐛 Known Issues

- Performance may vary on older devices
- Some furniture models might take time to load
- AR tracking quality depends on lighting conditions

## 🔮 Future Enhancements

- [ ] Cloud-based furniture catalog
- [ ] Social sharing features
- [ ] Measurement tools
- [ ] Lighting simulation
- [ ] Multiple furniture placement
- [ ] Room scanning and mapping
- [ ] Price comparison integration

---

*Made with ❤️ by Kartik Bhargava*
