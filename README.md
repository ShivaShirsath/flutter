<h1 align=center>
  <a href=https://flutter.dev>
    ⇱
  </a>
  Flutter
</h1>

## [⇱](https://flutter.dev/docs/get-started/install) Install 
- [⇱](https://flutter.dev/docs/get-started/install/windows) Windows
- [⇱](https://flutter.dev/docs/get-started/install/macos) macOS
- [⇱](https://flutter.dev/docs/get-started/install/linux) Linux
- [⇱](https://flutter.dev/docs/get-started/install/chromeos) Chrome OS
- [⇱](https://flutter.dev/docs/get-started/web) Web

+ **Download** 

  github [flutter](https://github.com/flutter)-[reporitory](https://github.com/flutter/flutter)
  ```bash
  git clone https://github.com/flutter/flutter.git -b stable
  ```
+ **Install**
  - Set path variable 
  
+ **Additional Linux requirements**
  
  Run the following command
  ```bash
  sudo apt install clang cmake ninja-build pkg-config libgtk-3-dev
  ```

## Flutter web [ぷ](https://ShivaShirsath.github.io/flutter-web)

### Create Project
```bash
flutter create 
```
### Configure Project
```bash
flutter config
```
### Single Platform
+ **Create**
  ```bash
  flutter create [project_name] --platforms [platform]
  ```
+ **Configure**
  ```bash
  flutter config --enable-[platform]
  # eg. platforms are [ android , ios , web , linux-desktop , windows-desktop , macos-desktop ]
  ```
+ **Run**
  ```bash
  cd [project_name]
  ```
  ```bash
  flutter run
  ```
  ```bash
  flutter run -d web-server --web-port 8080 # [Web-Server] : http://localhost:8080
  ```
