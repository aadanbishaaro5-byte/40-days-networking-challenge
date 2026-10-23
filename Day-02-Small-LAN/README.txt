# Day 02 — Small LAN with a Switch

## Project Overview

A small Local Area Network (LAN) connecting four computers through a Cisco 2960 switch.

## Objectives

* Understand how an Ethernet switch connects computers.
* Configure IPv4 addresses.
* Test communication using ping.

## Devices

* 4 PCs
* 1 Cisco 2960 switch
* 4 Copper Straight-Through cables

## IP Addressing

| Device | IP Address  | Subnet Mask   |
| ------ | ----------- | ------------- |
| PC0    | 192.168.2.1 | 255.255.255.0 |
| PC1    | 192.168.2.2 | 255.255.255.0 |
| PC2    | 192.168.2.3 | 255.255.255.0 |
| PC3    | 192.168.2.4 | 255.255.255.0 |

## Testing

Test connectivity between PCs using the ping command.

Example: `ping 192.168.2.2`

## Expected Result

All four computers should communicate with each other when the connections and IP settings are correct.

## Files

* small-lan.pkt
* topology.png

## What I Learned

* How to connect multiple computers using a switch.
* How to configure IPv4 addresses.
* How to test LAN connectivity.
