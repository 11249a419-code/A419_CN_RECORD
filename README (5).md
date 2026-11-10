# Experiment 03 — HTTP client using TCP sockets

**Aim:** Download a local web response using TCP sockets.

Terminal 1:
```bash
py http_server.py
```
Terminal 2:
```bash
py http_client.py
```
Use `python3` instead of `py` on Ubuntu/Linux. Run the server before the client.

**Expected output:** Client prints an `HTTP/1.1 200 OK` response and the HTML body. This is a local demonstration server, so it does not require external internet access.
