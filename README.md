# Task 5: Wireshark Network Traffic Capture

## Objective
Capture and analyze live network traffic using Wireshark and identify at least 3 different protocols.

## Tools Used
- **Wireshark** (latest version)
- **Browser** (Chrome/Firefox)
- **Command Line** (`ping` command)

## Steps Followed

1. **Installed Wireshark** and selected the active network interface (Wi-Fi).
![image](https://github.com/user-attachments/assets/a94781ff-f4c9-4d91-9bb0-f565246ab907)
2. **Started live capture** by clicking the shark icon.
![image](https://github.com/user-attachments/assets/7542d475-219e-4eda-b108-1411a3a6d7d4)
4. **Generated traffic**:
   - Opened `google.com` in the browser.
   - Ran `ping google.com` in terminal.
5. **Stopped capture** after ~1 minute.
6. **Filtered packets** by protocols using:
   - `http`
![image](https://github.com/user-attachments/assets/24bdbc2a-46f7-4b75-8aab-6d58f79370d2)
   - `dns`
![image](https://github.com/user-attachments/assets/e8846606-d39a-4cb8-b7c7-136f9c81a366)
   - `tcp`
![image](https://github.com/user-attachments/assets/e57d1c76-cd6d-4680-b45d-1aab32522c41)

7. **Identified protocols** and saved the capture as `task5_Capture.pcap`.

## Protocols Identified

| Protocol | Description | Filter Used |
|----------|-------------|-------------|
| TCP | Ensures reliable communication between systems | `tcp` |
| HTTP | Used to browse web pages | `http` |
| DNS | Resolves domain names to IPs | `dns` |

## Files Included

- `task5_Capture.pcap` - Packet capture file.
- `report_task5.md` - Detailed protocol analysis report.

## Outcome
I learned how to capture, filter, and analyze live network traffic, and gained familiarity with real-time protocol inspection.
