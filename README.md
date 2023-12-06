# Jarkom-Modul-4-E20-2023

Laporan Resmi Praktikum Jaringan Komputer Modul 4

# Nama Anggota
1. Mochammad Taslam Gustino Prianto. (5025211011)

# Pembagian Route
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/c747f094-9658-42a3-b89c-9f55661cd4f9)

# Pembagian Subnet
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/22e27a87-896f-4444-aa8b-88dacee40f88)

# Perhitungan CIDR

## Penggabungan CIDR
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/4b40f9b3-fe0f-47d4-a87b-7d503c6c4ece)
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/28db78ff-7bef-42d5-af70-8f12d6a340a0)
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/8b363a12-84dc-402c-8aec-4b88c843e7ea)

## CIDR Tree
![Tree CIDR](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/22eab004-7632-4fec-8758-520214370d82)

## Pembagian IP CIDR
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/108f213c-d92f-4a4b-b39d-ff7384486db9)

## Subnetting
- Aura
```c
# NAT1 (Internet)
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
  address 192.219.128.1
  netmask 255.255.255.252

auto eth2
iface eth2 inet static
  address 192.217.0.1
  netmask 255.255.255.252

auto eth3
iface eth3 inet static
  address 192.218.1.1
  netmask 255.255.255.252
```

- Denken
```c
auto eth0
iface eth0 inet static
  address 192.218.1.2
  netmask 255.255.255.252
  gateway 192.172.1.1

auto eth1
iface eth1 inet static
  address 192.218.0.1
  netmask 255.255.255.0
```

- RoyalCapital
```c
auto eth0
iface eth0 inet static
  address 192.218.0.2
  netmask 255.255.255.0
  gateway 192.218.0.1
```

- WillieRegion
```c
auto eth0
iface eth0 inet static
  address 192.218.0.3
  netmask 255.255.255.0
  gateway 192.218.0.1

```

- Frieren
```c
auto eth0
iface eth0 inet static
  address 192.219.128.2
  netmask 255.255.255.252
  gateway 192.219.128.1

auto eth1
iface eth1 inet static
  address 192.219.64.1
  netmask 255.255.255.224

auto eth2
iface eth2 inet static
  address 192.219.32.1
  netmask 255.255.255.252
```

- LakeKorridor
```c
auto eth0
iface eth0 inet static
  address 192.219.64.2
  netmask 255.255.255.224
  gateway 192.219.64.1
```

- Flamme
```c
auto eth0
iface eth0 inet static
  address 192.219.32.2
  netmask 255.255.255.252
  gateway 192.219.32.1

auto eth1
iface eth1 inet static
  address 192.219.8.1
  netmask 255.255.255.252

auto eth2
iface eth2 inet static
  address 192.219.16.1
  netmask 255.255.252.0

auto eth3
iface eth3 inet static
  address 192.219.20.9
  netmask 255.255.255.252
```

- Fern
```c
auto eth0
iface eth0 inet static
  address 192.219.8.2
  netmask 255.255.255.252
  gateway 192.219.8.1

auto eth1
iface eth1 inet static
  address 192.219.0.1
  netmask 255.255.248.0
```

- LaubHills
```c
auto eth0
iface eth0 inet static
  address 192.219.0.2
  netmask 255.255.248.0
  gateway 192.219.0.1
```

- ApetitRegion
```c
auto eth0
iface eth0 inet static
  address 192.219.0.3
  netmask 255.255.248.0
  gateway 192.219.0.1
```

- RohrRoad
```c
auto eth0
iface eth0 inet static
  address 192.219.16.2
  netmask 255.255.252.0
  gateway 192.219.16.1
```

- Himmel
```c
auto eth0
iface eth0 inet static
  address 192.219.20.10
  netmask 255.255.255.252
  gateway 192.172.0.37

auto eth1
iface eth1 inet static
  address 192.219.20.1
  netmask 255.255.255.248
```

- SchwerMountain 
```c
auto eth0
iface eth0 inet static
  address 192.219.20.2
  netmask 255.255.255.248
  gateway 192.219.20.1
```

- Eisen
```c
auto eth0
iface eth0 inet static
  address 192.217.0.1
  netmask 255.255.255.252
  gateway 192.217.0.2

auto eth1
iface eth1 inet static
  address 192.216.128.1
  netmask 255.255.255.248

auto eth2
iface eth2 inet static
  address 192.216.32.1
  netmask 255.255.255.252

auto eth3
iface eth3 inet static
  address 192.216.72.1
  netmask 255.255.255.252

auto eth4
iface eth4 inet static
  address 192.216.128.9
  netmask 255.255.255.252
```

- Richter
```c
auto eth0
iface eth0 inet static
  address 192.216.128.2
  netmask 255.255.255.248
  gateway 192.216.128.1
```

- Revolte
```c
auto eth0
iface eth0 inet static
  address 192.216.128.3
  netmask 255.255.255.248
  gateway 192.216.128.1
```

- Linie
```c
auto eth0
iface eth0 inet static
  address 192.216.32.2
  netmask 255.255.255.252
  gateway 192.216.32.1

auto eth1
iface eth1 inet static
  address 192.216.8.1
  netmask 255.255.255.252

auto eth2
iface eth2 inet static
  address 192.216.16.1
  netmask 255.255.254.0
```

- Lawine
```c
auto eth0
iface eth0 inet static
  address 192.216.8.2
  netmask 255.255.255.252
  gateway 192.216.8.1

auto eth1
iface eth1 inet static
  address 192.216.4.1
  netmask 255.255.255.192
```

- BredtRegion
```c
auto eth0
iface eth0 inet static
  address 192.216.4.2
  netmask 255.255.255.192
  gateway 192.216.4.1
```

- Heiter
```c
auto eth0
iface eth0 inet static
  address 192.216.4.3
  netmask 255.255.255.192
  gateway 192.216.4.1

auto eth1
iface eth1 inet static
  address 192.216.0.1
  netmask 255.255.252.0
```

- Sein
```c
auto eth0
iface eth0 inet static
  address 192.216.0.2
  netmask 255.255.252.0
  gateway 192.216.0.1
```

- RiegelCanyon
```c
auto eth0
iface eth0 inet static
  address 192.216.0.3
  netmask 255.255.252.0
  gateway 192.216.0.1
```

- GranzChannel
```c
iface eth0 inet static
  address 192.216.16.2
  netmask 255.255.254.0
  gateway 192.216.16.1
```

- Lugner
```c
auto eth0
iface eth0 inet static
  address 192.216.72.2
  netmask 255.255.255.252
  gateway 192.216.72.1

auto eth1
iface eth1 inet static
  address 192.216.64.1
  netmask 255.255.252.0

auto eth2
iface eth2 inet static
  address 192.216.68.1
  netmask 255.255.255.0
```

- TurkRegion
```c
auto eth0
iface eth0 inet static
  address 192.216.64.2
  netmask 255.255.252.0
  gateway 192.216.64.1
```

- GrobeForest
```c
auto eth0
iface eth0 inet static
  address 192.216.68.2
  netmask 255.255.255.0
  gateway 192.216.68.1
```

- Stark
```c
auto eth0
iface eth0 inet static
  address 192.216.128.10
  netmask 255.255.255.252
  gateway 192.216.128.9
```

## Routing

- AURA:

iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 192.216.0.0/14

KANAN
route add -net 192.218.1.0 netmask 255.255.255.252 gw 192.218.1.2
route add -net 192.218.0.0 netmask 255.255.255.0 gw 192.218.1.2

KIRI
route add -net 192.219.128.0 netmask 255.255.255.252 gw 192.219.128.2
route add -net 192.219.64.0 netmask 255.255.255.224 gw 192.219.128.2
route add -net 192.219.32.0 netmask 255.255.255.252 gw 192.219.128.2
route add -net 192.219.8.0 netmask 255.255.255.252 gw 192.219.128.2
route add -net 192.219.0.0 netmask 255.255.248.0 gw 192.219.128.2
route add -net 192.219.16.0 netmask 255.255.252.0 gw 192.219.128.2
route add -net 192.219.20.8 netmask 255.255.255.252 gw 192.219.128.2
route add -net 192.219.20.0 netmask 255.255.255.248 gw 192.219.128.2

BAWAH
route add -net 192.217.0.0 netmask 255.255.255.252 gw 192.217.0.2
route add -net 192.216.128.0 netmask 255.255.255.248 gw 192.217.0.2
route add -net 192.216.32.0 netmask 255.255.255.252 gw 192.217.0.2
route add -net 192.216.8.0 netmask 255.255.254.0 gw 192.217.0.2
route add -net 192.216.4.0 netmask 255.255.255.252 gw 192.217.0.2
route add -net 192.216.0.0 netmask 255.255.252.0 gw 192.217.0.2
route add -net 192.216.16.0 netmask 255.255.252.0 gw 192.217.0.2
route add -net 192.216.72.0 netmask 255.255.255.252 gw 192.217.0.2
route add -net 192.216.64.0 netmask 255.255.255.0 gw 192.217.0.2
route add -net 192.216.68.0 netmask 255.255.252.0 gw 192.217.0.2
route add -net 192.216.128.8 netmask 255.255.255.252 gw 192.217.0.2

- FRIEREN:

ATAS
route add -net 192.219.64.0 netmask 255.255.255.224 gw 192.219.64.2

KIRI
route add -net 192.219.32.0 netmask 255.255.255.252 gw 192.219.32.1
route add -net 192.219.8.0 netmask 255.255.255.252 gw 192.219.32.1
route add -net 192.219.0.0 netmask 255.255.248.0 gw 192.219.32.1
route add -net 192.219.16.0 netmask 255.255.252.0 gw 192.219.32.1
route add -net 192.219.20.8 netmask 255.255.255.252 gw 192.219.32.1
route add -net 192.219.20.0 netmask 255.255.255.248 gw 192.219.32.1

- FLAMME:

ATAS
route add -net 192.219.8.0 netmask 255.255.255.252 gw 192.219.8.2
route add -net 192.219.0.0 netmask 255.255.248.0 gw 192.219.8.2

KIRI
route add -net 192.219.16.0 netmask 255.255.252.0 gw 192.219.20.9

BAWAH
route add -net 192.219.20.8 netmask 255.255.255.252 gw 192.219.20.10
route add -net 192.219.20.0 netmask 255.255.255.248 gw 192.219.20.10

- FERN:

route add -net 192.219.0.0 netmask 255.255.248.0 gw 192.219.0.1

- HIMMEL:

route add -net 192.219.20.0 netmask 255.255.255.248 gw 192.219.20.1

- EISEN:

KIRI
route add -net 192.216.128.0 netmask 255.255.255.248 gw 10.47.0.49

BAWAH
route add -net 192.216.32.0 netmask 255.255.255.252 gw 192.216.128.1
route add -net 192.216.8.0 netmask 255.255.254.0 gw 192.216.128.1
route add -net 192.216.4.0 netmask 255.255.255.252 gw 192.216.128.1
route add -net 192.216.0.0 netmask 255.255.252.0 gw 192.216.128.1
route add -net 192.216.16.0 netmask 255.255.252.0 gw 192.216.128.1

KANAN
route add -net 192.216.72.0 netmask 255.255.255.252 gw 192.216.32.1
route add -net 192.216.64.0 netmask 255.255.255.0 gw 192.216.32.1
route add -net 192.216.68.0 netmask 255.255.252.0 gw 192.216.32.1

KANAN-ATAS
route add -net 192.216.128.8 netmask 255.255.255.252 gw 192.216.72.1

- LUGNER:

route add -net 192.216.64.0 netmask 255.255.255.0 gw 192.216.68.1
route add -net 192.216.68.0 netmask 255.255.252.0 gw 192.216.64.1

- LINIE:

BAWAH 
route add -net 192.216.16.0 netmask 255.255.254.0 gw 192.216.16.1

KIRI
route add -net 192.216.8.0 netmask 255.255.254.0 gw 192.216.8.1
route add -net 192.216.4.0 netmask 255.255.255.252 gw 192.216.8.1
route add -net 192.216.0.0 netmask 255.255.252.0 gw 192.216.8.1

- LAWINE:

route add -net 192.216.4.0 netmask 255.255.255.252 gw 192.216.4.1
route add -net 192.216.0.0 netmask 255.255.252.0 gw 192.216.4.1

- HEITER:

route add -net 192.216.0.0 netmask 255.255.252.0 gw 192.216.0.1

- DENKEN:

route add -net 192.218.0.0 netmask 255.255.255.0 gw 192.218.0.1

# VLSM

## VLSM Tree
![Tree VLSM](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/5d9a84bd-d227-434d-b25f-831044f8e15c)

## Pembagian IP
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/4d0bfdef-a712-41ab-8a74-f1fb94fc641c)

## Subnetting
- Subnet A1
  Aura
  - IP : 192.216.1.1
  - Netmask : 255.255.255.252
  Frieren
  - IP : 192.216.1.2
  - Netmask : 255.255.255.252
- Subnet A2
  Frieren
  - IP : 192.216.1.65
  - Netmask : 255.255.255.224
  LakeKorridor
  - IP : 192.216.1.66
  - Netmask : 255.255.255.224
- Subnet A3
  Frieren
  - IP : 192.216.1.5
  - Netmask : 255.255.255.252
  Flamme
  - IP : 192.216.1.6
  - Netmask : 255.255.255.252
- Subnet A4
  Flamme
  - IP : 192.216.1.9
  - Netmask : 255.255.255.252
  Fern
  - IP : 192.216.1.10
  - Netmask : 255.255.255.252
- Subnet A5
  Fern
  - IP : 192.216.25.1
  - Netmask : 255.255.248.0
  LaubHills
  - IP : 192.216.25.2
  - Netmask : 255.255.248.0
  AppetitRegion
  - IP : 192.216.25.3
  - Netmask : 255.255.248.0
- Subnet A6
  Flamme
  - IP : 192.216.9.1
  - Netmask : 255.255.252.0
  RohrRoad
  - IP : 192.216.9.2
  - Netmask : 255.255.252.0
- Subnet A7
  Flamme
  - IP : 192.216.1.12
  - Netmask : 255.255.255.252
  Himmel
  - IP : 192.216.1.13
  - Netmask : 255.255.255.252
- Subnet A8
  Himmel
  - IP : 192.216.20.41
  - Netmask : 255.255.255.248
  SchweMountains
  - IP : 192.216.20.42
  - Netmask : 255.255.255.248
- Subnet A9
  Aura
  - IP : 192.216.1.17
  - Netmask : 255.255.255.252
  Eisen
  - IP : 192.216.1.18
  - Netmask : 255.255.255.252
- Subnet A10
  Eisen
  - IP : 192.216.1.49
  - Netmask : 255.255.255.248
  Richter
  - IP : 192.216.1.50
  - Netmask : 255.255.255.248
  Revolte
  - IP : 192.216.1.51
  - Netmask : 255.255.255.248
- Subnet A11
  Eisen
  - IP : 192.216.1.21
  - Netmask : 255.255.255.252
  Linie
  - IP : 192.216.1.22
  - Netmask : 255.255.255.252
- Subnet A12
  Linie
  - IP : 192.216.1.25
  - Netmask : 255.255.255.252
  Lawine
  - IP : 192.216.1.26
  - Netmask : 255.255.255.252
- Subnet A13
  Lawine
  - IP : 192.216.1.129
  - Netmask : 255.255.255.192
  BredthRegion
  - IP : 192.216.1.130
  - Netmask : 255.255.255.192
  Heiter
  - IP : 192.216.1.131
  - Netmask : 255.255.252.0
- Subnet A14
  Heiter
  - IP : 192.216.13.1
  - Netmask : 255.255.252.0
  Sein
  - IP : 192.216.13.2
  - Netmask : 255.255.252.0
  RiegeCanyon
  - IP : 192.216.13.3
  - Netmask : 255.255.252.0
- Subnet A15
  Linie
  - IP : 192.216.5.1
  - Netmask : 255.255.254.0
  GranzChannel
  - IP : 192.216.5.2
  - Netmask : 255.255.254.0
- Subnet A16
  Eisen
  - IP : 192.216.1.29
  - Netmask : 255.255.255.252
  Lugner
  - IP : 192.216.1.30
  - Netmask : 255.255.255.252
- Subnet A17
  Lugner
  - IP : 192.216.17.1
  - Netmask : 255.255.252.0
  TurkRegion
  - IP : 192.216.17.2
  - Netmask : 255.255.252.0
- Subnet A18
  Lugner
  - IP : 192.216.2.1
  - Netmask : 255.255.255.0
  GrobeForest
  - IP : 192.216.2.2
  - Netmask : 255.255.255.0
- Subnet A19
  Eisen
  - IP : 192.216.1.33
  - Netmask : 255.255.255.252
  Stark
  - IP : 192.216.1.34
  - Netmask : 255.255.255.252
- Subnet A20
  Aura
  - IP : 192.218.1.37
  - Netmask : 255.255.255.252
  Denken
  - IP : 192.218.1.38
  - Netmask : 255.255.255.252
- Subnet A21
  Denken
  - IP : 192.218.3.1
  - Netmask : 255.255.255.0
  RoyalCapital
  - IP : 192.218.3.2
  - Netmask : 255.255.255.0
  WillieRegion
  - IP : 192.218.3.3
  - Netmask : 255.255.255.0

 ## Routing

 - Router Aura
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/ca9382e9-214a-4dac-a903-148219027858)
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/adedda00-147a-4b8b-b9cc-c077d65657f2)
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/40febe34-b557-4bae-bcb8-a20fb4a3bd85)

- Router Denken
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/adf181f5-424e-4c1d-bfdc-93bbfd077ab8)

- Router Frieren
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/32bed670-c48f-483e-b1d2-0b445a8c4ce6)

- Router Flamme
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/82151a3e-9ca2-4851-83ef-38f545d57310)

- Router Fern
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/705affc8-f39a-497c-a0e4-ab98ebcdce61)

- Router Himmel
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/c29e8fcd-9b8d-442b-ae69-b2365c5700fc)

- Router Eisen
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/0063dae4-eb16-4d53-91f9-9f8f53744cb3)

- Router Lugner
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/b9911824-fabc-4b67-b49b-f0ed4d746993)

- Router Linie
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/06459476-c681-4548-b032-5e1e903b70cf)

- Router Lawine
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/27d0734e-c828-4ef5-846f-d267a78392b6)

- Router Heiter
![image](https://github.com/gustino7/Jarkom-Modul-4-E20-2023/assets/93267604/5cec0d5d-8c2e-4023-8db9-482462f58388)
