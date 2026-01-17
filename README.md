# EE533 Lab 1

## Day 1
- Installed VMware Workstation Pro on Windows
- Created two Ubuntu 22.04 Desktop VMs: Server and Client
- Configured NAT networking between VMs
- Verified connectivity: Client successfully pinged Server

## Day 2
- Implemented TCP socket server and client using provided example code
- Successfully ran server on Server VM and client on Client VM
- Verified message exchange between client and server

## Day 3
- Modified TCP server to support concurrent clients using while loop and fork()
- Verified server can handle multiple client connections without terminating
- Successfully tested concurrent connections across two virtual machines
- Server handled each client request in a separate child process

