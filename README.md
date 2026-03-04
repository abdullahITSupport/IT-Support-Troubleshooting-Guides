# Network Connection Troubleshooting Guide

**Issue:** User unable to connect to the network or limited connectivity.

### 1. Initial Assessment
* Verify physical connection (Ethernet cable integrity).
* Check status lights on the NIC (Network Interface Card).

### 2. Diagnostic Steps
Execute the following commands in CMD (Command Prompt) with admin privileges:
- **`ipconfig /release`**: Releases current IP address.
- **`ipconfig /renew`**: Requests a new IP from the DHCP server.
- **`ipconfig /flushdns`**: Clears DNS cache to resolve connectivity issues.
- **`ping 8.8.8.8`**: Checks external internet connectivity.

### 3. Resolution
If ping fails to local gateway, check router configurations and switch ports.

### 4. Verification
Re-run `ping` and open a web browser to confirm access.
