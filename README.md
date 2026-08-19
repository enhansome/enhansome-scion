# Awesome SCION with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 497,472 | 🐛 102 | 📅 2026-08-18
[![Slack chat](https://img.shields.io/badge/chat%20on-slack-blue?logo=slack)](https://scionproto.slack.com)
[![Matrix chat](https://img.shields.io/badge/chat%20on-matrix-blue?logo=matrix)](https://matrix.to/#/#scion:matrix.scion.org)
[![SCION Association](https://img.shields.io/badge/SCION-Association-white)](https://www.scion.org)

<a href="https://www.scion.org"><img src="awesome-scion-logo.webp" height="160" align="right" alt="awesome SCION"></a>

A curated list of awesome SCION tools, applications, libraries and resources.

> Symbol legend
>
> * :wrench:: Experimental
> * :construction:: Under construction
> * :broom:: Outdated/discontinued/unclear

## Infrastructure

* [scionproto/scion](https://github.com/scionproto/scion) ⭐ 561 | 🐛 152 | 🌐 Go | 📅 2026-08-12 - The open-source implementation of SCION.
* [tofino-scion-br](https://github.com/netsys-lab/scion-p4/tree/main/tofino-scion-br) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-02-25 - SCION border router in P4 with support for AES accelerators. :wrench:
* [bootstrapper](https://github.com/netsec-ethz/bootstrapper) ⭐ 3 | 🐛 8 | 🌐 Go | 📅 2025-09-23 - SCION endhost autoconfiguration tool.
* [scion-ca](https://github.com/netsys-lab/scion-ca) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2023-03-20 - SCION Control Plane PKI implementation based on [smallstep/step-ca](https://github.com/smallstep/certificates) ⭐ 8,756 | 🐛 288 | 🌐 Go | 📅 2026-08-17.
* [step-scion-plugin](https://github.com/scionproto-contrib/step-scion-plugin) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-07-08 - SCION Control Plane PKI plugin for [smallstep/cli](https://github.com/smallstep/cli) ⭐ 4,309 | 🐛 190 | 🌐 Go | 📅 2026-08-17 :wrench: :construction:
* [Anapaya](https://www.anapaya.net) - Vendor of SCION infrastructure, both based on the open-source implementation and proprietary.

## Applications

* [scion-apps](https://github.com/netsec-ethz/scion-apps) ⭐ 31 | 🐛 40 | 🌐 Go | 📅 2026-07-09 - Miscellaneous SCION demo applications.
* [bittorrent-over-scion](https://github.com/netsys-lab/bittorrent-over-scion) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2024-10-07 - Path-aware BitTorrent client running on SCION.
* [scion-browser-extension](https://github.com/scionproto-contrib/browser-extension) ⭐ 4 | 🐛 3 | 🌐 TypeScript | 📅 2026-03-11 - SCION support for Chrome/Firefox :wrench: ([docs](https://scion-browser-extension.readthedocs.io/en/latest/index.html)).
* [ioq3-scion](https://github.com/lschulz/ioq3-scion) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-08-17 - Quake III with SCION networking. :boom:
* [hercules](https://github.com/netsec-ethz/hercules) ⭐ 2 | 🐛 3 | 🌐 C | 📅 2024-04-17 - High speed bulk data transfer application. :wrench:
* [multiping](https://github.com/netsec-ethz/scion-java-multiping) ⭐ 2 | 🐛 1 | 🌐 Java | 📅 2026-05-04 - A tool to measure latency on multiple paths to multiple destinations. :wrench:
* [HTTP proxy](https://github.com/scionproto-contrib/http-proxy) ⭐ 1 | 🐛 1 | 🌐 Go | 📅 2026-05-18 - SCION enabled HTTP Forward/Reverse proxy :wrench:
* [jpan-cli](https://github.com/netsec-ethz/jpan-cli) ⭐ 1 | 🐛 1 | 🌐 Java | 📅 2026-08-14 - A stand-alone tool for ping, traceroute, showpaths, address, etc. Based on jpan. :wrench:
* [nats-server](https://github.com/MartincoitNetworks/nats-server) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2023-12-18 - [NATS](https://nats.io/) server with SCION networking. :wrench: :construction:
* [spate](https://github.com/netsys-lab/scion-apps/tree/tool/spate-bpf/spate) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2025-05-08 - Multipath traffic generator and bandwidth tester. :wrench:
* [nats-client](https://github.com/MartincoitNetworks/scion-nats.go) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2023-12-18 - Simple [NATS](https://nats.io/) client for SCION Enabled NATS servers. :wrench: :construction:
* [SCION Application docs](https://docs.scion.org/projects/scion-applications/en/latest/) Compilation of technical information for supported SCION applications.
* [Scitra-TUN](https://lcschulz.de/software/scitra-tun/) - A SCION-IPv6 packet translator.

## Examples

* [JPAN packet example](https://github.com/netsec-ethz/scion-java-packet-example) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-07-19 - A simple example (used [here](https://apps.scion.org)) that sends a packet to the [SCION packet analyzer](https://scionpacketinspector.netsec.ethz.ch).

## Libraries

##### Go

* [parts](https://github.com/netsys-lab/parts) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2022-05-22 - Path-aware Reliable Transport over SCION. :wrench:
* [scion-path-discovery](https://github.com/netsys-lab/scion-path-discovery) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2024-01-15 - Multipath library for SCION.
* [scion-apps/pkg/pan](https://pkg.go.dev/github.com/netsec-ethz/scion-apps/pkg/pan) - Policy-based, path aware network library for building applications supporting SCION natively.
* [scion-apps/pkg/shttp](https://pkg.go.dev/github.com/netsec-ethz/scion-apps/pkg/shttp) - Glue to use the standard net/http libraries for HTTP with SCION, using pan.
* [scion-apps/pkg/shttp3](https://pkg.go.dev/github.com/netsec-ethz/scion-apps/pkg/shttp3) - Glue to use quic-go/http3 libraries for HTTP/3 with SCION, using pan.
* [snet](https://pkg.go.dev/github.com/scionproto/scion/pkg/snet) - Primary, but low-ish-level level library for native SCION applications.

##### Java

* [jpan](https://github.com/scionproto-contrib/jpan) ⭐ 5 | 🐛 11 | 🌐 Java | 📅 2026-08-18 - Java SCION application library. :wrench:

##### Rust

* [scion-sdk](https://github.com/Anapaya/scion-sdk) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 - SCION endhost stack written in Rust.

##### C++

* [scion-cpp](https://github.com/lschulz/scion-cpp) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2026-08-10 - SCION C++ application SDK. Includes support for ASIO and C-style socket programming.

##### Bindings

* [pan-lua](https://github.com/netsys-lab/pan-lua) ⭐ 2 | 🐛 1 | 🌐 Go | 📅 2024-04-02 - Lua-scriptable path selector interface to pan.
* [pan-bindings](https://github.com/lschulz/pan-bindings) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-08-17 - C, C++, and Python bindings for pan.
* [snet-bindings](https://github.com/lschulz/snet-bindings) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2026-08-17 - C and C++ bindings for snet. :wrench:

## Deployments

* [ISD and AS Assignments](https://learn.anapaya.net/docs/resources/assignments/) - Assigned [ISD](https://docs.scion.org/en/latest/glossary.html#term-ISD) and [AS](https://docs.scion.org/en/latest/glossary.html#term-AS) numbers<sup>[1](#footnonte-isd-as-assignment)</sup>.
* [SSFN](https://www.six-group.com/de/products-services/banking-services/ssfn.html) - Swiss Secure Finance Network, a closed network using SCION.
* [Scion Education Network](https://sciera.readthedocs.io/en/latest/index.html) - SCION network connecting universities and national research and education networks (NRENs).
* [SCIONLab](https://www.scionlab.org) - Global SCION network testbed.
* [SCI-ED](https://scied.scion-architecture.net/) - SCION at various institutions of the ETH Domain. :broom:
* [swissix SCION peering](https://www.swissix.ch/services/scion-peering-mesh/scion-peering-participants/) - SCION peering mesh at the swissix internet exchange.

## Tools

* [SEED Emulator](https://github.com/seed-labs/seed-emulator/tree/master/examples/scion) ⭐ 284 | 🐛 32 | 🌐 Python | 📅 2026-08-09 - SEED Security Labs network emulator supports SCION.
* [scapy-scion-int](https://github.com/lschulz/scapy-scion-int) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-07-16 - [Scapy](https://scapy.net/) layers for SCION.
* [tofino-pktgen](https://github.com/netsys-lab/scion-p4/tree/main/tofino-pktgen) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-02-25 - SCION packet generator for Intel Tofino 2 switches.
* [ietf-scion-testbed](https://github.com/netsys-lab/ietf-scion-testbed) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-07-24 - Ansible/Proxmox deployment of a 12-AS SCION testbed with parallel BGP/IP routing, link shaping and a monitoring dashboard.

## IETF

* [draft-dekater-scion-pki](https://datatracker.ietf.org/doc/draft-dekater-scion-pki/)
* [draft-dekater-scion-controlplane](https://datatracker.ietf.org/doc/draft-dekater-scion-controlplane/)
* [draft-dekater-scion-dataplane](https://datatracker.ietf.org/doc/draft-dekater-scion-dataplane/)

## Research

* [Publications list](https://www.scion.org/research/)
* [LightningFilter](https://github.com/netsec-ethz/lightning-filter) ⭐ 4 | 🐛 12 | 🌐 C | 📅 2025-03-26 - High-speed traffic filtering mechanism that performs authentication, rate limiting, and duplicate detection.

## Operating System Support

* [NixOS Support for SCION](https://wiki.nixos.org/wiki/SCION)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

***

<sub><a name="footnonte-isd-as-assignment">\[1]</a>: ISD and AS numbers assignments are currently managed by Anapaya. This will be handed over to a vendor-neutral governance body, like the regional internet registries or the SCION Association, as soon as possible.</sub>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
