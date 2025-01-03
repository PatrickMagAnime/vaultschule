[[3.Nwt]]
___
R1:
int g0/0/1
no shutdown
int g0/0/1.10
encapsulation dot1q 10
ip addr 192.168.10.1 255.255.55.0
int g0/0/1.20
enc dot1q 20
ip addr 192.168.20.1 255.255.55.0
nt g0/0/1.99
enc dot1q 99 (native)
ip addr 192.168.99.1 255.255.55.0
___
S1:
vlan 10
vlan 20
vlan 99
int range fa0/1 fa0/5
switchport mode trunk
switchport trunk native vlan 99
switchport allowed vlan 10,20,99
int fa0/6
switch port mode access
switch access vlan 10
___
enable
conf t
ip interface 0/2
switchport trunk nat
switchport trunk
______________________
enable conf t
interface f0/0
no shut
encapsulation dot 1 q
ip adress 192.168.10.1 255.255.255.0      (Das selbe auch noch bei pc 2)
___
enable conf t
interface f0/0
no shut
encapsulation dot 1 q
ip adress 192.168.20.1 255.255.255.0  
___
Jetzt können diese in einem Netzwerk miteinander Komunizieren.
Default gateway anpingen nicht vergessen
___
