# 🚚 Transport: Reliable Transport Protocol
The goal of this project was to implement a TCP-like protocol with reliable, in-order data delivery over an unreliable network. The protocol handles connection setup, teardown, retransmissions, congestion control, and timeout management, emulating core TCP behaviors from scratch.

## 🛠️ Skills & Technologies Used

- **Languages:** Python 3
- **Networking Concepts:**
  - 3-Way Handshake (SYN, SYN-ACK, ACK)
  - Reliable data delivery (seq/ack tracking)
  - Sliding Window protocol
  - Congestion Control (Slow Start, Congestion Avoidance, Fast Retransmit)
  - RTT Estimation with exponential smoothing
  - Finite State Machines for connection lifecycle
- **Tools & Testing:**
  - Python asyncio for non-blocking IO
  - Project-provided harness and test framework
  - Wireshark for packet inspection and debugging

Network simulator code from [https://github.com/noxrepo/pox](https://github.com/noxrepo/pox). See that repo for licensing information.
