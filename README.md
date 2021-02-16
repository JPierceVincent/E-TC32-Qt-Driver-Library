**TC32-Ethernet-Qt-C++-Driver-Library v1.0.0**

A Qt C++ modified port of an open source C driver for the MCC TC-32 written by Warren Jasper and housed at the repo:
https://github.com/org-arl/MCC_Linux_Drivers/tree/master/Ethernet/c
This port expands system compatibility along with moving towards support for automated collection and multithreaded operation in order to leverage the jump to C++.

**TODO**
1. Move UDP/TCP buffers into mccqethernet object.
2. Add additional support for functions in original project which are not currently ported.

**v1.0 Notes**

**JV(2/16/2021 15:43 PST):** *Discovered that there was mishandling in the multithreading implementation. Project was fixed, rezipped, and uploaded. Now there are indicators in the gui indicating current collected temperature as well as connection status and units being displayed on the LCD panel*

**JV(2/15/2021 17:06 PST):** *Example project which includes the source of the driver and an example of how to create a device and start automated collection of a single channel's data.*

**Notes on Licensing**

As with the original version, this is released under the GNU lesser general public license and as such, it may be used in any other project you deem fit but comes with no guaranteed support or functionality. Furthermore if this code is modified, that code will also need to be released (as I'm doing here) under the same license.
