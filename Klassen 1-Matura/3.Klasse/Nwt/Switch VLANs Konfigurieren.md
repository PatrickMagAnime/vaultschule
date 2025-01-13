[[3.Nwt]]
___
## R1 Konfiguration:
````c
R1:
int g0/0/1
no shutdown
int g0/0/1.10
encapsulation dot1q 10
ip addr 192.168.10.1 255.255.55.0
int g0/0/1.20
enc dot1q 20
ip addr 192.168.20.1 255.255.55.0
int g0/0/1.99
enc dot1q 99 (native)
ip addr 192.168.99.1 255.255.55.0
````
## S1 Konfiguration:

````c
S1:
vlan 10
vlan 20
vlan 99
int range fa0/1 - 5
switchport mode trunk
switchport trunk native vlan 99
switchport trunk allowed vlan 10,20,99
int fa0/6
switchport mode access
switchport access vlan 10
````
## Zusätzliche Befehle:

````c
enable
conf t
interface fa0/2
switchport trunk native vlan 99
switchport mode trunk
````

## Beispiel PC-Konfiguration:

````c
enable
conf t
interface f0/0
no shutdown
encapsulation dot1q
ip address 192.168.10.1 255.255.255.0
````

(Das selbe auch noch bei PC 2 mit entsprechender IP-Adresse)
## Weiteres PC-Konfigurationsbeispiel:

````c
enable
conf t
interface f0/0
no shutdown
encapsulation dot1q
ip address 192.168.20.1 255.255.255.0
````