#Windows 10 Themes#

[![Join the chat at https://gitter.im/Elbullazul/Windows-10](https://badges.gitter.im/Elbullazul/Windows-10.svg)](https://gitter.im/Elbullazul/Windows-10?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

**Home of the Windows 10 Transformation Pack for Linux compatible Distributions**

---
![Windows-10-theme-by-B00merang](https://cn.pling.com/img//hive/content-pre1/171327-1.png)

> Website: http://b00merang.weebly.com/windows-10-transformation-pack.html

**Theme produced and maintained by**
- [Elbullazul](https://github.com/Elbullazul) (Christian Medel) since it's creation, back in September of 2015

**Distributor: B00merang Theming**

License: GPL v3

##How to install##

- **From source**
 
1. Head to the [releases](https://github.com/Elbullazul/Windows-10/releases) page
2. Download the latest release (as of 7/4/2016 latest is v0.9.9)
3. **Checksum** the packages to check everything is ok. To do so, open a terminal and navigate to the folder where the package is stored. Then run sha512sum and copy the resulting string. Use [Text Compare](https://text-compare.com/) to compare the sums you get and the one shown in the releases page
4. If the sums match, open your file manager and navigate to your home folder. If nonexistant, create the **.themes** and **.icons** folder. Enable the 'view hidden files' option to work with them. Generally, Ctrl+H reveals the hidden folders
5. Extract the packages and place the resulting folders (named *Windows 10 Light* and *Windows 10 Dark*) in the .themes folder. The Icon set should be placed in *.icons* once extracted
6. You're all set! Open your appearance manager and select the corresponding themes from the list

- **Using the built-in installer**

*Some users may find it hard to manipulate files like this, so we've built a small shell script that installs it for you,***SYSTEM-WIDE**

1. Get the latest transformation pack from our [GNOME-LOOK](https://www.gnome-look.org/content/show.php/Windows%ED%9D%8F%E9%8E%85%EE%A6%9E?content=171327) webpage
2. Unpack the file and open a terminal in the current directory
3. Type ```bash install.sh```. What we're doing is piping the file to bash, so we don't have to mess with permissions and chmod +x
4. The B00merang Installer should launch. Follow the steps until you get a message that everything went well. If it **DOESN'T**, then email-us, including the install.log file created during the installation and explaining what didn't go as expected

