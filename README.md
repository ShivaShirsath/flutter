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
- [⇱](https://flutter.dev/docs/get-started/install/linux) Chrome OS
- [⇱](https://flutter.dev/docs/get-started/web) Web

### Windows
+ **Install**
  Open cmd / camandLine 
  ```cmd
  cd C:\src
  git clone https://github.com/flutter/flutter.git -b stable
  ```
+ **Update your path**
  If you wish to run Flutter commands in the regular Windows console, take these steps to add Flutter to the PATH environment   variable:

  - From the Start search bar, enter ‘env’ and select *Edit* **Environment Variables** for your account.
  - Under **User variables** check if there is an entry called **Path**:
    + If the entry exists, append the full path to `flutter\bin` using `;` as a separator from existing values.
    + If the entry doesn’t exist, create a new user variable named Path with the full path to `flutter\bin` as its value.

  You have to close and reopen any existing console windows for these changes to take effect.
  
+ **Enable desktop support**
  - At the command line, perform the following command to enable Win32 desktop support:

    ```cmd
    flutter config --enable-windows-desktop
    ```
  - For Windows UWP desktop support perform the following commands to switch to the dev channel, upgrade Flutter, and enable UWP.

    ```cmd
    flutter channel dev
    flutter upgrade
    flutter config --enable-windows-uwp-desktop
    ```
    
### macOS
+ **Install**
  Open Terminal
  ```shell
  git clone https://github.com/flutter/flutter.git -b stable
  ```
+ **Update your path**
  You can update your PATH variable for the current session at the command line, as shown in Get the Flutter SDK. You’ll probably want to update this variable permanently, so you can run flutter commands in any terminal session.

  The steps for modifying this variable permanently for all terminal sessions are machine-specific. Typically you add a line to a file that is executed whenever you open a new window. For example:

  - Determine the path of your clone of the Flutter SDK. You need this in Step 3.
  - Open (or create) the rc file for your shell. Typing echo $SHELL in your Terminal tells you which shell you’re using. If you’re using Bash, edit $HOME/.bash_profile or $HOME/.bashrc. If you’re using Z shell, edit $HOME/.zshrc. If you’re using a different shell, the file path and filename will be different on your machine.
  - Add the following line and change [PATH_OF_FLUTTER_GIT_DIRECTORY] to be the path of your clone of the Flutter git repo:

  ```bash
  export PATH="$PATH:[PATH_OF_FLUTTER_GIT_DIRECTORY]/bin"
  ```
  Run source $HOME/.<rc file> to refresh the current window, or open a new terminal window to automatically source the file.
## Flutter web [ぷ](https://ShivaShirsath.github.io/flutter-web)
A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
