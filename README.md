README:

This file contains instructions for running Deluxe Programming Tools
Made by Grant Napier, Sr., Joshua Clemens, Philip Harman

The program runs using Python 2.7

You must run the main program with root permission "sudo python tDriver.py"
 - Creating subprocesses to call nmap requires root privlages

Using the tools:
  Run the main driver program:                 "sudo python tDriver.py"
  Run the system information tool:             "python sysinfo.py"
  Run the basic chat room server/client:       "python chat2.py"
  Run the async chat room server:              "python CR3.py"
  Run the asyn chat room client:               "python CRclient3.py"
  Run the network monitoring tool:             "sudo python nm5.py"
  Run the DoS/Ping of Death tool:              "python pingtd.py"
  Run Ping of Death Verification tool:         "python ping_v.py"

Dependencies:

  Command Line Utilities:
    Must have arp-scan installed:   "sudo apt-get install arp-scan"
    Must have nmap installed:       "sudo apt-get install nmap"

  Python Module Utilities:
    Must have netifaces installed:  "sudo pip install netifaces"
    Must have colorama installed:   "sudo pip install colorama"
    Must have scapy installed:      "sudo pip install scapy"
