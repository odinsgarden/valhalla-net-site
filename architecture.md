---
layout: page
title: THORVEIL Architecture
permalink: /architecture/
---

# THORVEIL Architecture Overview

**Core principle**: Make operating-system complexity irrelevant by enforcing physical and cryptographic boundaries that software alone cannot bypass.

### High-Level Block Diagram
[Insert simple diagram here — you can use draw.io / Excalidraw and upload as PNG to /assets/img/]

- **Dirty Side** (exposed, complex, internet-facing)  
  - Standard OS (Windows/Linux) or hardened container  
  - All normal applications and network access  
  - Can be fully compromised — assumed hostile

- **One-Way Data Diode** (hardware-enforced)  
  - Commercial or custom FPGA-based unidirectional gateway  
  - Data flows out only (telemetry, logs, results)  
  - No reverse path possible — physics-level block

- **Clean Side** (protected, minimal, isolated)  
  - RAM-only OS (Alpine toram variant or custom micro-distro)  
  - Ephemeral execution — no disk, no persistence  
  - SHA-3 measured boot + PQC signatures (Dilithium)  
  - Post-quantum key exchange (Kyber) for any outbound tunnels  
  - Ghost-layer identity overlay (ephemeral IDs, no static MAC/UUID)

- **Outcome**  
  - Dirty-side malware cannot pivot or exfiltrate from clean side  
  - No forensic artifacts after shutdown  
  - Quantum-resistant against harvest-now-decrypt-later  
  - Minimal attack surface on clean side (verifiable by audit)

### Key Differentiators vs Existing Solutions
- Not software firewall / sandbox / VDI — physical diode cannot be reconfigured or bypassed  
- Not just PQC — combines hardware isolation + quantum crypto + zero persistence  
- Not cloud-dependent — fully air-gapped-capable endpoint

thor.whittaker@valhallainnovations.com
