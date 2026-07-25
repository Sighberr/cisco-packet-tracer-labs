# 02 - Multi-Department Office Network

## Business Scenario

Apex Solutions expanded from one office into two departments: Accounting and Sales. Each department needed its own network while still being able to communicate with the other through a router.

## Overview

Designed and configured a routed office network using two subnets connected by a Cisco router.

## Goal

Allow devices in different departments to communicate while keeping each department on its own network.

## Devices

- Cisco 2911 Router
- 2 Cisco 2960 Switches
- 4 PCs
- 2 Network Printers

## Network

### Accounting
- Network: 192.168.10.0/24
- Default Gateway: 192.168.10.1

### Sales
- Network: 192.168.20.0/24
- Default Gateway: 192.168.20.1

## Skills

- Router Configuration
- Static IP Addressing
- Multiple Subnets
- Default Gateway Configuration
- Routing Between Networks
- Network Testing

## Results

- Configured two separate LANs.
- Configured router interfaces.
- Verified communication within each department.
- Verified communication between both departments using ping.

## Files



## What I Learned

This project helped me understand how routers connect different subnets and why every device uses the router interface on its own subnet as its default gateway.
