#Windows 10 Transformation Pack#

Repository hosting the Windows 10 GTK, Icon and Metacity themes. This Work aims to provide the closest imitation of Microsoft's Windows 10 appearance, while making itself available to the most Desktop Environments. For a complete compatibility list, visit the [theme's webpage](http://b00merang.weebly.com/windows-10-transformation-pack.html)

![Windows-10-TP-by-B00merang](http://b00merang.weebly.com/uploads/1/6/8/1/16813022/2d76a816-3341-11e6-8a4b-67e8253851c7_orig.png)

**Maintainer :** [Elbullazul](https://github.com/Elbullazul) - since September of 2015

**Distributor :** [B00merang Theming](https://github.com/B00merang-Project)

**License :** GPL v3

##How to install##

- **From source**
 
1. Head to the [releases](https://github.com/Elbullazul/Windows-10/releases) page
2. Download the latest release (as of 10/26/2016 latest is v0.9.9 SP1)
3. **Checksum** the packages to check everything is ok. To do so, open a terminal and navigate to the folder where the package is stored. Then run sha512sum and copy the resulting string. Use [Text Compare](https://text-compare.com/) to compare the sums you get and the one shown in the releases page
4. If the sums match, open your file manager and navigate to your home folder. If nonexistant, create the **.themes** and **.icons** folder. Enable the 'view hidden files' option to work with them. Generally, Ctrl+H reveals the hidden folders
5. Extract the packages and place the resulting folders (named *Windows 10 Light* and *Windows 10 Dark*) in the .themes folder. The Icon set should be placed in *.icons* once extracted
6. You're all set! Open your appearance manager and select the corresponding themes from the list

> For common issues and solutions, visit our [wiki page](https://github.com/Elbullazul/Windows-10/wiki)

- **Using Bash script**

*This method gets the source code from the master branch, thus always installing the latest version*

1. Get the TransPack installer [from here](https://github.com/B00merang-Project/TransPack/archive/master.zip)
2. Unpack the package and open a terminal in extracted folder. Add execution rights with `chmod +x install.sh`
3. In same terminal, type `./install.sh`
4. Choose which variant to install and wait till the process finishes. *YOU MAY need to restart your DE after the install*
5. If the installation fails, open an issue, clearly explaining the error and including the log file if possible

`To uninstall the package`

1. Open a terminal and navigate to where uninstall.sh is
2. Add execution rights with `chmod +x uninstall.sh`
3. Run `./uninstall.sh`
