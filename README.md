# Initializing-and-Reloading-Networking-Devices
This is a simple project in which two devices (PCs) are connect to two networking devices (router and switch) in order to reload them.
Firstly, the router has been initialized and reloaded. The startup-config file has been deleted and then the reload command is given. 
After the reload command us issued, if prompted for entering or continuing previous startup, enter 'no'. 

Same process goes for switch.
First the **show flash** command has been issued in order to keep a check on any previously created VLANs. Then we clear all vlan.dat files by **delete vlan.dat** command.
Once the file has been deleted, we erase the startup config and then issue the reload command. 

The two devices now have been reloaded. 
