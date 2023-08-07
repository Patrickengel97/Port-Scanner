# Network Port Scanner and Analysis

This document outlines the process of using an advanced IP scanner to scan and analyze the devices on a network. The procedure involves scanning the network, identifying devices, exploring shared folders, and performing basic network operations.

## Overview

Network port scanning is a valuable technique for assessing the devices connected to a network and gaining insights into their configurations.

## Steps

1. **Power On Devices:**
   - Ensure that Device A (Domain Controller) and Device B (Workstation) are powered on.

2. **Network Scanning with Advanced IP Scanner:**
   - Connect to Device B.
   - Open Advanced IP Scanner.

3. **Configure Scan:**
   - Remove the [IP range 1] - [IP range 2] network ID range.
   - The remaining network ID range is [new IP range].
   - Initiate the scan.

4. **Device Identification:**
   - View the list of devices discovered within the range.
   - Identify network devices, including the one with IP address [IP address].
     - Note: This device serves as the default gateway for all devices to reach the internet.

5. **Shared Folders Discovery:**
   - Expand the host information for Device A.
   - Observe the discovery of two shared folders on the device.

6. **Network Testing:**
   - Right-click on Device A.
     - Select "Tools" > "Ping."
   - A command prompt window opens, setting up a ping session between Device B and Device A.

7. **Device Management:**
   - Right-click on Device A.
     - Choose "Advanced" > "Shutdown" > "Reboot."
   - Confirm the reboot operation.

8. **Observations:**
   - Switch to Device A.
   - Observe the indication that the device is about to be rebooted.

## Conclusion

Network port scanning provides valuable insights into the devices and configurations within a network. By using advanced IP scanning tools, network administrators can efficiently manage devices, troubleshoot issues, and ensure smooth network operations.
