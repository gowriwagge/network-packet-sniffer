# networkk-packet-sniffer
A Network Packet Sniffer developed in Python 3. Packets are disassembled as they arrive at a given network interface controller and their information is displayed on the screen.  This application depends exclusively on the NETProtocols library 

Usage
sniffer.py [-h] [-i INTERFACE] [-d]

Network Packet Sniffer

optional arguments:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface INTERFACE
                        Interface from which packets will be captured (monitors
                        all available interfaces by default).
  -d, --data            Output packet data during capture.
