
# port-scanner

  Overview:
  ========
port-scanner is a lightweight port scanner written in python. It takes a host name or IP address as a target and the port number that you want to check whether the port is open or not. It can also scan multiple ports simultaneously. It also scans remote hosts as well and shows the services running on that port. It is not designed to give any indepth information about a network, simply to check if the provided port is open and what services are running on it.

Dependencies
========
 This program written in Python 2.7

Compatibility: 
========
This program will run in any python installed Linux distros and windows machine. Tested on Kali Linux and Windows 10 (python 2.7 installed)

 USAGE: 
========
Navigate to the program folder and run the following command:

python port-scanner.py -H (Host name or IP address) -p (port number you want to check)
 
optional arguments:
  -h /  --help           ==  show this help message 
  
  python port-scanner.py  ==  Program usage

Examples
========
python port-scanner.py -H 192.168.1.1 -p 80
if You want to scan multiple ports, please write the port number using a comma:

python port-scanner.py -H 192.168.1.1 -p 21, 22, 80, 416


Bugs & Contact
==============
Feel free to email me with any problem, bug, suggestions or fixes at:
Sazzad Ovi <ovisecret@gmail.com>
