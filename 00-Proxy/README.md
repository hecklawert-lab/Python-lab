# Python-Network-Tools
_Just some network tools written in Python_

## pyproxy.py
There are a number of reasons to have a TCP proxy in your tool belt, both for forwarding traffic to bounce from host to host, but also when assessing network-based software. When performing penetration tests in enterprise environments, you’ll commonly be faced with the fact that you can’t run Wireshark, that you can’t load drivers to sniff the loopback on Windows, or that network segmentation prevents you from running your tools directly against your target host.

```
Usage: ./pyproxy.py [localhost] [localport] [remotehost] [remoteport] [receive_first]
Example: ./pyproxy.py 127.0.0.1 9000 10.12.132.1 9000 True
``` 
