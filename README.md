# Hi, I'm Bo Sam Ath 👋

IP Network Engineer based in Cambodia — 8 years building and operating service-provider core networks at **Metfone**, now IP Network Operations at **Telcotech**.

Direction: **AI-powered network engineer** — carrier-scale networking experience, multiplied by automation and AI. Not replacing the network engineer with AI; making one engineer count for more.

---

## 🌐 Networking Background

- **Experience:** MPLS core networks — L2 VPN (VPWS, VPLS), L3 VPN (MP-BGP VPNv4), transport operations at Metfone
- **Deep dives:** Segment Routing (SR-MPLS, SRv6, TI-LFA, SR-TE), EVPN, DC fabrics (VXLAN EVPN)
- **Platforms:** Cisco IOS XR, NX-OS · EVE-NG labs

**Protocols:**
`IS-IS` · `BGP` · `MPLS` · `SR-MPLS` · `SRv6` · `EVPN` · `VXLAN` · `L3VPN` · `L2VPN`

---

## 🧭 Where I'm Heading

| Step | Focus |
|------|-------|
| **Now** | Core routing depth — BGP, IS-IS: the *why*, not just the config |
| **Next** | Linux + network automation — Python, Netmiko/NAPALM, Ansible |
| **Then** | AI agents on network ops — fault analysis, config generation, monitoring |
| **Always** | AI-assisted daily operations — documentation, troubleshooting, runbooks |

---

## 📁 Featured Labs

Every lab is phased, verified in EVE-NG with real `show` output, and ends each phase with a "Can I explain it?" checkpoint.

### [SR-MPLS & SRv6 on Cisco IOS XRv9000 — EVE-NG](https://github.com/bosamart/sr-mpls-iosxr-eveng-lab)

A 7-phase lab building a service-provider core from scratch — no LDP, no RSVP-TE.

| Phase | Topic |
|-------|-------|
| 1 | IS-IS baseline (Level-2, wide metrics) |
| 2 | SR-MPLS — prefix-SIDs, no LDP |
| 3 | TI-LFA fast reroute — 100% coverage, sub-50ms |
| 4 | SR-TE explicit-path policy |
| 5 | L3VPN over SR-MPLS (MP-BGP VPNv4) |
| 6 | L3VPN over SRv6 (uDT4) |
| 7 | EVPN-VPWS L2VPN over SR-MPLS and SRv6 (uDX2) |

### [MPLS Traffic Engineering on Cisco IOS XRv9000 — EVE-NG](https://github.com/bosamart/xrv9000-mpls-te-lab)

A 6-phase lab on the transport generation *before* Segment Routing — RSVP-TE and LDP — because you can't appreciate SR until you've felt RSVP-TE's state problem.

| Phase | Topic |
|-------|-------|
| 1 | IS-IS baseline |
| 2 | MPLS LDP label distribution |
| 3 | RSVP-TE explicit-path tunnels |
| 4 | CSPF and autoroute announce |
| 5 | Fast Reroute (FRR) protection |
| 6 | L3VPN over MPLS-TE |

### [VXLAN EVPN Fabric on Cisco Nexus 9000v — EVE-NG-(building)](https://github.com/bosamart/VXLAN-EVPN-L3-Fabric)

Spine-leaf DC fabric: OSPF underlay, MP-BGP EVPN overlay with spine route reflectors, VTEP/NVE, L2VNI extension — including the eBGP-overlay lessons learned the hard way.

**Sequel in progress:** L3 fabric — L3VNI, symmetric IRB, distributed anycast gateway, tenant VRF, EVPN Type-5 border leaf. Public after full verification.

---

## 🤖 AI & Automation

Using AI aggressively as a working tool, not a buzzword: documentation, troubleshooting analysis, lab design, and study — moving toward LLM agents that read network state and assist operations.

- AI-assisted network operations (Claude workflows, daily ops)
- Python for network automation (Netmiko/NAPALM, in progress)
- Linux foundations for automation and monitoring
- Git/GitHub for everything you see here

---

## 📫 Contact

- GitHub: [@bosamart](https://github.com/bosamart)
- Email: bosamart@gmail.com
