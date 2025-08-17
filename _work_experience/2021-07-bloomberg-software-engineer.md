---
layout: single
title: "Bloomberg, Edge Access and Security (Software Engineer)"
collection: work_experience
permalink: /work_experience/bloomberg-software-engineer/
start: 2021-07
end: present
location: "New York, NY"
---

Built and maintained secure access infrastructure for Bloomberg engineers, focusing on Zero Trust, identity-aware reverse proxies, and a company VPN client.

- Designed and implemented an Identity-Aware Proxy (IAP) and level-2 reverse proxy including a JWT validator; enabled transparent TCP connections over a layer-7 proxy to support non-HTTP traffic.
	- Scaled to handle ~2M requests/day with reliable authorization checks.
	- Coordinated with the Browser Working Group on HTTP/CORS mitigations and contributed fixes upstream to Envoy and Pomerium to improve mTLS support.

- Developed "bbVPN" (internal VPN client) replacing a third-party solution; integrated OpenVPN3 and built cross-platform GUI components.
	- Tuned gateway configurations and deployment, improving global throughput by ~30% and APAC throughput by ~54%.

Tech stack: Go, C++, Envoy, Pomerium, Postgres, C# (.NET), Swift, Python, OpenVPN.
