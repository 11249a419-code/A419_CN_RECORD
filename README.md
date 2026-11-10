# Computer Networks Lab — SCSVMV (2026–2027)

Computer Networks Lab repository arranged for GitHub upload, based on **Dr. T. Dinesh Kumar's Computer Networks Lab Manual**.

## Experiments

| No. | Experiment |
|---:|---|
| 01 | Network commands and capture ping/traceroute packets |
| 02 | Identify machine hostname and IP address |
| 03 | HTTP client using TCP sockets |
| 04 | TCP Echo client and server |
| 05 | TCP Chat application |
| 06 | TCP File transfer |
| 07 | ARP/RARP simulation |
| 08 | Study of NS2 |
| 09 | Congestion control simulation using NS2 |
| 10 | TCP/UDP performance using NS2 |
| 11 | Distance Vector Routing using NS2 |
| 12 | Link State Routing using NS2 |
| 13 | Obtain local DNS server hostname and IP address |
| 14 | CRC error detection |
| 15 | Wireshark capture filters |
| 16 | RTP delay/loss analysis in Wireshark |
| 17 | Inspect packets using Wireshark |
| 18 | Simple LAN using Cisco Packet Tracer |
| 19 | Benchmark LAN Trainer Kit topologies |

## Folder structure

Each experiment folder has a `README.md` describing the aim, how to run/do the experiment, and what output evidence to save. Runnable source files are included where appropriate. The `outputs/` folder contains the NAM screenshots supplied for Experiments 9–12.

## Run Python programs

Use Python 3. For Windows, run `py filename.py`; for Ubuntu/Linux, run `python3 filename.py`.

Some experiments need two terminals (for example, client/server programs). Start the server first, then start the client in a second terminal.

## Output authenticity

The included images for Experiments 9–12 are the screenshots supplied for this repository. Text files named `sample_output.txt` are examples of the expected style of output, not screenshots or measurements from your own machine. For Wireshark, Packet Tracer, and physical LAN Trainer Kit experiments, capture your own screenshots/photos and add them to the matching `outputs/` folder before submission.

## Tools

- Python 3
- NS2 and NAM (Experiments 8–12)
- Wireshark (Experiments 1, 15–17)
- Cisco Packet Tracer (Experiment 18)
- Benchmark LAN Trainer Kit (Experiment 19)
