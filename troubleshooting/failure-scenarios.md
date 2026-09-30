# Failure Scenarios & Troubleshooting

This document records the 6 intentional failures practiced during the lab and how they were resolved using NOC methodology.

---

## FAILURE 1: Wrong Access VLAN

**How Introduced**  
```cisco
interface FastEthernet0/1
 switchport access vlan 20