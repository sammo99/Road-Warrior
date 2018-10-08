# Road-Warrior
OpenWrt Atheros Openvpn/Wireguard VPN router.  The following scripts automate the configurations of the OpenWrt Atheros Router to support Openvpn/Wireguard VPN clients.  The build supports split VPNs and can have multiple instances of Openvpn/Wireguard VPN running at the same time.  It also has passthrough for Captive Portal login.  VPNs has killswitch and no dnsleak builtin. Built-in VPN monitoring, so it restart or move to the next one on a predefined lists when the current VPN is not contactable.  It also resolves the STA+AP problem on WISP mode so you will never be locked out and supports multiple STA clients connect. Once setup, it's very much self service/automated with no intervention from user other than setting up STA clients/Captive Portal login, so ideal for moving from location to location.

Requirements

OpenWrt Atheros Chipset Router eg TP-Link 810n, GL inet 6146A/AR150 etc.

Basic Linux skills.

Very basic understanding of routing.

Restrictions

Currently supported on OpenWrt 18.06.

Router must have minimum 8M flash and 64M memory.

No Luci/Gui support.

VPNs support IPv4 only.

WISP mode only.

Tested on PIA/NordVPN VPN providers so far.
