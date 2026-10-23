---
topic:
  - Technology
aliases:
  - Internet Protocol address
---
*An unique identifying number assigned to every device connected to the [[internet]]*[^4]

# IPv4

In this IP version each IP address has 4 numbers 0 to 255. Since each number uses 8 bits of space (00010101 for example), one IP address uses 32 bits

> [!a] Examples
> 12.5.23.102
> 203.22.0.9

There are only 256⁴ = 4,294,967,296 (~4.3 billion) IP addresses available[^1]

## Classes

|     | Range                       | Subnet mask          | No. of IP addresses | No. of networks |
| --- | --------------------------- | -------------------- | ------------------- | --------------- |
| A   | 1.0.0.0 - 126.255.255.255   | a.x.y.z              | 16 777 214          | 126             |
| B   | 128.0.0.0 - 191.255.0.0     | a.b.x.y              | 65 534              | 16 382          |
| C   | 192.0.0.0 - 223.255.255.0   | a.b.c.x              | 254                 | 2 097 150       |
| D   | 224.0.0.0 - 239.255.255.255 | (used for multicast) |                     |                 |
| E   | 240.0.0.0 - 255.255.255.255 |                      |                     |                 |

a, b and c refers the numbers attributed to a network. x, y and z refers the numbers attributed to each device

*Nowadays we mainly to classless networks to take advantage of the IP addresses we need to use*[^1]. Class A has too many IP addresses per network...

## Private IP addresses

A set of addresses of the classes A, B and C are reserved for the private IP addresses. Those are only used within the LAN (Local Area Network) and will not connect a device to the Internet

|     | Range                         |
| --- | ----------------------------- |
| A   | 10.0.0.0 - 10.255.255.255     |
| B   | 172.16.0.0 - 172.31.255.255   |
| C   | 192.168.0.0 - 192.168.255.255 |

# Loop back addresses

127.0.0.0 - 127.255.255.255 which can be used to test a local network[^2]

# Special IP addresses

- 0.0.0.0 - *used as a default or placeholder address*[^3]; it refers to "this network"

# Ports

*A port is a virtual point where network connections start and end*[^5]

Each port is assigned a number and is reserved for specific protocols[^5]. The Internet Assigned Numbers Authority manages the ports uses. [List of ports in Wikipedia](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)

*Ports allow computers to easily differentiate between different kinds of traffic*[^5] which makes network connections more efficient


[^1]: *We ran out of IP Addresses*, NetworkChuck (2022)
[^2]: 16 777 216 different addresses available!
[^3]: *What does the 0.0.0.0 IP address mean and why is it used?*, Jessica Scarpati (2021)
[^5]: *What is a computer port?*, Cloudfare