WINAUTOPWN :
Created by Azim Poonawala (quakerdoomer@fmguy.com)
http://solidmecca.co.nr
http://winautopwn.co.nr


 
WINDOWS AUTOPWN

Autohack your targets with least possible interaction.

Features :

- Contains already custom-compiled executables of famous and effective exploits alongwith a few original exploits.
- No need to debug, script or compile the source codes.
- Scans all ports 1 - 65535 after taking the IP address and tries all possible exploits according to the list of discovered open ports (OpenPorts.TXT)
- PortScan is multi-threaded.
- Multiple types and platforms of Shellcodes available for exploits.
- Can be also be used to test effectiveness of IDS/IPS
- Launched exploits are independent and doesn't rely on service fingerprinting (to avoid evasion, if any)

winAUTOPWN unlike a few other frameworks maintains the original exploit writer's source code intact just as it was and uses it. This way the exploit writer's credit and originality is maintained. The source is modified only when required to enable a missing feature or to remove hard-coded limitations. Under these circumstances also, the exploit writers credits remain intact. 

Newer exploit modules are added as and when they release and older ones are also being daily added.
Binaries of perl, php, python, ruby and cygwin DLLs (included) are required to exist either in a common folder or should be properly installed with their paths registered for those exploits which are cannot be compiled into a PE-exe. 

Some anti-viruses might falsely detect the exploits as malicious.

Future :
- A separate DragonflyBSD-server is being set up which will hold the exploit repository and the next version will autosync the exploits from them in the appropriate folder. 


NOTE : In case of emergency, Press "Q" / "q" anytime during the portscan to EXIT the winAUTOPWN.
NOTE : This program winAUTOPWN was released earlier under the WTFPL (http://sam.zoy.org/wtfpl/)


Thanks to Ameya M. Nayak for helping with the strchr() problem