# Pack-View
A network toolkit for Network Professionals for Packet analysis and Troubleshooting

## Table of Contents:
- [Subnet Calculator](#subnet-calculator)
- [Telnet and SSH Network Configuration](#telnet-and-ssh-network-configuration)
- [DHCP Client Simulator](#dhcp-client-simulator)
- [Network Parameter Extractor](#network-parameter-extractor)
- [OSPF Network Discovery via SNMP](#ospf-network-discovery-via-snmp)
- [Packet sniffer](#packet-sniffer)
- [Config File Comparator](#config-file-comparator)
- [Network Topology](#network-topology)


##Subnet Calculator
##Telnet and SSH Network Configuration
##DHCP Client Simulator
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
