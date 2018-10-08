# Road-Warrior
OpenWrt Atheros Openvpn/Wireguard VPN router.  The following scripts automate the configurations of the OpenWrt Atheros Router to support Openvpn/Wireguard VPN clients.  The build supports split VPNs and can support multiple instances of Openvpn/Wireguard VPN running at the same time.  It also has passthrough for Captive Portal login.  VPNs has killswitch and no dnsleak builtin. Built-in VPN monitoring, so it restarts or move to the next one on a predefined lists.  It also resolves the STA+AP problem on WISP mode so you will never be locked out and supports multiple STA clients connect. 

Requirements

OpenWrt Atheros Chipset Router eg TP-Link 810n, GL inet 6146A/AR150.

Basic Linux skills.

Very basic understanding of routing.

Restrictions

Currently supported on OpenWrt 18.06.

Router must have minimum 8M flash and 64M memory.

VPNs support IPv4 only.

Tested on PIA/NordVPN vpn provider so far.

No Luci/Gui support.
