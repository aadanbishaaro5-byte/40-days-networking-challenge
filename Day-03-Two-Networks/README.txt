# Day 03 — Two Different Networks

## Project Overview

This project connects two different IPv4 networks using a Cisco 2911 router and two Cisco 2960 switches.

## Objectives

* Understand IPv4 addressing and subnet masks.
* Identify network and host addresses.
* Configure router interfaces.
* Configure default gateways.
* Test communication between different networks using ping.

## Devices

* 2 PCs
* 2 Cisco 2960 switches
* 1 Cisco 2911 router
* Ethernet cables

## IP Addressing

| Device      | IP Address    | Subnet Mask   | Default Gateway |
| ----------- | ------------- | ------------- | --------------- |
| PC0         | 192.168.10.10 | 255.255.255.0 | 192.168.10.1    |
| Router G0/0 | 192.168.10.1  | 255.255.255.0 | N/A             |
| Router G0/1 | 192.168.20.1  | 255.255.255.0 | N/A             |
| PC1         | 192.168.20.10 | 255.255.255.0 | 192.168.20.1    |

## Testing

* Ping the local router interface from each PC.
* Ping between PC0 and PC1.
* Verify router interfaces with `show ip interface brief`.

## Expected Result

PC0 and PC1 should communicate through the router when the IP addresses, gateways, interfaces, and cables are configured correctly.

## Files

* two-networks.pkt
* topology.png

## What I Learned

* How subnet masks identify network boundaries.
* How a router connects different IP networks.
* How to configure router interfaces and default gateways.
