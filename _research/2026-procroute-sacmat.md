---
layout: single
title: "ProcRoute: Process-Scoped Authorization of Split-Tunnel Routes"
collection: research
permalink: /research/procroute
year: 2026
authors: ["Arul Thileeban Sagayam"]
---

Accepted in SACMAT 2026. 

ProcRoute prevents split-tunnel VPN abuse by restricting internal routes to explicitly authorized applications instead of the entire device. It enforces per-process access control using a default-deny model, mediating connections via eBPF and cgroup-based identity. The system achieves near-baseline performance with minimal overhead, blocks all tested unauthorized access, and supports fast, scalable policy enforcement.
