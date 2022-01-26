# Dopple
This program is used to scan/spoof MAC addresses. The main use case to disguise the MAC address of a selected interface to be the same as a target machine. Additionally this program will also allow users to set their own custom mac addresses. The program can also be used to simply get the mac address of a connected device as well.

<!-- GETTING STARTED -->

### Prerequisites

This program runs on most modern linux operating systems. Python3 is required to run the program.

<!-- USAGE EXAMPLES -->
## Usage
Root privileges are required for dopple to function.


Usage example:

_Sudo python3 dopple -l -d_

### Arguments:

```
An interface will need to be specified and an additional program option must be given.

[Interface]
(The last used interface will be used if none are given)
-i | --interface [Interface]       used to specify what interface the program uses
-l | --list                        used to select from a list the device's network interfaces
    
[Program]
-m | --mac [MAC]                   sets an interface with a specified MAC address
-d | --duplicate                   sets an interface with the MAC address of a connected machine
-s | --scan                        used to view the mac address of a connected machine

[Other]
-h | --help                        used to show help page
--version                          show program's version number
```

<p align="right">(<a href="#top">back to top</a>)</p>
