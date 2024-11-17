# Jarkom-Modul-4-IT36-2024

## Laporan Resmi Modul 4 : Subneting & Routing

### IT36

| Nama                        | NRP           |
|-----------------------------|---------------|
| Fico Simhanandi                | 5027231030   |
| Agnes Zenobia Griselda Petrina | 5027231034    |

# CPT - VLSM

### Topologi

![topo-cpt-modul4](https://github.com/user-attachments/assets/551cfd95-ce19-43dd-a21e-f43a0be6b1e3)

### Rute

![Route](https://github.com/user-attachments/assets/1800c614-e537-456a-87fd-cc42b43c593d)

### Pembagian IP - VLSM

![Pembagian IP](https://github.com/user-attachments/assets/996a62cd-a02b-44bf-9062-67d69ef6d71f)

![Section 1](https://github.com/user-attachments/assets/8633c8bd-9b7b-4c36-ae41-405b8c0a8c65)

### Konfigurasi CPT - VLSM

## For HoloLive

### Interfaces
```
Fast Ethernet1/0 (A8)
- IPv4 Address  : 10.81.19.81
- Subnet Mask   : 255.255.255.252

Fast Ethernet1/1 (A9)
- IPv4 Address  : 10.81.19.85
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/1 (A16)
- IPv4 Address  : 10.81.19.101
- Subnet Mask   : 255.255.255.252
```

### Static route
```
(A1)
10.81.18.128/26 via 10.81.19.82

Network: 10.81.18.128
Mask: 255.255.255.192
Next Hop: 10.81.19.82

(A2)
10.81.19.48/29 via 10.81.19.82

Network: 10.81.19.48
Mask: 255.255.255.248
Next Hop: 10.81.19.82

(A3)
10.81.19.56/29 via 10.81.19.82

Network: 10.81.19.56
Mask: 255.255.255.248
Next Hop: 10.81.19.82

(A4)
10.81.12.0/23 via 10.81.19.82

Network: 10.81.12.0
Mask: 255.255.254.0
Next Hop: 10.81.19.82

(A5)
10.81.19.72/30 via 10.81.19.82

Network: 10.81.19.72
Mask: 255.255.255.252
Next Hop: 10.81.19.82

(A6)
10.81.19.76/30 via 10.81.19.82

Network: 10.81.19.76
Mask: 255.255.255.252
Next Hop: 10.81.19.82

(A7)
10.81.19.0/27 via 10.81.19.82

Network: 10.81.19.0
Mask: 255.255.255.224
Next Hop: 10.81.19.82

(A10)
10.81.19.88/30 via 10.81.19.86

Network: 10.81.19.88
Mask: 255.255.255.252
Next Hop: 10.81.19.86

(A11)
10.81.8.0/22 via 10.81.19.86

Network: 10.81.8.0
Mask: 255.255.252.0
Next Hop: 10.81.19.86

(A12)
10.81.19.92/30 via 10.81.19.86

Network: 10.81.19.92
Mask: 255.255.255.252
Next Hop: 10.81.19.86

(A13)
10.81.18.192/26 via 10.81.19.86

Network: 10.81.18.192
Mask: 255.255.255.192
Next Hop: 10.81.19.86

(A14)
10.81.19.96/30 via 10.81.19.86

Network: 10.81.19.96
Mask: 255.255.255.252
Next Hop: 10.81.19.86

(A15)
10.81.16.0/23 via 10.81.19.86

Network: 10.81.16.0
Mask: 255.255.254.0
Next Hop: 10.81.19.86

(A17)
10.81.19.64/29 via 10.81.19.102

Network: 10.81.19.64
Mask: 255.255.255.248
Next Hop: 10.81.19.102

(A18)
10.81.19.32/28 via 10.81.19.102

Network: 10.81.19.32
Mask: 255.255.255.240
Next Hop: 10.81.19.102

(A19)
10.81.0.0/21 via 10.81.19.102

Network: 10.81.0.0
Mask: 255.255.248.0
Next Hop: 10.81.19.102

(A20)
10.81.14.0/23 via 10.81.19.102

Network: 10.81.14.0
Mask: 255.255.254.0
Next Hop: 10.81.19.102

(A21)
10.81.19.104/30 via 10.81.19.102

Network: 10.81.19.104
Mask: 255.255.255.252
Next Hop: 10.81.19.102

(A22)
10.81.18.0/25 via 10.81.19.102

Network: 10.81.18.0
Mask: 255.255.255.128
Next Hop: 10.81.19.102
```

## For Holo-EN

### Interfaces
```
Fast Ethernet0/1 (A5)
- IPv4 Address  : 10.81.19.73
- Subnet Mask   : 255.255.255.252

Fast Ethernet1/0 (A6)
- IPv4 Address  : 10.81.19.77
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/0 (A8)
- IPv4 Address  : 10.81.19.82
- Subnet Mask   : 255.255.255.252
```

### Static route
```
Default (HoloLive)
0.0.0.0/0 via 10.81.19.81

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.81

(A1)
10.81.18.128/26 via 10.81.19.74

Network: 10.81.18.128
Mask: 255.255.255.192
Next Hop: 10.81.19.74

(A2)
10.81.19.48/29 via 10.81.19.74

Network: 10.81.19.48
Mask: 255.255.255.248
Next Hop: 10.81.19.74

(A3)
10.81.19.56/29 via 10.81.19.74

Network: 10.81.19.56
Mask: 255.255.255.248
Next Hop: 10.81.19.74

(A4)
10.81.12.0/23 via 10.81.19.74

Network: 10.81.12.0
Mask: 255.255.254.0
Next Hop: 10.81.19.74

(A7)
10.81.19.0/27 via 10.81.19.78

Network: 10.81.19.0
Mask: 255.255.255.224
Next Hop: 10.81.19.78
```
## For Holo-Myth

### Interfaces
```
Fast Ethernet0/1 (A2)
- IPv4 Address  : 10.81.19.49
- Subnet Mask   : 255.255.255.248

Fast Ethernet1/0 (A4)
- IPv4 Address  : 10.81.12.1
- Subnet Mask   : 255.255.254.0

Fast Ethernet0/0 (A5)
- IPv4 Address  : 10.81.19.74
- Subnet Mask   : 255.255.255.252
```

### Static route
```
Default (Holo-EN)
0.0.0.0/0 via 10.81.19.73

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.73

(A1)
10.81.18.128/26 via 10.81.19.50

Network: 10.81.18.128
Mask: 255.255.255.192
Next Hop: 10.81.19.50

(A3)
10.81.19.56/29 via 10.81.19.51

Network: 10.81.19.56
Mask: 255.255.255.248
Next Hop: 10.81.19.51
```
## For Gura_Ame_Ina
```
IPv4 Address 10.81.12.2
Netmask 255.255.254.0
Default Gateway 10.81.12.1
```
## For Kiara_Calli
```
IPv4 Address 10.81.12.3
Netmask 255.255.254.0
Default Gateway 10.81.12.1
```
## For Project-Hope

### Interfaces
```
Fast Ethernet0/0 (A2)
- IPv4 Address  : 10.81.19.51
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/1 (A3)
- IPv4 Address  : 10.81.19.57
- Subnet Mask   : 255.255.255.248

```

### Static route
```
Default (Holo-Myth)
0.0.0.0/0 via 10.81.19.49

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.49
```
## For Tys
```
IPv4 Address 10.81.18.58
Netmask 255.255.255.248
Default Gateway 10.81.19.57
```
## For Holo-Council

### Interfaces
```
Fast Ethernet0/1 (A1)
- IPv4 Address  : 10.81.18.129
- Subnet Mask   : 255.255.255.192

Fast Ethernet0/0 (A2)
- IPv4 Address  : 10.81.19.50
- Subnet Mask   : 255.255.255.248
```

### Static route
```
Default (Holo-Myth)
0.0.0.0/0 via 10.81.19.49

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.49
```
## For Kronii_Mumei
```
IPv4 Address 10.81.18.130
Netmask 255.255.255.192
Default Gateway 10.81.18.129
```
## For Bae_Fauna
```
IPv4 Address 10.81.18.131
Netmask 255.255.255.192
Default Gateway 10.81.18.129
```
## For Holo-Advent
(Default to Holo-EN)
ip route 0.0.0.0 0.0.0.0 10.81.19.77

## For FuwaMoco
```
IPv4 Address 10.81.19.2
Netmask 255.255.255.224
Default Gateway 10.81.19.1
```
## For Shiori_Nerissaa
```
IPv4 Address 10.81.19.3
Netmask 255.255.255.224
Default Gateway 10.81.19.1
```
## For Biboo
```
IPv4 Address 10.81.19.4
Netmask 255.255.255.224
Default Gateway 10.81.19.1
```
## For Holo-ID

### Interfaces
```
Fast Ethernet0/0 (A9)
- IPv4 Address  : 10.81.19.86
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/1 (A10)
- IPv4 Address  : 10.81.19.89
- Subnet Mask   : 255.255.255.252

Fast Ethernet1/0 (A11)
- IPv4 Address  : 10.81.19.93
- Subnet Mask   : 255.255.255.252

Fast Ethernet1/1 (A12)
- IPv4 Address  : 10.81.19.97
- Subnet Mask   : 255.255.255.252
```

### Static route
```
Default (Holo-Live)
0.0.0.0/0 via 10.81.19.85

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.85

(A11)
10.81.8.0/22 via 10.81.19.90

Network: 10.81.8.0
Mask: 255.255.252.0
Next Hop: 10.81.19.90

(A13)
10.81.18.192/26 via 10.81.19.94

Network: 10.81.18.192
Mask: 255.255.255.192
Next Hop: 10.81.19.94

(A15)
10.81.16.0/23 via 10.81.19.98

Network: 10.81.16.0
Mask: 255.255.254.0
Next Hop: 10.81.19.98
```
## For Area15

### Interfaces
```
Fast Ethernet0/0 (A10)
- IPv4 Address  : 10.81.19.90
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/1 (A11)
- IPv4 Address  : 10.81.8.1
- Subnet Mask   : 255.255.252.0
```

### Static route
```
Default (Holo-ID)
0.0.0.0/0 via 10.81.19.89

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.89
```
## For Risu
```
IPv4 Address 10.81.8.2
Netmask 255.255.252.0
Default Gateway 10.81.8.1
```
## For Moona
```
IPv4 Address 10.81.8.3
Netmask 255.255.252.0
Default Gateway 10.81.8.1
```
## For Iofi
```
IPv4 Address 10.81.8.4
Netmask 255.255.252.0
Default Gateway 10.81.8.1
```
## For Holoro

### Interfaces
```
Fast Ethernet0/0 (A12)
- IPv4 Address  : 10.81.19.94
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/1 (A13)
- IPv4 Address  : 10.81.18.193
- Subnet Mask   : 255.255.255.192
```

### Static route
```
Default (Holo-ID)
0.0.0.0/0 via 10.81.19.93

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.93
```
## For Ollie
```
IPv4 Address 10.81.18.194
Netmask 255.255.255.192
Default Gateway 10.81.18.193
```
## For Anya
```
IPv4 Address 10.81.18.195
Netmask 255.255.255.192
Default Gateway 10.81.18.193
```
## For Reine
```
IPv4 Address 10.81.18.196
Netmask 255.255.255.192
Default Gateway 10.81.18.193
```
## For Holoh3ro

### Interfaces
```
Fast Ethernet0/0 (A14)
- IPv4 Address  : 10.81.19.98
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/1 (A15)
- IPv4 Address  : 10.81.16.1
- Subnet Mask   : 255.255.254.0
```

### Static route
```
Default (Holo-ID)
0.0.0.0/0 via 10.81.19.97

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.97
```
## For Zeta
```
IPv4 Address 10.81.16.2
Netmask 255.255.254.0
Default Gateway 10.81.16.1
```
## For Kaela
```
IPv4 Address 10.81.16.3
Netmask 255.255.254.0
Default Gateway 10.81.16.1
```
## For Kobo
```
IPv4 Address 10.81.16.4
Netmask 255.255.254.0
Default Gateway 10.81.16.1
```
## For Holo-JP

### Interfaces
```
Fast Ethernet0/0 (A16)
- IPv4 Address  : 10.81.19.102
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/1 (A17)
- IPv4 Address  : 10.81.19.65
- Subnet Mask   : 255.255.255.248
```

### Static route
```
Default (Holo-Live)
0.0.0.0/0 via 10.81.19.101

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.101

(A18)
10.81.19.32/28 via 10.81.19.66

Network: 10.81.19.32
Mask: 255.255.255.240
Next Hop: 10.81.19.66

(A19)
10.81.0.0/21 via 10.81.19.67

Network: 10.81.0.0
Mask: 255.255.248.0
Next Hop: 10.81.19.67

(A20)
10.81.14.0/23 via 10.81.19.67

Network: 10.81.14.0
Mask: 255.255.254.0
Next Hop: 10.81.19.67

(A21)
10.81.19.104/30 via 10.81.19.67

Network: 10.81.19.104
Mask: 255.255.255.252
Next Hop: 10.81.19.67

(A22)
10.81.18.0/25 via 10.81.19.67

Network: 10.81.18.0
Mask: 255.255.255.128
Next Hop: 10.81.19.67
```
## For DEV-LS

### Interfaces
```
Fast Ethernet0/0 (A17)
- IPv4 Address  : 10.81.19.66
- Subnet Mask   : 255.255.255.248

Fast Ethernet0/1 (A18)
- IPv4 Address  : 10.81.19.33
- Subnet Mask   : 255.255.255.240
```

### Static route
```
Default (Holo-JP)
0.0.0.0/0 via 10.81.19.65

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.65
```
## For Ririka_Raden
```
IPv4 Address 10.81.19.34
Netmask 255.255.255.240
Default Gateway 10.81.19.33
```
## For Ao
```
IPv4 Address 10.81.19.35
Netmask 255.255.255.240
Default Gateway 10.81.19.33
```
## For Hajime_Kanade
```
IPv4 Address 10.81.19.36
Netmask 255.255.255.240
Default Gateway 10.81.19.33
```
## For GEN:0

### Interfaces
```
Fast Ethernet0/0 (A17)
- IPv4 Address  : 10.81.19.67
- Subnet Mask   : 255.255.255.248

Fast Ethernet0/1 (A19)
- IPv4 Address  : 10.81.0.1
- Subnet Mask   : 255.255.248.0
```

### Static route
```
Default (Holo-JP)
0.0.0.0/0 via 10.81.19.65

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.65

(A20)
10.81.14.0/23 via 10.81.0.4

Network: 10.81.14.0
Mask: 255.255.254.0
Next Hop: 10.81.0.4

(A21)
10.81.19.104/30 via 10.81.0.4

Network: 10.81.19.104
Mask: 255.255.255.252
Next Hop: 10.81.0.4

(A22)
10.81.18.0/25 via 10.81.0.4

Network: 10.81.18.0
Mask: 255.255.255.128
Next Hop: 10.81.0.4
```
## For MiComet
```
IPv4 Address 10.81.0.2
Netmask 255.255.248.0
Default Gateway 10.81.0.1
```
## For Sora_Robo_AZKi
```
IPv4 Address 10.81.0.3
Netmask 255.255.248.0
Default Gateway 10.81.0.1
```
## For GEN:

### Interfaces
```
Fast Ethernet0/0 (A19)
- IPv4 Address  : 10.81.0.4
- Subnet Mask   : 255.255.248.0

Fast Ethernet0/1 (A20)
- IPv4 Address  : 10.81.14.1
- Subnet Mask   : 255.255.254.0

Fast Ethernet0/1 (A21)
- IPv4 Address  : 10.81.19.105
- Subnet Mask   : 255.255.255.252
```

### Static route
```
Default (GEN:0)
0.0.0.0/0 via 10.81.0.1

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.0.1

(A22)
10.81.18.0/25 via 10.81.19.106

Network: 10.81.18.0
Mask: 255.255.255.128
Next Hop: 10.81.19.106
```
## For FBK_Matsuri
```
IPv4 Address 10.81.14.2
Netmask 255.255.254.0
Default Gateway 10.81.14.1
```
## For Aki_Hachama
```
IPv4 Address 10.81.14.3
Netmask 255.255.254.0
Default Gateway 10.81.14.1
```
## For GAMERS

### Interfaces
```
Fast Ethernet0/1 (A21)
- IPv4 Address  : 10.81.19.106
- Subnet Mask   : 255.255.255.252

Fast Ethernet0/0 (A22)
- IPv4 Address  : 10.81.18.1
- Subnet Mask   : 255.255.255.128
```

### Static route
```
Default (GEN:1)
0.0.0.0/0 via 10.81.19.105

Network: 0.0.0.0
Mask: 0.0.0.0
Next Hop: 10.81.19.105
```
## For Korone
```
IPv4 Address 10.81.18.2
Netmask 255.255.255.128
Default Gateway 10.81.18.1
```
## For Okayu
```
IPv4 Address 10.81.18.3
Netmask 255.255.255.128
Default Gateway 10.81.18.1
```
## For Mio
```
IPv4 Address 10.81.18.4
Netmask 255.255.255.128
Default Gateway 10.81.18.1
```

# GNS3 - CIDR

### Topologi

![Screenshot 2024-11-14 003658](https://github.com/user-attachments/assets/d9db947c-c82b-403d-99e5-80c8cedf84c3)

### Rute

![image](https://github.com/user-attachments/assets/af602292-8069-48b1-b897-37d056263177)

### Penggabungan CIDR

![image](https://github.com/user-attachments/assets/0228ae6c-0176-48ff-b816-ead7a0994495)
![image](https://github.com/user-attachments/assets/6f75aca1-b0b8-44d8-b8ad-d4af2de93b43)

<img width="864" alt="modul4_A" src="https://github.com/user-attachments/assets/d7cb3af6-c8d4-4793-a1b4-f506408e179c">

### Pembagian IP - CIDR

Tree

![Screenshot 2024-11-17 123234](https://github.com/user-attachments/assets/307f1483-6ad9-4a85-bd6f-47decfe57d44)

![image](https://github.com/user-attachments/assets/5897fb21-4077-49b8-98df-f82a8a655ba4)

### Konfigurasi GNS3 - CIDR


