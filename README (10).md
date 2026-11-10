# Experiment 15 — Wireshark filter expressions

## Capture filters (set before starting capture)
```text
host 192.168.1.10
net 192.168.1.0/24
src host 192.168.1.10
dst port 53
tcp port 443
udp
```

## Display filters (apply after/during capture)
```text
ip.addr == 192.168.1.10
ip.src == 192.168.1.10
tcp.port == 80
dns
icmp
http.request.method == "GET"
tcp.flags.syn == 1 && tcp.flags.ack == 0
```

**Output evidence:** Screenshot the applied filter and matching packets. Replace sample addresses with values appropriate to your lab network.
