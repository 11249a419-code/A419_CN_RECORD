# Experiment 01 — Network commands and packet capture

**Aim:** Practise network commands and inspect ping/traceroute packets using Wireshark.

## Commands

### Ubuntu/Linux
```bash
ip addr
ip route
ss -tuln
nslookup example.com
traceroute example.com
ping -c 4 example.com
```

If `traceroute` is not installed, use `tracepath example.com` if available. For packet capture, open Wireshark, select the active interface, start capture, run `ping -c 4 example.com`, stop capture, and use the display filter `icmp`.

### Windows CMD
```bat
ipconfig
netstat -ano
nslookup example.com
tracert example.com
ping example.com
hostname
getmac
arp -a
tasklist
```

**Output evidence:** Save terminal output and a Wireshark screenshot showing ICMP packets in `outputs/`.
