# Windows 10 Transformation Pack

Repository hosting the Windows 10 GTK, Icon and Metacity themes. This Work aims to provide the closest imitation of Microsoft's Windows 10 appearance, while making itself available to the most Desktop Environments. For a complete compatibility list, visit the [theme's webpage](http://b00merang.weebly.com/windows-10-transformation-pack.html)

![Windows-10-TP-by-B00merang](http://b00merang.weebly.com/uploads/1/6/8/1/16813022/screenshot-2016-11-01-10-35-43_orig.png)

### [Dark available theme here](https://github.com/B00merang-Project/Windows-10-Dark) ###

**Maintainer :** [Elbullazul](https://github.com/Elbullazul) - since September of 2015

**Distributor :** [B00merang Theming](https://github.com/B00merang-Project)

**License :** GPL v3

For the moment, this theme works with the following Desktop environments : 
- Cinnamon 2.4/2.6/2.8/3.0/3.2
- GNOME-SHELL 3.14/3.16/3.18/3.20/3.22
- XFCE 4.x
- MATE 1.8/1.10/1.12 and greater
- LXDE 0.8/0.10 and greater
- KDE Plasma 5 (KDE 4 has some issues)
- Unity 7.x
- Openbox 3
- Fluxbox

### Requirements

- GTK+ 3.6 or above
- Murrine theme engine (GTK 2)

## How to install

- **From source**
1. Head to the [releases](https://github.com/Elbullazul/Windows-10/releases) page
2. Download the latest release (as of 8/6/2017 latest is v1.0.0)
3. Open your file manager and navigate to your home folder. If nonexistant, create the **.themes** and **.icons** folder. Enable the 'view hidden files' option to work with them. Generally, Ctrl+H reveals the hidden folders
4. Extract the packages and place the resulting folders (*Windows 10 Light*) in the .themes folder.
5. You're all set! Open your appearance manager and select the corresponding themes from the list

> For common issues and solutions, visit our [wiki page](https://github.com/Elbullazul/Windows-10/wiki)

- **Using Bash script**

*This method gets the source code from the master branch, thus always installing the latest version*

1. Get the auto installer [from here](https://raw.githubusercontent.com/B00merang-Project/Shell-Scripts/master/auto_install.sh)
2. Open a terminal where you downloaded the file and run chmod +x to allow execution
3. The script will download the latest version and unpack it in your ~/.themes folder
4. Open your distro's customization tool to apply the theme

`To uninstall the package`

1. Remove 'Windows 10' from your ~/.themes folder

## Configuration (Cinnamon Only)

Please note that this guide contains third-party software. Therefore, B00merang is not responsible for its content.

1. Most of the menu bar configuration is explained in [rubsalma's video on YouTube](https://www.youtube.com/watch?v=OT958w5YW9c).
2. To make your menu look like the menu in the image at the top of this page, install the "Slingshot" applet on Cinnamon. If you can't find any of the applets when you search, hit the "Refresh list" button in the "Available applets (online)" tab.
3. To make your taskbar icons look like Windows 10, install the "Icing Task Manager" applet, not the grouping applet described in the video (WindowListWithAppGrouping breaks Cinnamon 3.0 and above when used). Icing shows the thumbnails for the open programs, and also allows you to right click the icons.

PS: If you don't want to have to go through all this work yourself, but want the look in Linux Mint Cinnamon, then check out feren OS, it comes with a Windows 10 Transformation using this exact theme in Themer that does all the hard work for you.
