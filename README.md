# AS4242420288: IWARP Test Network on DN42


This page is under construction.

Peering to the following node(s) is open:
- Los Angeles, United States: Wireguard only

Send an email to `dn42 at iwarp dot org` with the following information:
- Your AS number
- Note to peer. `Los Angeles` by default.
- Wireguard info:
  - Your public IP address (or domain name). IPv4 is preferred but IPv6 is also supported. Currently my server doesn't have a native IPv6 address so I have to use a tunnel.
  - Your wireguard port, or `20288` by default. The port on my side will be `2<last 4 digits of your ASN>`.
  - Tunnel IPv4 address and/or IPv6 address on your side. A link-local IPv6 address is prefered.
  - Multiprotocol BGP supported or not. If yes, the link-local address on my side will be `fe80::<last 4 digits of your ASN>`
- Any other info
