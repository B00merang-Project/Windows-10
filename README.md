#Windows 10 Transformation Pack#

Repository hosting the Windows 10 GTK, Icon and Metacity themes. This Work aims to provide the closest imitation of Microsoft's Windows 10 appearance, while making itself available to the most Desktop Environments. For a complete compatibility list, visit the [theme's webpage](http://b00merang.weebly.com/windows-10-transformation-pack.html)

![Windows-10-TP-by-B00merang](http://b00merang.weebly.com/uploads/1/6/8/1/16813022/2d76a816-3341-11e6-8a4b-67e8253851c7_orig.png)

**Maintainer :** [Elbullazul](https://github.com/Elbullazul) - since September of 2015

**Distributor :** [B00merang Theming](https://github.com/B00merang-Project)

**License :** GPL v3

##How to install##

- **From source**
 
1. Head to the [releases](https://github.com/Elbullazul/Windows-10/releases) page
2. Download the latest release (as of 7/4/2016 latest is v0.9.9)
3. **Checksum** the packages to check everything is ok. To do so, open a terminal and navigate to the folder where the package is stored. Then run sha512sum and copy the resulting string. Use [Text Compare](https://text-compare.com/) to compare the sums you get and the one shown in the releases page
4. If the sums match, open your file manager and navigate to your home folder. If nonexistant, create the **.themes** and **.icons** folder. Enable the 'view hidden files' option to work with them. Generally, Ctrl+H reveals the hidden folders
5. Extract the packages and place the resulting folders (named *Windows 10 Light* and *Windows 10 Dark*) in the .themes folder. The Icon set should be placed in *.icons* once extracted
6. You're all set! Open your appearance manager and select the corresponding themes from the list

- **Using Bash script**

```diff
- Warning: This method is considered outdated and will soon lose all support
```

1. Get the latest transformation pack from our [GNOME-LOOK](https://www.gnome-look.org/content/show.php/Windows%ED%9D%8F%E9%8E%85%EE%A6%9E?content=171327) webpage
2. Unpack the file and open a terminal in the current directory
3. Type `bash install.sh`. What we're doing is piping the file to bash, so we don't have to mess with permissions and chmod +x
4. The B00merang Installer should launch. Follow the steps until you get a message that everything went well. If it **DOESN'T**, then email-us, including the install.log file created during the installation and explaining what didn't go as expected

**For common issues and solutions, visit our [wiki page](https://github.com/Elbullazul/Windows-10/wiki).
