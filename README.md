# Dylib-to-Deb-Converter
A script meant to run in iOS to convert .dylib file to .deb with the support for both Rootfull &amp; Rootless jailbreak environment.

# Requirements
macOS or Jailbroken IOS with Terminal access.

# Usage
For iOS:

1) Place the file in any desired location with proper access to it using File Manager like Filza.
2) Open Terminal, cd to the folder where you saved the file and give permission to the file using this cmd "chmod +x /path/to/iDebCreator.sh".
3) Then type, "sudo ./iDebCreator.sh".
4) Created deb by script will be saved in "/var/mobile".

For macOS:

1) Place the file in any desired location with proper access to it.
2) Open Terminal, cd to the folder where you saved the file and give permission to the file using this cmd "chmod +x /path/to/mDebCreator.sh".
3) Then type, "sudo ./mDebCreator.sh".
4) Created deb by script will be saved in
User Desktop.


PS: if file is not executing in macos terminal even with the above commands, then type "sudo drag&drop/mDebCreator.sh" then click Enter.

# Important
Make sure dpkg and bash is installed.
If not, you can install it from your package manager or "brew install dpkg" if using macOS.
Also, you can change the Maintainer name in the code of sh file.
