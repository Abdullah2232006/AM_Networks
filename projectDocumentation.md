# Table of Contents

1. Project description, objectives
2. Current / Final Topology
3. IP mapping
4. Firewall policies rules
5. Step-by-Step Implementation Guide - explained for someone else
6. Testing, Verification, & Troubleshooting Proofs
7. Lessons Learned & Future Enhancements

# Current Topology

![Goal Terminology](media/currentTopology.png)

# IP Mapping

## Port 1

- Alias: WAN
- Role: WAN port
- IP:
    - Gets it's IP address from a DHCP server
    - Connected directly to the home router as a seperate device
- Administrative Access: https, ssh, ping
- DHCP server: none
- Distance: 5

## Port 3

- Alias: Management
- Role: Undefined
- IP:
    - 192.168.68.222 - VMNet8
- Administrative Access: https, http, ssh, ping
- DHCP server: none
- Distance: 5