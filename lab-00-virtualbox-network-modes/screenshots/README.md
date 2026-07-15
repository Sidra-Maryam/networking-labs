## Screenshots & Evidence

This directory contains the complete compilation of raw terminal and GUI screenshots captured during the empirical testing phase of this lab.These images serve as verified verification of network configurations, routing tables, and interface states.

## 📁 Directory Structure

The screenshots are organized systematically by the specific networking mode under evaluation:

```text
screenshots/
├── nat/              # Evidence for Mode 1: Standard NAT behavior (isolated VM bubbles)
├── nat-network/      # Evidence for Mode 2: Shared NAT network environment
├── bridged/          # Evidence for Mode 3: Physical LAN integration peer tracking
├── host-only/        # Evidence for Mode 4: Host-to-VM loopbacks & DHCP validation
└── internal-network/ # Evidence for Mode 5: Pure intra-VM isolation (static configurations)
