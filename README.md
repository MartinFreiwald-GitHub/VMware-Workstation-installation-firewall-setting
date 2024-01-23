# VMware-Workstation-installation-firewall-setting
After installing your VMware Workstation look in the firewall to find VMware Authd Service.  Located on the inbound Rules side of the firewall.

Need to filter this VMware Authd Service through port 80/tcp and 443/tcp.  

This provides that your SSL service and TLS 1.3 are also routing VMware Workstation connections through port 80 and port 443 TCP.  

Makes a robust security posture.
