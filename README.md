# Task 5: Wireshark Network Traffic Capture

## Objective
Capture and analyze live network traffic using Wireshark and identify at least 3 different protocols.

## Tools Used
- **Wireshark** (latest version)
- **Browser** (Chrome/Firefox)
- **Command Line** (`ping` command)

## Steps Followed

1. **Installed Wireshark** and selected the active network interface (Wi-Fi).
2. **Started live capture** by clicking the shark icon.
3. **Generated traffic**:
   - Opened `google.com` in the browser.
   - Ran `ping google.com` in terminal.
4. **Stopped capture** after ~1 minute.
5. **Filtered packets** by protocols using:
   - `http`
   - `dns`
   - `tcp`
6. **Identified protocols** and saved the capture as `task5_capture.pcap`.

## Protocols Identified

| Protocol | Description | Filter Used |
|----------|-------------|-------------|
| TCP | Ensures reliable communication between systems | `tcp` |
| HTTP | Used to browse web pages | `http` |
| DNS | Resolves domain names to IPs | `dns` |

## Files Included

- `task5_capture.pcap` - Packet capture file.
- `report_task5.pdf` - Detailed protocol analysis report.
- `screenshots/` (optional) - Screenshots of filtered packets.

## Outcome
I learned how to capture, filter, and analyze live network traffic, and gained familiarity with real-time protocol inspection.
