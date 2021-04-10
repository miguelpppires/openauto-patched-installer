# OAInstaller Script
Installer for openauto which patches various issues with newer GSP/touchscreen/device detection issues.
Should work on any OpenAuto compatible platform, but intended for Raspberry Pi.

Tested using latest Raspbian Buster (2019-09-26) on 3B (but now supports other environments as of Feb 13 2020 - thank you DreamHazard for telling me about that)

# Installation Instructions
* Install git, if it's not already installed: `sudo apt install git`
* CD to user directory: `cd ~`
* Clone this repo: `git clone https://github.com/miguelpppires/openauto-patched-installer-e30`
* Mark as executable: `sudo chmod +x openauto-patched-installer-e30/installer.sh`
* Run the installer: `openauto-patched-installer-e30/installer.sh`
* Open OpenAuto (add to crontab or other autorun to start at boot): `sudo ~/openauto/bin/autoapp`
* Configure as necessary, plug in your phone, and you're good to go!

# Any issues?
Please notify me (issues tab) so I can attempt to find a solution.

# Uses:
**AASDK**: [abraha2d/aasdk](https://github.com/abraha2d/aasdk), forked from: [opencardev/aasdk](https://github.com/opencardev/aasdk), forked from: [f1xpl/aasdk](https://github.com/f1xpl/aasdk)

**OpenAuto**: [humeman/openauto](https://github.com/humeman/openauto), forked from: [Oper92/openauto](https://github.com/Oper92/openauto), forked from: [f1xpl/openauto](https://github.com/f1xpl/openauto)

*My openauto repo uses a fix to VideoService to stop compile errors, found at [abraha2d/openauto](https://github.com/abraha2d/openauto)*
