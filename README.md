# prismlauncher-cracked-makedeb
A **unofficial** makedeb repo for [prismlauncher-cracked](https://github.com/Diegiwg/PrismLauncher-Cracked) project.
This is used to simply build prismlauncher-cracked .deb using makedeb. 
The .deb can be used for debian and all systems that are based on it (Ubuntu, Linux Mint etc.)

This is not endorsed by Prism Launcher or by Prism Launcher Cracked Projects.

This project doesn't distribute prismlauncher-cracked binaries.
This project just has build files for easier building of prismlauncher-cracked package, with the package you can install it to system.

## Instructions
If you dont have make deb installed, install makedeb using command from [this site](https://www.makedeb.org/).

Get the files to build the package:
```
git clone https://github.com/Hydriam/prismlauncher-cracked-makedeb
cd prismlauncher-cracked-makedeb
```
Then we build it, in makedeb -s parametr installs dependency and -i installs the .deb to the system after building.
```
makedeb -si 
```
