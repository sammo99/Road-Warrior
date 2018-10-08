# Road-Warrior
OpenWrt Atheros Openvpn/Wireguard VPN router

The following scripts automate the configurations of the OpenWrt Atheros Router to support Openvpn/Wireguard VPN clients.
The build supports split VPNs and can support multiple instances of Openvpn/Wireguard VPN running at the same time.
It also has passthrough for Captive Portal login.  VPNs has killswitch and no dnsleak builtin.
It also resolves the STA+AP problem on WISP mode and supports multiple STA clients connect so you will never be locked out.

Requirements
  OpenWrt Atheros Chipset Router eg TP-Link810n, GL inet 6146A/AR150
  Basic Linux skills.
  Very basic understanding of routing.

Restrictions
  Currently supported on OpenWrt 18.06.
  Router must have minimum 8M flash and 64M memory.
  VPNs support IPv4 only.
  Tested on PIA/NordVPN so far.
  No Luci/Gui support
