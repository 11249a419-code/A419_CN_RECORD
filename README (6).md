# Experiment 17 — Inspect packets on your network

1. Open Wireshark and select the active interface.
2. Start capture.
3. Generate traffic in a terminal:
   - Windows: `ping example.com`, `nslookup example.com`
   - Ubuntu/Linux: `ping -c 4 example.com`, `nslookup example.com`
4. Stop capture.
5. Apply `dns` or `icmp`.
6. Select packets and expand Ethernet, IP, TCP/UDP, and application layers.
7. Optionally inspect **Statistics → Protocol Hierarchy** and **Statistics → Conversations**.

**Output evidence:** Add screenshots showing packet list and packet details. Do not publish captures containing private traffic or credentials.
