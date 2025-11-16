# TCP 3-Way Handshake — Wireshark Demo

## Goal
Capture SYN → SYN/ACK → ACK sequence and explain its importance in network security.

## Why It Matters
- Helps detect scanning behavior
- Useful for identifying anomalous TCP flows
- Basis for understanding packet-level traffic analysis

## Steps
1. Start Wireshark
2. Apply filter: tcp.flags.syn == 1 || tcp.flags.ack == 1
3. Initiate a connection (ping, browser request)
4. Observe handshake packets

## Key Learnings
- SYN: Client requests connection
- SYN/ACK: Server acknowledges
- ACK: Client finalizes connection

## Screenshot
<img width="1920" height="1080" alt="Screenshot_2025-11-14_00_47_40" src="https://github.com/user-attachments/assets/9e765bcb-1d14-4903-bf5b-3763dd1a2cea" />
<img width="1920" height="1080" alt="Screenshot_2025-11-14_00_46_24" src="https://github.com/user-attachments/assets/55a54afd-1160-4b75-b52c-2cdad0ae1272" />
<img width="1920" height="1080" alt="Screenshot_2025-11-14_00_46_33" src="https://github.com/user-attachments/assets/0a2e98c3-b20a-417a-9eb3-ecc6b877f120" />
