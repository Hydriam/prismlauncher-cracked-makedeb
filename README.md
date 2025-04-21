# prismlauncher-cracked-makedeb
A **unofficial** makedeb repo for [prismlauncher-cracked](https://github.com/Diegiwg/PrismLauncher-Cracked) project.
This is used to simply build prismlauncher-cracked .deb using makedeb. 
The .deb can be used for debian and all systems that are based on it (Ubuntu, Linux Mint etc.)

This is not endorsed by Prism Launcher or by Prism Launcher Cracked Projects.

## Instructions
Firstly get the files to build it:
```
git clone https://github.com/Hydriam/prismlauncher-cracked-make
cd prismlauncher-cracked-make
```
Then we build it, in makedeb -s parametr installs dependency and -i installs the .deb to the system after building.
```
makedeb -si 
```
