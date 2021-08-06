<h1 align=center>
  <a href=https://flutter.dev>
    ⇱
  </a>
  Flutter
</h1>

## [⇱](https://flutter.dev/docs/get-started/install) Install 
- [⇱](https://flutter.dev/docs/get-started/install/windows) Windows [⇲](#windows)
- [⇱](https://flutter.dev/docs/get-started/install/macos) macOS [⇲](#macos)
- [⇱](https://flutter.dev/docs/get-started/install/linux) Linux [⇲](#linux)
- [⇱](https://flutter.dev/docs/get-started/install/linux) Chrome OS [⇲](#chromeos)
- [⇱](https://flutter.dev/docs/get-started/web) Web [⇲](#web)

+ **Download** 
  ```bash
  git clone https://github.com/flutter/flutter.git -b stable
  ```
+ **Install**
  - Set path variable 
  
+ **Enable desktop support**
  
  ```bash
  flutter config --enable-windows-desktop
  ```
  ```bash
  flutter config --enable-windows-uwp-desktop
  ```
  ```bash
  flutter config --enable-macos-desktop
  ```
  ```bash
  flutter config --enable-linux-desktop
  ```
  
+ **Additional Linux requirements**

  For Linux desktop development, you need the following in addition to the Flutter SDK:

  - Clang
  - CMake
  - GTK development headers
  - Ninja build
  - pkg-config
  
  Run the following command
  ```bash
  sudo apt install clang cmake ninja-build pkg-config libgtk-3-dev
  ```

## Flutter web [ぷ](https://ShivaShirsath.github.io/flutter-web)
A new Flutter project.

### Create Project
```bash
flutter create --org=`PACKAGE_NAME` --android-language=`ANDROID_LANGUAGE` --ios-language=`IOS_LANGUAGE ` `PROJECT_NAME` -`MODE`overwrite # yes = "-", no = "-no-"
```
Windows Flutter Desktop App Support
flutter create --platforms=`PLATFORM_NAME` // windows, macos, linux, web

flutter config --enable-`PLATFORM_NAME` // platform-name= windows-desktop, macos-desktop, linux-desktop, web
### Check Flutter & Dart

### Check by Doctor

### ‎

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
