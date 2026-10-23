# Day 01 — Two PCs Connection

## Project Overview

This project demonstrates basic communication between two computers using IPv4 addressing in Cisco Packet Tracer.

## Objectives

* Understand basic IP addressing.
* Configure IPv4 addresses and subnet masks.
* Test connectivity using the ping command.

## Devices Used

* PC0
* PC1
* Ethernet cable

## IP Addressing

| Device | IP Address  | Subnet Mask   |
| ------ | ----------- | ------------- |
| PC0    | 192.168.1.1 | 255.255.255.0 |
| PC1    | 192.168.1.2 | 255.255.255.0 |

## Testing

From PC0, run:

`ping 192.168.1.2`

Expected result: PC0 receives replies from PC1 when the connection is configured correctly.

## Files

* `two-pcs.pkt` — Packet Tracer project
* `topology.png` — Network topology screenshot

## What I Learned

* How to assign IPv4 addresses.
* How to use the ping command.
* How to verify basic network connectivity.
