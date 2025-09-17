# cisco-ccna-miniproject
Cisco Packet Tracer project with OSPF, VLANs, and port-security-Telnet

## Cisco Packet Tracer Project – Features & Key Configuration

This lab demonstrates basic network design and security using Cisco routers and switches.

### Implemented Configuration
- **Hostname**: `R6`
- **Enable Password**: `abi` (with `enable secret abi123` for encrypted privilege access)
- **Service Hardening**
  - `no ip domain-lookup` to prevent unwanted DNS lookups
  - `service password-encryption` to encrypt all plaintext passwords
  - `banner motd # Unauthorized Access Prohibited #`
- **Layer-2 Security**
  - VLAN creation and assignment
  - Port Security with `switchport port-security`, maximum 1, sticky MAC, violation shutdown
- **Routing**
  - OSPF single-area configuration with appropriate network statements
- **Remote Access**
  - Telnet enabled on VTY lines with local user authentication

### File List
- `microsolutions-network-demo.pkt` – Full Packet Tracer topology
- `configs/` – Individual running-config files for routers and switches

Open the `.pkt` file in Cisco Packet Tracer 8.x or later to explore the topology and verify the configuration.

