## 📡 4. Connectivity Testing

### 4.1 Ping Test Screenshot(s)
```
images/ping-pc0.png
```

### 4.2 Describe the Results
- Were all PCs able to ping each other?
- Answer, Yes, all configured PCs(PCO through PC4) successfully pinged one another because they are on the same switch and subnet.
- Which pings were successful?
  Answer, All local pings between the valid configured IP address from 192.168.1.10 to 192.168.1.14 were completely successful.
- Which ones failed and why?
  Answer, Pinging the non-existing IP address 192.168.1.15 failed (timed out) because no physical device or host on the network was assigned that address,

_Write your explanation here…
The connectivity test confirms that the local network is properly configured and functioning. All five workstation (PCo-PC4) sucessfully exchanged ICMP echo packets becuse they share an identical subnet mask and reside within the same layer 2 broadcast domainon the central switch.

