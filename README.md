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
flutter create 
```
```
flutter create <output directory>

    <output directory>                [ Information ]
    
-h                       Print this usage information.
--help                   Print this usage information.

--[no-]pub               Whether to run "flutter pub get" after the project has been created.
                         (defaults to on)
                             
--[no-]offline           When "flutter pub get" is run by the create command, this indicates whether to run it in offline mode or not. In offline mode, it will need to have all dependencies already available in the pub cache to succeed.
    
--[no-]overwrite         When performing operations, overwrite existing files.
    
--description            The description to use for your new Flutter project. This string ends up in the pubspec.yaml file.
                         (defaults to "A new Flutter project.")
                             
--org                    The organization responsible for your new Flutter project, in reverse domain name notation. This string is used in Java package names and as prefix in the iOS bundle identifier.
                         (defaults to "com.example")
                             
--project-name           The project name for this new Flutter project. This must be a valid dart package name.
    
-i                       The language to use for iOS-specific code, either ObjectiveC (legacy) or Swift (recommended).
--ios-language           The language to use for iOS-specific code, either ObjectiveC (legacy) or Swift (recommended).
                         [objc, swift (default)]
                             
-a                       The language to use for Android-specific code, either Java (legacy) or Kotlin (recommended).
--android-language       The language to use for Android-specific code, either Java (legacy) or Kotlin (recommended).
                         [java, kotlin (default)]
                             
--platforms              The platforms supported by this project. Platform folders (e.g. android/) will be generated in the target project. This argument only works when "--template" is set to app or plugin. When adding platforms to a plugin project, the pubspec.yaml will be updated with the requested platform. Adding desktop platforms requires the corresponding desktop config setting to be enabled.
                         [ios (default), android (default), windows (default), linux (default), macos (default), web (default)]
                             
-t                       Specify the type of project to create.
--template=<type>        Specify the type of project to create.

          [app]              (default) Generate a Flutter application.
          
          [module]           Generate a project to add a Flutter module to an existing Android or iOS application.
          
          [package]          Generate a shareable Flutter project containing modular Dart code.
          
          [plugin]           Generate a shareable Flutter project containing an API in Dart code with a platform-specific implementation for Android, for iOS code, or for both.
          [skeleton]         Generate a List View / Detail View Flutter application that follows community best practices.


-s                       Specifies the Flutter code sample to use as the "main.dart" for an application. Implies "--template=app". The value should be the sample ID of the desired sample from the API documentation website (http://docs.flutter.dev/). An example can be found at: https://api.flutter.dev/flutter/widgets/SingleChildScrollView-class.html
--sample=<id>            Specifies the Flutter code sample to use as the "main.dart" for an application. Implies "--template=app". The value should be the sample ID of the desired sample from the API documentation website (http://docs.flutter.dev/). An example can be found at: https://api.flutter.dev/flutter/widgets/SingleChildScrollView-class.html

--list-samples=<path>    Specifies a JSON output file for a listing of Flutter code samples that can be created with "--sample".

Run "flutter help" to see global options.                           
```
### Configure Project
```bash
flutter config
```bash
flutter config [arguments]

     [ arguments ]                                        [ Information ]
     
-h                                          Print this usage information.

--help                                      Print this usage information.

--[no-]analytics                            Enable or disable reporting anonymously tool usage statistics and crash reports.

--clear-ios-signing-cert                    Clear the saved development certificate choice used to sign apps for iOS device deployment.

--android-sdk                               The Android SDK directory.

--android-studio-dir                        The Android Studio install directory.

--build-dir=<out/>                          The relative path to override a projects build directory.

--[no-]enable-web                           Enable or disable Flutter for web. This setting will take effect on the master, dev, beta, and stable channels.

--[no-]enable-linux-desktop                 Enable or disable beta-quality support for desktop on Linux. This setting will take effect on the master, dev, beta, and stable channels. Newer beta versions are available on the beta channel.

--[no-]enable-macos-desktop                 Enable or disable beta-quality support for desktop on macOS. This setting will take effect on the master, dev, beta, and stable channels. Newer beta versions are available on the beta channel.

--[no-]enable-windows-desktop               Enable or disable beta-quality support for desktop on Windows. This setting will take effect on the master, dev, beta, and stable channels. Newer beta versions are available on the beta channel.

--[no-]enable-windows-uwp-desktop           Enable or disable Flutter for Windows UWP. This setting will take effect on the master and dev channels.

--[no-]single-widget-reload-optimization    Enable or disable Hot reload optimization for changes to class body of a single widget. This setting will take effect on the master, dev, and beta channels.

--[no-]enable-android                       Enable or disable Flutter for Android. This setting will take effect on the master, dev, beta, and stable channels.

--[no-]enable-ios                           Enable or disable Flutter for iOS. This setting will take effect on the master, dev, beta, and stable channels.

--[no-]enable-fuchsia                       Enable or disable Flutter for Fuchsia. This setting will take effect on the master channel.

--[no-]enable-custom-devices                Enable or disable Early support for custom device types. This setting will take effect on the master and dev channels.

--clear-features                            Remove all configured features and restore them to the default values.

Run "flutter help" to see global options.
```
