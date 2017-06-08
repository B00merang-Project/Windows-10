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

1. Get the TransPack installer [from here](https://github.com/B00merang-Project/Shell-Scripts/blob/master/transpack.sh)
2. Unpack the package and open a terminal in extracted folder. Add execution rights with `chmod +x transpack.sh`
3. In same terminal, type `./transpack.sh`
4. Choose which variant to install and wait till the process finishes. *YOU MAY need to restart your DE after the install*
5. If the installation fails, open an issue, clearly explaining the error and including the log file if possible

`To uninstall the package`

1. Open a terminal and navigate to where transpack.sh is
3. Run `./transpack.sh (-l for local uninstall) -u`
