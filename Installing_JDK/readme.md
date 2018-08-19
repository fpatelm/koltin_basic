# Installing the Java Development Kit (JDK)
If you don't have the latest JDK already installed on your computer, follow the steps below. You will need to have the JDK installed to run Kotlin programs.

The JDK is freely available, and you can download it here: http://www.oracle.com/technetwork/java/javase/overview/index.html.

# The JDK or the JRE?
The JRE (Java Runtime Environment) is needed for running Java and Kotlin programs. The JDK (Java Development Kit), on the other hand, includes the JRE, plus the development tools you'll need for writing and running Java programs. You need the JDK for writing Kotlin Programs.

# Steps to install the JDK
1. Uninstall any older versions of the JDK/JRE
We recommend that you install only the latest JDK.

1. Download the JDK
You can download the JDK for free here: http://www.oracle.com/technetwork/java/javase/downloads/index.html.
    1. Click the "Download" button under the JDK for the latest Java SE version.
    1. Check "Accept License Agreement".
    1. Choose the JDK for your operating system.
1. Install the JDK (for Mac)
From either the Downloads window of the browser, or from the file browser, double-click the .dmg file to launch the install file.
A Finder window appears with an icon of an open box and the name of the .pkg file.
Double-click the package icon to launch the Install app, and follow the prompts as they appear.
You might need to enter the administrator password to continue.
Feel free to delete the .dmg file to save space after the installation is complete.
1. Install the JDK (for Windows)
Run the downloaded installer (e.g., jdk-10.0.x_windows-x64_bin.exe), which installs both the JDK and the JRE.

By default, the JDK will be installed in the directory "C:\Program Files\Java\jdk-10.0.x", where x denotes the version number; and the JRE in "C:\Program Files\Java\jre-10.0.x".

Accept the defaults, and follow the screen instructions to install the JDK.

1. Add the JDK installation path to PATH (Windows only)
Windows searches the current directory and the directories listed in the PATH environment variable (system variable) for executable programs.

    1. Open "Control Panel" -> "System" -> "Advanced system settings" -> "Environment Variables".
    1. Under "System variables", scroll down to select "Path" and click "Edit...".
    1. Append to the existing Path value a semi-colon ";" then the JDK's "bin" directory (e.g. ";C:\Program Files\Java\jdk-10.0.0\bin").
