# CUCME with SIP phones and SRST fallback

Branch voice lab: SIP phones register to CUCME, and the branch router is set up for SRST (`call-manager-fallback`) so phones keep working if the link to central call control is lost.

- `configs/`: `voice register global`, `voice register dn` and `pool` for Cisco 9951 SIP phones, `allow-connections sip to sip`, POTS and VoIP dial peers, DHCP pools for the voice subnets, and RIP routing.
- `captures/`: phone registration and signalling, a voice call and a video call.

---
Lab work from my Master of Engineering in Internetworking, Dalhousie University (2024 to 2026). Course handouts and graded answer sheets are not included.

Author: Vikramjeet Singh, [LinkedIn](https://www.linkedin.com/in/vikramjeet-singh-75b7a2183)
