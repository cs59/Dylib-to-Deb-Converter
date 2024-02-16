# Dylib-to-Deb-Converter
A script meant to run in iOS to convert .dylib file to .deb with the support for both Rootfull &amp; Rootless jailbreak environment.

# Requirements
macOS or Jailbroken IOS with Terminal access.

# Usage
Place the Deb-Creator.sh file into any location using filza or any file manager.
(If script having some permission issues, then run 'chmod +x path/to/deb-creator.sh'.
Open any Terminal and cd to the folder where you saved the file.
Then run 'sudo ./Deb-Creator.sh'.
Place path of dylib file and select version you want to.
Then select whether to make deb for rootfull or rootless environment.
After done creating deb. you can locate the deb in /var/mobile in root or in Desktop if using macOS.

PS: if file is not executing in macos terminal even with the above commands, then type "sudo drag&drop.shFile" then click Enter.

# Important
Make sure dpkg and bash is installed.
If not, you can install it from your package manager or "brew install dpkg" if using macOS.
Also, you can change the Maintainer name in the code of deb creator sh file.
