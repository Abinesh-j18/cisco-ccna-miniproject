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

<img width="1677" height="893" alt="1" src="https://github.com/user-attachments/assets/c4c0bb24-6229-4d74-8441-afefe4f38e5f" />

<img width="1666" height="924" alt="2" src="https://github.com/user-attachments/assets/409ec1d2-076b-4f29-87f5-2d25f36b7740" />

<img width="1657" height="870" alt="3" src="https://github.com/user-attachments/assets/7512f347-cfa6-4161-8bc6-790ed23de220" />

<img width="1679" height="1002" alt="4" src="https://github.com/user-attachments/assets/86c679d3-0a56-4166-8395-2dfd78c095d8" />

<img width="1672" height="927" alt="5" src="https://github.com/user-attachments/assets/ac807419-f875-4fea-ae62-8087a31ddcc9" />



