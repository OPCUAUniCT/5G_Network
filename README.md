# 5G_Network AAS — Asset Administration Shell for 5G Network Infrastructure

This repository contains the **Asset Administration Shell (AAS)** model for a **5G Network Infrastructure**, provided in the file `5G_NETWORK.aasx`.  
The model was developed as part of the *Water 4.0* project to support the integration of 5G connectivity into the **Digital Twin of the Integrated Water System (SII)**.

## Repository Contents

- `5G_NETWORK.aasx` → Complete AAS model of a 5G Network (shell + submodels)
  - Represents the technical, topological, operational, and service-oriented aspects of a 5G network.


## Model Structure

The AAS model is structured as follows:

### Common Submodels

These submodels provide general-purpose metadata shared across multiple AAS in the Water 4.0 ecosystem:

- `Identification` – General metadata describing the digital asset
- `TechnicalData` – Basic technical attributes of the 5G network infrastructure
- `Documentation` – Attached documentation or external references (e.g., manuals, diagrams, certificates)
- `Nameplate` – Manufacturer and product identity (manufacturer, model, serial number, hardware/software revisions, year of construction, etc.)

###  5G-Specific Submodels

These submodels capture the core functional aspects of the 5G network:

- `Network5GDataSheet` – Radio and core network configuration, frequencies, nodes, capabilities
- `PDUSessions` – Active PDU sessions between UEs and the network, with identifiers and QoS settings
- `Performance` – Real-time information on throughput, latency, signal quality, and related metrics
- `PhysicalAndLogicalTopology` – Logical and geographical representation of connected nodes/users
- `QosFlows` – Event-driven monitoring and management of quality of service (QoS) flows
- `AssetServiceRegistry` – Service metadata (SLA, integrator, coverage maps, service types)

---

##  Viewing the Model

To explore or modify the model:

1. Download AASX Package Explorer v2024-05-08

2. Open the application and load `5G_NETWORK.aasx` via `File → Open`.

3. Browse the shell and submodels to inspect property structures and semantic definitions.

---


