<h1>Intended for Debian Linux.</h1>


<h2>Description:</h2>

This is a network scanner that allows you to discover all devices in the subnet by sending an arp message with the broadcast mac address to all hosts in the subnet.

<h2>Prerequisites:</h2>

1. scapy.all

2. optparse


To install: 

pip install scapy.all 

pip install optparse


<h2>Usage:</h2>

--help  ---> will show available options

example: 

python Network_scanner.py -t <subnet like 10.0.0.1/24>


<h2>Note:</h2>

by default, this program will use the original NIC (eth0). If you intend to use this with an external NIC (wlan0) please turn off eth0.
