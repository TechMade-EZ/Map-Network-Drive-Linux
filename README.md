This is a Linux app that makes Mapping to a Network Share automated through a Linux Graphical Interface without having to edit the fstab file.
You just need to input 

the Server IP Address - 

the server share - 

your server creditials/username-password - 

the folder you want to map to. 

Click the button Map Network Drive - The app automaticlly updates the fstab file and mounts your share. 

The app is a flatpak so it can be installed in Debian, Fedora and Arch
Just Download the app. You can just double mouse click on it and the software manager should onep up and let you install it.
Some software managers can't install a flatpak inless its in the flathub repository you can install it from the terminal
Open Terminal Navigate to the Download Folder cd /Downloads
Copy and Paste Command below to insall:

flatpak install org.mapdrive.MapDrive.flatpak
or sudo flatpak install org.mapdrive.MapDrive.flatpak

Example

![image alt](https://github.com/TechMade-EZ/Map-Network-Drive-Linux/blob/main/input.png?raw=true)
