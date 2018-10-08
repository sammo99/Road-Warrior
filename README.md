# Road-Warrior
OpenWrt Atheros openvpn/wireguard VPN router

The following scripts automate the configurations of the OpenWrt Atheros Router to support openvpn/wireguard VPN clients.
The build supports split VPNs and support multiple instances of openvpn/wireguard VPN running at the same time.
It also has passthrough for Captive Portal login.  VPNs has killswitch and no dnsleak builtin.
It also resolves the STA+AP problem on WISP mode and supports multiple STA clients so you will never be locked out.

Requirements
OpenWrt Atheros Chipset Router.
Basic Linux skills.
Basic understanding of routing.

Restrictions
Currently supported on Openwrt 18.06
Router must have minimum 8M flash and 64M memory.
VPNs supported on IPv4 only.
