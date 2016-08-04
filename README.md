# Pack-View
A network toolkit for Network Professionals for Packet analysis and Troubleshooting.

## Table of Contents:
- [Address Cal](#address-cal)
- [Dev-connect](#dev-connect)
- [DHCP Client Simulator](#dhcp-client-simulator)
- [Network Parameter Extractor](#network-parameter-extractor)
- [OSPF Network Discovery via SNMP](#ospf-network-discovery-via-snmp)
- [Packet sniffer](#packet-sniffer)
- [Config File Comparator](#config-file-comparator)
- [Network Topology](#network-topology)


##Address Cal
Address Cal is a subnet calculator which involves the user for ip address and subnet mask in dotted decimal Notation. It produces the output with network address, boardcast address, number of valid hosts, wildcard mask and mask bits.

##Dev-connect
Dev-connect is a scripting tool which manages various files for pinging 2 or more routers from a host, validate the username and password from a file, connects using telnet or SSH connection and runs the respective commands on each router. By doing so, it is easy to manage 2 or more routers from a single host. 

##DHCP Client Simulator
DHCP Client Simulator is a simulator which is designed for stimulating DHCP client and stimulating DHCP releases. The leased IP addresses are then exported to a separate text file. 

##Network Parameter Extractor

##OSPF Network Discovery via SNMP

##Pack-Sniff
Pack-Sniff is a basic network sniffer, which captures some predefined protocols
and saves info about each network packet in an external file.
##Config File Comparator
This application connects to a router in the network via Telnet, extracts the output of
“show running-config” and “show startup-config”, filters the irrelevant lines and
finally compares the configurations. This can be accomplished using the
“show archive config differences” command in Cisco CLI. Instead i succeeded in
accomplishing this task using Python.


##Network Topology

![network topology](https://cloud.githubusercontent.com/assets/16948906/17378009/22fc60c8-5971-11e6-9bfa-a03aa4948b1b.png)
