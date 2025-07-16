# VLAN, Trunking & Routing Practice

## VLAN Configuration
```bash
vlan 10
name SALES
vlan 20
name HR
```

## Assigning Ports
```bash
interface fa0/1
switchport mode access
switchport access vlan 10
```

## Trunking
```bash
interface fa0/24
switchport mode trunk
switchport trunk allowed vlan 10,20
```
