# Mac Changer

A MAC address is a unique identifier assigned to a network interface controller for use as a network address in communications within a network segment.

## Usage

When we type `ifconfig` on the terminal we see the following output -

![eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 192.168.31.134  netmask 255.255.255.0  broadcast 192.168.31.255
        inet6 fe80::20c:29ff:fe0d:c4ec  prefixlen 64  scopeid 0x20<link>
        ether ```48:46:16:f2:40:c5```  txqueuelen 1000  (Ethernet)
        RX packets 1106  bytes 1407300 (1.3 MiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 293  bytes 36703 (35.8 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0](image-1.png)

        we see the mac address is 48:46:16:f2:40:c5

### After running the command

the mac address had been changed to the desired address.

![alt text](image-2.png)
