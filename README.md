# ADB-RoboRIO-Installer
A port of ADB for the NI RoboRIO. Intended for use in First Robotics Challenge.

### Installing ADB on your RoboRIO
1. Clone this repository onto a USB flash drive.
2. Plug the flash drive into the RoboRIO.
3. SSH into the RoboRIO using the SSH client of your choice as user ```admin@roboRIO-{your team number}-frc.local```. (i.e. PuTTY)
4. cd into the directory of the installer.
5. Run the following commands:
```
chmod 755 install.sh 
./install.sh
```
