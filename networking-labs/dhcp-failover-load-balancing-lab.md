# DHCP Failover and Load Balancing Lab

## Goal

Configure and test DHCP failover between two servers.

## Lab environment

- Windows Server
- DHCP Server
- Router server: RTR
- Domain Controller / DHCP partner: DC01
- Client PC

## What I configured

- DHCP failover relationship between RTR and DC01
- Load balance mode
- DHCP scope redundancy
- Client IP lease testing
- Failover test by shutting down RTR

## Test result

Before shutting down RTR, the client received DHCP service from:

- DHCP server: 10.6.1.1

After shutting down RTR, the DHCP server changed to:

- DHCP server: 10.6.1.11

This shows that DHCP failover worked correctly.

## Proof / screenshots

Screenshots from the lab show:

- ipconfig /all output
- DHCP server address change
- Failover status: Normal
- Mode: Load balance
- Partner server: DC01

## What I learned

In this lab I learned how DHCP failover works, how load balancing is used between DHCP servers, and how to verify failover using ipconfig /all.

## Status

Completed
