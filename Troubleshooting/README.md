Network Troubleshooting

This section contains my hands-on CCNA troubleshooting labs focused on identifying, isolating, and resolving common network connectivity and configuration issues.

## Troubleshooting Areas

- Interface and Link Issues
- IP Addressing Errors
- Subnet Mask Errors
- Default Gateway Issues
- VLAN Configuration Issues
- Trunking Problems
- Inter-VLAN Routing Issues
- STP Issues
- Routing Table Problems
- OSPF Neighbor Issues
- DHCP Problems
- NAT Problems
- ACL-Related Connectivity Issues
- DNS Connectivity Issues
- Basic Cisco IOS Troubleshooting

## Lab Environment

### Physical Hardware
- Cisco 1841 Routers
- Cisco Catalyst 3550 Series Switches

### Virtual Labs
- GNS3
- Cisco Packet Tracer

## Troubleshooting Methodology

1. Identify the problem
2. Check physical and interface status
3. Verify IP addressing
4. Check VLAN and trunk configuration
5. Check the MAC address table
6. Check the routing table
7. Verify routing protocols
8. Test connectivity
9. Isolate the root cause
10. Apply and verify the solution

## Common Verification Commands

```text
show ip interface brief
show interfaces
show vlan brief
show interfaces trunk
show mac address-table
show spanning-tree
show ip route
show ip protocols
show ip ospf neighbor
show ip dhcp binding
show ip nat translations
show access-lists
ping
traceroute
