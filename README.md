# Simulation of CoAP Protocol in IoT Networks using Cooja

A simulation study of the Constrained Application Protocol (CoAP) on
Contiki-NG and the Cooja simulator, evaluating latency, packet delivery
ratio (PDR) and energy consumption in a low-power, lossy wireless
sensor network.

> **Status:** Project proposal and methodology with literature survey.
> Simulation results will be added to `/results` once experiments are complete.

## Team
- Aishwarya Y (22MIS0281)
- Sandhya A (22MIS0248)
- Radhika Raina (22MIS0468)

VIT, Information Security Analysis and Audit course project.

## Objective
Evaluate how CoAP behaves in a resource-constrained network under
varying topology size and traffic conditions, to support protocol
selection and optimization in IoT systems.

## Background
- **CoAP:** lightweight RESTful application-layer protocol over UDP
  (GET, POST, PUT, DELETE), with a compact binary format, retransmission
  support and multicast.
- **Cooja / Contiki-NG:** open-source simulator that emulates real motes
  (e.g. Sky, Z1) and supports packet logs, topology visualization and
  energy profiling (Powertrace).

## Tech stack
Contiki-NG, Cooja, CoAP, UDP, 6LoWPAN, RPL, Powertrace

## Metrics
| Metric | Meaning |
|---|---|
| Latency | Time between a CoAP request and its response |
| Packet Delivery Ratio | Packets received / packets sent |
| Energy consumption | Per-node energy measured with Powertrace |

## Methodology (planned)
| Phase | Weeks | Activities |
|---|---|---|
| 1. Setup | 1-2 | Install Contiki-NG and Cooja; basic CoAP exchange between 2 motes |
| 2. Network design | 3-4 | Build a 10+ node 6LoWPAN/RPL topology; generate CoAP GET/POST traffic; analyze logs |
| 3. Evaluation | 5-6 | Measure latency, PDR and energy; generate graphs; document results |

## Literature survey
A review of 10 papers on CoAP performance, congestion control
(CoCoA, CoCoA+), MQTT-SN comparisons, RPL/6LoWPAN and secure CoAP
(LightCert4IoT). Full table in [`docs/literature_survey.md`](docs/literature_survey.md).

**Identified gaps:** limited work on scalability, mixed traffic
patterns, security overhead at scale, and unified evaluation of
congestion, energy and reliability.

## Results
_To be added._

## Documents
- [Project presentation](docs/CoAP_Cooja_Project_Presentation.pdf)
