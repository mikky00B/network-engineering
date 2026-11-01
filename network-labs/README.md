# Network Labs

A collection of practical networking exercises, virtual topologies, configuration examples, and troubleshooting notes.

## Lab categories

| Directory | Focus |
|---|---|
| [VLAN labs](./vlan-labs/) | VLAN creation, access and trunk ports, segmentation, and inter-VLAN communication |
| [Routing labs](./routing-labs/) | Routing tables, gateways, static routes, and packet paths |
| [OSPF labs](./ospf-labs/) | OSPF neighbours, areas, route learning, and convergence |
| [BGP labs](./bgp-labs/) | Autonomous systems, peering, route advertisement, and route selection |
| [Troubleshooting](./troubleshooting/) | Structured diagnosis of connectivity and network issues |

## Lab documentation template

Use this outline for each substantial lab:

- **Objective:** What are you trying to understand or configure?
- **Prerequisites:** Required concepts, software, and device images.
- **Topology:** Diagram, addressing plan, and interface connections.
- **Configuration:** Step-by-step commands or configuration files.
- **Verification:** Commands, packet captures, and expected outcomes.
- **Troubleshooting:** Symptoms, diagnostic process, root cause, and fix.
- **Conclusion:** Key observations and possible next experiments.

## Lab principles

- Keep exercises reproducible and explain the environment used.
- Include IP addressing tables and topology diagrams when relevant.
- Verify behaviour rather than relying only on configuration success messages.
- Never include passwords, private keys, API tokens, or other secrets in committed files.
- Distinguish simulated behaviour from behaviour verified on physical equipment.
