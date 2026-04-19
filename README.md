*This project has been created as part of the 42 curriculum by cgross-s.*

# NetPractice

## Description
NetPractice is a practical networking training project from the 42 curriculum.

The goal is to understand and apply core TCP/IP networking concepts by fixing misconfigured network diagrams in a browser-based simulator. Across 10 levels, you configure IP addresses, subnet masks, and default gateways, and verify connectivity between hosts and routers.

This repository stores exported configuration files for all mandatory levels and a short reference guide used during practice.

## Instructions
### 1. Start the training interface
From the project folder, run:

```bash
cd net_practice
./run.sh
```

If needed, you can start it manually:

```bash
cd net_practice
python3 -m http.server 49242
```

Then open:

http://localhost:49242

### 2. Solve each level
- Enter your login in the training interface.
- Complete each network objective by editing only allowed fields.
- Use Check again to validate your solution.

### 3. Export configurations
- After completing each level, click Get my config.
- Save one exported file per level.

### 4. Submission requirements
- Submit exactly 10 exported configuration files (one per level).
- Place all 10 files at the repository root.
- Ensure filenames match what the platform/evaluation expects.
- During peer evaluation, you must be able to solve random levels without external tools.

## Conversion Subnetting Table
| CIDR | Addresses | Hosts | Netmask         |
|------|-----------|-------|-----------------|
| /30  | 4         | 2     | 255.255.255.252 |
| /29  | 8         | 6     | 255.255.255.248 |
| /28  | 16        | 14    | 255.255.255.240 |
| /27  | 32        | 30    | 255.255.255.224 |
| /26  | 64        | 62    | 255.255.255.192 |
| /25  | 128       | 126   | 255.255.255.128 |
| /24  | 256       | 254   | 255.255.255.0   |
| /23  | 512       | 510   | 255.255.254.0   |
| /22  | 1024      | 1022  | 255.255.252.0   |
| /21  | 2048      | 2046  | 255.255.248.0   |
| /20  | 4096      | 4094  | 255.255.240.0   |
| /19  | 8192      | 8190  | 255.255.224.0   |
| /18  | 16384     | 16382 | 255.255.192.0   |
| /17  | 32768     | 32766 | 255.255.128.0   |
| /16  | 65536     | 65534 | 255.255.0.0     |

## Resources
### Networking references
- RFC 791 (Internet Protocol)
- RFC 950 (Internet Standard Subnetting Procedure)
- RFC 4632 (Classless Inter-domain Routing)
- Subnetting reference sheet: https://www.aelius.com/njh/subnet_sheet.html
- Cisco IP addressing and subnetting guides

### Concepts studied in this project
- TCP/IP addressing
- Subnet masks and CIDR notation
- Default gateway behavior
- Router vs switch roles
- Broadcast and network addresses
- OSI layers (especially Layers 2 and 3)
