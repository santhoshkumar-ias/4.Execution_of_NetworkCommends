# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
```
Microsoft Windows [Version 10.0.26200.8973]
(c) Microsoft Corporation. All rights reserved.

C:\Users\santhosh>ipconfig /all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : HP_VICTUS_AI
   Primary Dns Suffix  . . . . . . . :
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Realtek Gaming GbE Family Controller
   Physical Address. . . . . . . . . : 24-FB-E3-C2-82-E2
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-18
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::b352:849d:ddc5:62a4%24(Preferred)
   Autoconfiguration IPv4 Address. . : 169.254.120.33(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 923402279
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-E3-B4-24-FB-E3-C2-82-E2
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Ethernet 3:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter #2
   Physical Address. . . . . . . . . : 0A-00-27-00-00-03
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::a37c:6a25:ff56:b9a2%3(Preferred)
   IPv4 Address. . . . . . . . . . . : 169.254.78.2(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 856293415
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-E3-B4-24-FB-E3-C2-82-E2
   NetBIOS over Tcpip. . . . . . . . : Enabled

Wireless LAN adapter Wi-Fi 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC #2
   Physical Address. . . . . . . . . : 5E-02-05-47-B7-AC
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Wi-Fi 5:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC #5
   Physical Address. . . . . . . . . : 5A-02-05-47-B7-AC
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . : saveetha.in
   Description . . . . . . . . . . . : Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC
   Physical Address. . . . . . . . . : 58-02-05-47-B7-AC
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   IPv6 Address. . . . . . . . . . . : 2403:8600:c090:42:0:400:65:1a8b(Preferred)
   Lease Obtained. . . . . . . . . . : 06 August 2026 07:53:45
   Lease Expires . . . . . . . . . . : 06 August 2026 08:06:56
   Link-local IPv6 Address . . . . . : fe80::c1c2:435b:b09a:4160%11(Preferred)
   Autoconfiguration IPv4 Address. . : 169.254.145.111(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . : fe80::eedd:24ff:fe3d:ced5%11
   DHCPv6 IAID . . . . . . . . . . . : 106430981
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-E3-B4-24-FB-E3-C2-82-E2
   DNS Servers . . . . . . . . . . . : 2403:8600:c090:42:a000::200
   NetBIOS over Tcpip. . . . . . . . : Enabled
   Connection-specific DNS Suffix Search List :
                                       saveetha.in

Ethernet adapter VMware Network Adapter VMnet1:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VMware Virtual Ethernet Adapter for VMnet1
   Physical Address. . . . . . . . . : 00-50-56-C0-00-01
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::54ba:4a02:fe34:ed65%7(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.56.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 06 August 2026 07:53:39
   Lease Expires . . . . . . . . . . : 06 August 2026 08:28:17
   Default Gateway . . . . . . . . . :
   DHCP Server . . . . . . . . . . . : 192.168.56.254
   DHCPv6 IAID . . . . . . . . . . . : 822104150
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-E3-B4-24-FB-E3-C2-82-E2
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter VMware Network Adapter VMnet8:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VMware Virtual Ethernet Adapter for VMnet8
   Physical Address. . . . . . . . . : 00-50-56-C0-00-08
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::afab:7e61:830d:9cb9%21(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.119.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 06 August 2026 07:53:39
   Lease Expires . . . . . . . . . . : 06 August 2026 08:28:17
   Default Gateway . . . . . . . . . :
   DHCP Server . . . . . . . . . . . : 192.168.119.254
   DHCPv6 IAID . . . . . . . . . . . : 838881366
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-E3-B4-24-FB-E3-C2-82-E2
   Primary WINS Server . . . . . . . : 192.168.119.2
   NetBIOS over Tcpip. . . . . . . . : Enabled

C:\Users\santhosh>netstat -an

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    0.0.0.0:135            0.0.0.0:0              LISTENING
  TCP    0.0.0.0:445            0.0.0.0:0              LISTENING
  TCP    0.0.0.0:902            0.0.0.0:0              LISTENING
  TCP    0.0.0.0:912            0.0.0.0:0              LISTENING
  TCP    0.0.0.0:5040           0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49664          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49665          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49666          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49667          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49668          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49671          0.0.0.0:0              LISTENING
  TCP    127.0.0.1:11434        0.0.0.0:0              LISTENING
  TCP    127.0.0.1:63159        0.0.0.0:0              LISTENING
  TCP    169.254.78.2:139       0.0.0.0:0              LISTENING
  TCP    169.254.120.33:139     0.0.0.0:0              LISTENING
  TCP    169.254.145.111:139    0.0.0.0:0              LISTENING
  TCP    192.168.56.1:139       0.0.0.0:0              LISTENING
  TCP    192.168.119.1:139      0.0.0.0:0              LISTENING
  TCP    [::]:135               [::]:0                 LISTENING
  TCP    [::]:445               [::]:0                 LISTENING
  TCP    [::]:49664             [::]:0                 LISTENING
  TCP    [::]:49665             [::]:0                 LISTENING
  TCP    [::]:49666             [::]:0                 LISTENING
  TCP    [::]:49667             [::]:0                 LISTENING
  TCP    [::]:49668             [::]:0                 LISTENING
  TCP    [::]:49671             [::]:0                 LISTENING
  TCP    [::1]:42050            [::]:0                 LISTENING
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:1710  [2404:6800:4007:836::200a]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:5455  [2603:1040:5:3::1d]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:6685  [2606:4700:3037::ac43:a01e]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:10391  [2600:140f:5e00:14::17d3:3c18]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:10392  [2603:1046:c06:8ce::2]:443  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:13418  [2a06:98c1:3109::6812:2159]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:14785  [2a06:98c1:3109::ac40:9aa7]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:15762  [2001:4860:4826:200::]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:15931  [64:ff9b::8efb:dc62]:443  TIME_WAIT
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:20583  [2600:1901:0:47fc::]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:22009  [64:ff9b::36f:f1e0]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:28861  [64:ff9b::22d7:9e0b]:443  CLOSE_WAIT
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:31873  [64:ff9b::14b8:af13]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:32118  [2404:6800:4007:800::200a]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:32125  [64:ff9b::14b8:af04]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:33506  [2606:50c0:8003::215]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:35520  [64:ff9b::8c52:7219]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:36378  [2404:6800:4007:83c::200e]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:38514  [2600:140f:5e00:14::17d3:3c29]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:43056  [2600:140f:5e00:14::17d3:3c2e]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:43172  [2a06:98c1:3109::6812:2159]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:44444  [2600:140f:5e00:14::17d3:3c18]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:45714  [64:ff9b::acbc:9b19]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:49211  [2404:6800:4007:808::200e]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:49408  [2603:1040:a06:6::2]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:49409  [2603:1040:a06:6::2]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:49692  [2603:1040:5:3::1d]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:49781  [2001:4860:4827:7700::]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:52817  [2606:50c0:8000::154]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:56311  [2603:1040:a06:6::2]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:59492  [2403:8600:80c0:4a::e62:1008]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:63724  [2001:4860:4802:32::181]:443  ESTABLISHED
  TCP    [2403:8600:c090:42:0:400:65:1a8b]:65234  [2404:6800:4007:816::2003]:443  ESTABLISHED
  UDP    0.0.0.0:5050           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5355           *:*
  UDP    127.0.0.1:1900         *:*
  UDP    127.0.0.1:49257        *:*
  UDP    127.0.0.1:64404        127.0.0.1:64404
  UDP    169.254.78.2:137       *:*
  UDP    169.254.78.2:138       *:*
  UDP    169.254.78.2:1900      *:*
  UDP    169.254.78.2:49253     *:*
  UDP    169.254.120.33:137     *:*
  UDP    169.254.120.33:138     *:*
  UDP    169.254.120.33:1900    *:*
  UDP    169.254.120.33:49252   *:*
  UDP    169.254.145.111:137    *:*
  UDP    169.254.145.111:138    *:*
  UDP    169.254.145.111:1900   *:*
  UDP    169.254.145.111:49254  *:*
  UDP    192.168.56.1:137       *:*
  UDP    192.168.56.1:138       *:*
  UDP    192.168.56.1:1900      *:*
  UDP    192.168.56.1:49255     *:*
  UDP    192.168.119.1:137      *:*
  UDP    192.168.119.1:138      *:*
  UDP    192.168.119.1:1900     *:*
  UDP    192.168.119.1:49256    *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5355              *:*
  UDP    [::1]:1900             *:*
  UDP    [::1]:49251            *:*
  UDP    [fe80::54ba:4a02:fe34:ed65%7]:1900  *:*
  UDP    [fe80::54ba:4a02:fe34:ed65%7]:49249  *:*
  UDP    [fe80::a37c:6a25:ff56:b9a2%3]:1900  *:*
  UDP    [fe80::a37c:6a25:ff56:b9a2%3]:49247  *:*
  UDP    [fe80::afab:7e61:830d:9cb9%21]:1900  *:*
  UDP    [fe80::afab:7e61:830d:9cb9%21]:49250  *:*
  UDP    [fe80::b352:849d:ddc5:62a4%24]:1900  *:*
  UDP    [fe80::b352:849d:ddc5:62a4%24]:49246  *:*
  UDP    [fe80::c1c2:435b:b09a:4160%11]:1900  *:*
  UDP    [fe80::c1c2:435b:b09a:4160%11]:49248  *:*

C:\Users\santhosh>netstat -r
===========================================================================
Interface List
  9...24 fb e3 c2 82 e2 ......Realtek Gaming GbE Family Controller
 24...0a 00 27 00 00 18 ......VirtualBox Host-Only Ethernet Adapter
  3...0a 00 27 00 00 03 ......VirtualBox Host-Only Ethernet Adapter #2
 17...5e 02 05 47 b7 ac ......Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC #2
 14...5a 02 05 47 b7 ac ......Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC #5
 11...58 02 05 47 b7 ac ......Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC
  7...00 50 56 c0 00 01 ......VMware Virtual Ethernet Adapter for VMnet1
 21...00 50 56 c0 00 08 ......VMware Virtual Ethernet Adapter for VMnet8
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
      169.254.0.0      255.255.0.0         On-link      169.254.78.2    281
      169.254.0.0      255.255.0.0         On-link    169.254.120.33    281
      169.254.0.0      255.255.0.0         On-link   169.254.145.111    286
     169.254.78.2  255.255.255.255         On-link      169.254.78.2    281
   169.254.120.33  255.255.255.255         On-link    169.254.120.33    281
  169.254.145.111  255.255.255.255         On-link   169.254.145.111    286
  169.254.255.255  255.255.255.255         On-link      169.254.78.2    281
  169.254.255.255  255.255.255.255         On-link    169.254.120.33    281
  169.254.255.255  255.255.255.255         On-link   169.254.145.111    286
     192.168.56.0    255.255.255.0         On-link      192.168.56.1    291
     192.168.56.1  255.255.255.255         On-link      192.168.56.1    291
   192.168.56.255  255.255.255.255         On-link      192.168.56.1    291
    192.168.119.0    255.255.255.0         On-link     192.168.119.1    291
    192.168.119.1  255.255.255.255         On-link     192.168.119.1    291
  192.168.119.255  255.255.255.255         On-link     192.168.119.1    291
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link      192.168.56.1    291
        224.0.0.0        240.0.0.0         On-link     192.168.119.1    291
        224.0.0.0        240.0.0.0         On-link    169.254.120.33    281
        224.0.0.0        240.0.0.0         On-link      169.254.78.2    281
        224.0.0.0        240.0.0.0         On-link   169.254.145.111    286
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link      192.168.56.1    291
  255.255.255.255  255.255.255.255         On-link     192.168.119.1    291
  255.255.255.255  255.255.255.255         On-link    169.254.120.33    281
  255.255.255.255  255.255.255.255         On-link      169.254.78.2    281
  255.255.255.255  255.255.255.255         On-link   169.254.145.111    286
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
 11    286 ::/0                     fe80::eedd:24ff:fe3d:ced5
  1    331 ::1/128                  On-link
 11    286 2403:8600:c090:42::/84   On-link
 11    286 2403:8600:c090:42:0:400:65:1a8b/128
                                    On-link
  7    291 fe80::/64                On-link
 21    291 fe80::/64                On-link
 24    281 fe80::/64                On-link
  3    281 fe80::/64                On-link
 11    286 fe80::/64                On-link
  7    291 fe80::54ba:4a02:fe34:ed65/128
                                    On-link
  3    281 fe80::a37c:6a25:ff56:b9a2/128
                                    On-link
 21    291 fe80::afab:7e61:830d:9cb9/128
                                    On-link
 24    281 fe80::b352:849d:ddc5:62a4/128
                                    On-link
 11    286 fe80::c1c2:435b:b09a:4160/128
                                    On-link
  1    331 ff00::/8                 On-link
  7    291 ff00::/8                 On-link
 21    291 ff00::/8                 On-link
 24    281 ff00::/8                 On-link
  3    281 ff00::/8                 On-link
 11    286 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

C:\Users\santhosh>nslookup google.com
Server:  UnKnown
Address:  2403:8600:c090:42:a000::200

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4007:80f::200e
          142.250.77.142


C:\Users\santhosh>tracert google.com

Tracing route to google.com [2404:6800:4007:80f::200e]
over a maximum of 30 hops:

  1     3 ms   272 ms    19 ms  2403:8600:c090:42::1
  2     *        *        *     Request timed out.
  3     *        *        *     Request timed out.
  4    28 ms   264 ms    20 ms  maa05s05-in-x0e.1e100.net [2404:6800:4007:80f::200e]

Trace complete.

C:\Users\santhosh>route print
===========================================================================
Interface List
  9...24 fb e3 c2 82 e2 ......Realtek Gaming GbE Family Controller
 24...0a 00 27 00 00 18 ......VirtualBox Host-Only Ethernet Adapter
  3...0a 00 27 00 00 03 ......VirtualBox Host-Only Ethernet Adapter #2
 17...5e 02 05 47 b7 ac ......Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC #2
 14...5a 02 05 47 b7 ac ......Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC #5
 11...58 02 05 47 b7 ac ......Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC
  7...00 50 56 c0 00 01 ......VMware Virtual Ethernet Adapter for VMnet1
 21...00 50 56 c0 00 08 ......VMware Virtual Ethernet Adapter for VMnet8
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
      169.254.0.0      255.255.0.0         On-link      169.254.78.2    281
      169.254.0.0      255.255.0.0         On-link    169.254.120.33    281
      169.254.0.0      255.255.0.0         On-link   169.254.145.111    286
     169.254.78.2  255.255.255.255         On-link      169.254.78.2    281
   169.254.120.33  255.255.255.255         On-link    169.254.120.33    281
  169.254.145.111  255.255.255.255         On-link   169.254.145.111    286
  169.254.255.255  255.255.255.255         On-link      169.254.78.2    281
  169.254.255.255  255.255.255.255         On-link    169.254.120.33    281
  169.254.255.255  255.255.255.255         On-link   169.254.145.111    286
     192.168.56.0    255.255.255.0         On-link      192.168.56.1    291
     192.168.56.1  255.255.255.255         On-link      192.168.56.1    291
   192.168.56.255  255.255.255.255         On-link      192.168.56.1    291
    192.168.119.0    255.255.255.0         On-link     192.168.119.1    291
    192.168.119.1  255.255.255.255         On-link     192.168.119.1    291
  192.168.119.255  255.255.255.255         On-link     192.168.119.1    291
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link      192.168.56.1    291
        224.0.0.0        240.0.0.0         On-link     192.168.119.1    291
        224.0.0.0        240.0.0.0         On-link    169.254.120.33    281
        224.0.0.0        240.0.0.0         On-link      169.254.78.2    281
        224.0.0.0        240.0.0.0         On-link   169.254.145.111    286
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link      192.168.56.1    291
  255.255.255.255  255.255.255.255         On-link     192.168.119.1    291
  255.255.255.255  255.255.255.255         On-link    169.254.120.33    281
  255.255.255.255  255.255.255.255         On-link      169.254.78.2    281
  255.255.255.255  255.255.255.255         On-link   169.254.145.111    286
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
 11    286 ::/0                     fe80::eedd:24ff:fe3d:ced5
  1    331 ::1/128                  On-link
 11    286 2403:8600:c090:42::/84   On-link
 11    286 2403:8600:c090:42:0:400:65:1a8b/128
                                    On-link
  7    291 fe80::/64                On-link
 21    291 fe80::/64                On-link
 24    281 fe80::/64                On-link
  3    281 fe80::/64                On-link
 11    286 fe80::/64                On-link
  7    291 fe80::54ba:4a02:fe34:ed65/128
                                    On-link
  3    281 fe80::a37c:6a25:ff56:b9a2/128
                                    On-link
 21    291 fe80::afab:7e61:830d:9cb9/128
                                    On-link
 24    281 fe80::b352:849d:ddc5:62a4/128
                                    On-link
 11    286 fe80::c1c2:435b:b09a:4160/128
                                    On-link
  1    331 ff00::/8                 On-link
  7    291 ff00::/8                 On-link
 21    291 ff00::/8                 On-link
 24    281 ff00::/8                 On-link
  3    281 ff00::/8                 On-link
 11    286 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

C:\Users\santhosh>net view
System error 6118 has occurred.

The list of servers for this workgroup is not currently available


C:\Users\santhosh>systeminfo

Host Name:                     HP_VICTUS_AI
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              perarasuarasu451@gmail.com
Registered Organization:       HP
Product ID:                    00342-42745-37755-AAOEM
Original Install Date:         03-08-2025, 04:18:20
System Boot Time:              06-08-2026, 07:53:08
System Manufacturer:           HP
System Model:                  Victus by HP Gaming Laptop 15-fb3xxx
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: AMD64 Family 25 Model 117 Stepping 2 AuthenticAMD ~3993 Mhz
BIOS Version:                  AMI F.15, 27-04-2026
Windows Directory:             C:\windows
System Directory:              C:\windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         15,599 MB
Available Physical Memory:     5,008 MB
Virtual Memory: Max Size:      22,255 MB
Virtual Memory: Available:     7,140 MB
Virtual Memory: In Use:        15,115 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\HP_VICTUS_AI
Hotfix(s):                     6 Hotfix(s) Installed.
                               [01]: KB5100998
                               [02]: KB5050575
                               [03]: KB5054156
                               [04]: KB5059093
                               [05]: KB5101684
                               [06]: KB5101711
Network Card(s):               6 NIC(s) Installed.
                               [01]: Realtek Gaming GbE Family Controller
                                     Connection Name: Ethernet
                                     Status:          Media disconnected
                               [02]: Realtek 8852BE-VT Wireless LAN WiFi 6 PCI-E NIC
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     255.255.255.255
                                     IP address(es)
                                     [01]: 169.254.145.111
                                     [02]: fe80::c1c2:435b:b09a:4160
                                     [03]: 2403:8600:c090:42:0:400:65:1a8b
                               [03]: VMware Virtual Ethernet Adapter for VMnet1
                                     Connection Name: VMware Network Adapter VMnet1
                                     DHCP Enabled:    Yes
                                     DHCP Server:     192.168.56.254
                                     IP address(es)
                                     [01]: 192.168.56.1
                                     [02]: fe80::54ba:4a02:fe34:ed65
                               [04]: VMware Virtual Ethernet Adapter for VMnet8
                                     Connection Name: VMware Network Adapter VMnet8
                                     DHCP Enabled:    Yes
                                     DHCP Server:     192.168.119.254
                                     IP address(es)
                                     [01]: 192.168.119.1
                                     [02]: fe80::afab:7e61:830d:9cb9
                               [05]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 169.254.120.33
                                     [02]: fe80::b352:849d:ddc5:62a4
                               [06]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 3
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 169.254.78.2
                                     [02]: fe80::a37c:6a25:ff56:b9a2
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                                     Secure Launch
                                     SMM Firmware Measurement
                               Services Running:
                                     Hypervisor enforced Code Integrity
                                     Secure Launch
                                     SMM Firmware Measurement
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
                               SMM Isolation Level: 30
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Users\santhosh>
```
## Result
Thus Execution of Network commands Performed 



