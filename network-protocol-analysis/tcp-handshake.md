# TCP 3-Way Handshake Analysis

This lab demonstrates how a TCP connection is established between a client and a server using the three-way handshake: **SYN → SYN/ACK → ACK**.

## Objective
Analyse a real TCP handshake captured in Wireshark and understand how connection establishment works.

## Tools
- Wireshark
- Kali Linux / Ubuntu
- curl or ping for generating packets

## Steps

### 1. Start Packet Capture
```bash
sudo wireshark
Apply filter: tcp.flags.syn == 1 || tcp.flags.ack == 1
```
### 2. Initiate a Connection
curl www.google.com

### 3. Observe the Handshake
Step	Description

- ` SYN	Client - asks to initiate connection `
- ` SYN/ACK	Server - acknowledges and responds `
- ` ACK	Client confirms, - connection established `

### 4. Screenshots
<img width="1920" height="1080" alt="Screenshot_2025-11-14_00_47_40" src="https://github.com/user-attachments/assets/42b3d107-650f-4eb6-88ab-f9f1b4d63884" />
<img width="1920" height="1080" alt="Screenshot_2025-11-14_00_46_24" src="https://github.com/user-attachments/assets/191b7b17-711f-4a95-8120-d9e25809262d" />
<img width="1920" height="1080" alt="Screenshot_2025-11-14_00_46_33" src="https://github.com/user-attachments/assets/34dfa3c7-9685-4245-badf-5aa16f96127a" />

### 5. Key Fields Observed

- Sequence numbers
- ACK numbers
- Window size
- Flags (SYN, ACK)

  

## What I Learned

- How TCP establishes reliable communication
- Importance of sequence and acknowledgment numbers
- How network delay or packet loss affects the handshake
