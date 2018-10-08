# Road-Warrior
Openwrt Atheros openvpn/wireguard VPN router

The following scripts automate the configurations of the Atheros router to support openvpn/wireguard VPN clients.
The build supports split VPN and support multiple instances of openvpn/wireguard VPN running at the same time.
It also has passthrough to for Captive Portal login.  VPNs has killswitch, no dnsleak builtin.
It also resolves the STA+AP problem on WISP mode and supports multiple STA clients so you will never be locked out.

Restrictions
Currently supports on Openwrt 18.06
Hardware must be Atheros Chipset, eg. TP-Link 810Nv1, GL inet 6164A/AR150
Router must have minimum 8M flash and 64M memory.
IPv4 on VPN only.
