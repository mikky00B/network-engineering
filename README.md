# Network Engineering

A practical portfolio documenting my work in **network engineering, network automation, and network software development**.

This repository brings together hands-on virtual labs, troubleshooting exercises, technical notes, and implementation experiments. The goal is to connect telecommunications and networking fundamentals with software engineering using Python and Go.

## Focus areas

- **Networking fundamentals:** TCP/IP, Ethernet, IPv4/IPv6, subnetting, switching, routing, DNS, DHCP, and NAT.
- **Routing and infrastructure:** VLANs, static routing, OSPF, BGP fundamentals, and network troubleshooting.
- **Network automation:** Python-based device interaction, configuration collection, validation, and repeatable workflows.
- **Network software:** APIs, monitoring, telemetry, and network-facing services built with Python and Go.

## Repository structure

```text
network-engineering/
├── README.md
└── network-labs/
    ├── README.md
    ├── vlan-labs/
    ├── routing-labs/
    ├── ospf-labs/
    ├── bgp-labs/
    └── troubleshooting/
```

## Labs

The [network-labs](./network-labs/) directory contains practical exercises. Each lab should aim to include:

1. **Objective** — the concept or problem being explored.
2. **Topology** — a diagram and device/interface details where applicable.
3. **Configuration** — commands or configuration files needed to reproduce it.
4. **Verification** — tests and expected results.
5. **Troubleshooting** — issues encountered and how they were diagnosed.
6. **Takeaways** — what the lab demonstrates and any limitations.

## Tools

The lab environment will use tools such as Cisco Packet Tracer, Wireshark, Linux networking utilities, and later Containerlab or GNS3 where appropriate. Tool choice will depend on the exercise.

## Approach

I prioritise reproducible work over screenshots alone. Where possible, labs will include configuration files, command output, diagrams, and clear verification steps. Experiments will be labelled as such, and vendor-specific behaviour will be identified.

## Progress

This repository is being built incrementally. The initial focus is on core networking labs before moving into network automation and network software projects.
