Networking:
IP Address: Unique address of a device on a network.

Public IP: Assigned by ISP, visible on the Internet, usually one per home router.
Private IP: Assigned by the router inside your home network (e.g. 192.168.x.x).
Used only within the local network.

Router: Connects your home network to the Internet. It has a Public IP on the Internet side and assigns Private IPs to local devices. 
NAT (Network Address Translation): Performed by the router. It translates Private IPs to the router's Public IP when 
sending traffic to the Internet , and translates replies back to the correct device.


Flow: Laptop (192.168.1.10) -> Router (NAT) -> Public IP (49.x.x.x) -> Internet -> Google -> Router -> Laptop. 
Mobile Data: Your phone connects to a mobile tower. The tower forwards traffic to the mobile operator's core network. 
The core network assigns your phone an internal IP and usually uses CGNAT (Carrier-Grade NAT). 


CGNAT: Used by ISPs/mobile operators so many customers can share a limited number of Public IPv4 addresses. 
It translates the phone's internal IP to a shared Public IP and keeps a translation table using ports.
Difference: • Home Wi-Fi: Router assigns Private IP and performs NAT.  


Mobile Data: Mobile operator assigns internal IP and the operator's CGNAT performs NAT.
Important: Public IP reaches the router (or carrier network), not directly your laptop or phone.
The router/CGNAT decides where to forward packets.
