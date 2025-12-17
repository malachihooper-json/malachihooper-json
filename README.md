<div align="center">

<!-- HEADER BANNER -->
<img src="assets/banner.jpg.jpg" alt="Neural Network Banner" width="100%"/>

                                                                                                                                            
### `Malachi Hooper`
                                                                                                                                            
## `Library of Developments`

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/m.alachii)
[![ProtonMail](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:malllachi@proton.me)
[![GitHub followers](https://img.shields.io/github/followers/malachihooper-json?style=for-the-badge&logo=github&logoColor=white)](https://github.com/malachihooper-json)

</div>

---

<div align="center">

### `> Machine Learning Systems Designer `
### `> Texas Tech University`

</div>

---

## Focus:

Currently, I am focusing on adaptive mesh networks using machine learning. I have also just released a plug-and-play peer-to-peer mesh network library for distributed computation on .NET/C# systems (8). This requires Powershell accessibility and is very durable. The project is called Nightframe.

<table>
<tr>
<td width="50%">

```
┌──────────────────────────────┐
│  Neural Network Cross-Communication
│  Network Durability          │
│  Peer-To-Peer Protocols      │
└──────────────────────────────┘
```

</td>
<td width="50%">

```
┌──────────────────────────────┐
│  Cross-Platform Inter-op     │
│  Active ML Self-Critique     │
│  Embedded Coding Agents      │
└──────────────────────────────┘
```

</td>
</tr>
</table>

---

## Proficiencies

<div align="center">

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

</div>

---

<div align="center">

# NIGHTFRAME

**Decentralized AI Mesh Network Overview**

A distributed computing platform that enables collaborative neural network inference across a mesh of autonomous nodes. Features cellular intelligence, GPU-accelerated ONNX runtime, and viral network propagation.

---

## VIEW FEATURES

| Feature | Description |
|---------|-------------|
| **Distributed Inference** | Pipeline-parallel model sharding across nodes |
| **Cellular Intelligence** | RF fingerprinting and handover prediction |
| **Neural Compute** | ONNX Runtime with GPU acceleration (CUDA, DirectML, CoreML) |
| **Mesh Discovery** | UDP broadcast + mDNS peer discovery |
| **Captive Portal** | Platform-aware network propagation |
| **Credit Economy** | Incentivized compute contribution |

---

## VIEW ARCHITECTURE

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         WEB CONSOLE (React/Next.js)                          │
└───────────────────────────────────────┬─────────────────────────────────────┘
                                        │ SignalR WebSocket
                                        ▼
┌─────────────────────────────────────────────────────────────────────────────┐
│                        ORCHESTRATOR (Command Node)                           │
│                        ASP.NET Core + gRPC                                   │
├─────────────────────────────────────────────────────────────────────────────┤
│  Drone Registry │ Ledger Service │ Shard Coordinator │ Cell Coordinator     │
└───────────────────────────────────────┬─────────────────────────────────────┘
                                        │ gRPC bidirectional streaming
                        ┌───────────────┼───────────────┐
                        ▼               ▼               ▼
                  ┌─────────┐     ┌─────────┐     ┌─────────┐
                  │ DESKTOP │     │  SCOUT  │     │ ANDROID │
                  │  DRONE  │     │  DRONE  │     │  SCOUT  │
                  │─────────│     │─────────│     │─────────│
                  │ Compute │     │ Cellular│     │ Wi-Fi   │
                  │ Storage │     │ RF Loc  │     │ Scanning│
                  │ Gateway │     │ Predict │     │ GPS Map │
                  └─────────┘     └─────────┘     └─────────┘
```

---

## VIEW COMPONENTS

| Project | Description |
|---------|-------------|
| **Shared** | Unified interfaces (INeuralCompute, ICellular, INetworkNode) |
| **Orchestrator** | Command node with gRPC server and SignalR hub |
| **Drone** | Desktop node with cellular and ONNX integration |
| **DroneAndroid** | Android Scout app (MAUI) |
| **Watchdog** | Process supervisor for hot-swap updates |
| **gamma1-web** | Next.js web console |

---

## QUICK START GUIDE

### Prerequisites
- .NET 8.0 SDK
- Node.js 18+ (for web console)
- Windows 10/11, macOS, or Linux

### Build

```bash
# Build all projects
dotnet build NIGHTFRAME.sln

# Run Orchestrator in Genesis mode (single PC testing)
dotnet run --project Orchestrator -- --mode genesis

# Run standalone Drone
dotnet run --project Drone
```

### Web Console

```bash
cd gamma1-web
npm install
npm run dev
```

---

## 📡 Cellular Intelligence

- **RF Fingerprinting**: GPS-free location (50-500m accuracy)
- **Handover Prediction**: Preemptive tower switching via LSTM
- **AT Command Support**: Quectel, Telit, Sierra modems
- **OpenCellID Integration**: Cell tower database sync

---

## 🧠 Neural Compute

| Provider | Platform | Hardware |
|----------|----------|----------|
| **CUDA** | All | NVIDIA GPUs |
| **DirectML** | Windows | AMD, Intel GPUs |
| **CoreML** | macOS | Apple Silicon |
| **CPU** | All | Fallback |

---

## 🔐 Security

- **ECDSA Identity**: Cryptographic node authentication
- **Shadow Mode**: Probationary period for new nodes
- **Consensus Validation**: Multi-node result verification
- **Signed Compute**: Verifiable result attribution

---

## 📊 Credit Economy

| Action | Credits |
|--------|---------|
| Compute shard | +100 |
| Storage (per GB) | +10 |
| Uptime (per hour) | +5 |
| Prompt submission | -50 |

---

## 📁 Project Structure

```
├── NIGHTFRAME.sln
├── Shared/              # Shared interfaces
├── Orchestrator/        # Command node
├── Drone/               # Desktop drone
├── DroneAndroid/        # Android scout
├── Watchdog/            # Process supervisor
├── gamma1-web/          # Web console
└── docs/                # Documentation
```

---

## 🔄 Platform Support

| Platform | Role | Status |
|----------|------|--------|
| Windows | Full Node | ✅ |
| macOS | Full Node | ✅ |
| Linux | Full Node | ✅ |
| Android | Scout Node | 🚧 |

---

## 📜 License

Copyright © 2024 Malachi Hooper. All rights reserved.

---

**NIGHTFRAME** — Decentralized Intelligence at Scale


</details>

---
```
```
---

## Contact

<div align="center">

| Platform | Link |
|:--------:|:----:|
| **Instagram** | [@m.alachii](https://instagram.com/m.alachii) |
| **Email** | [malllachi@proton.me](mailto:malllachi@proton.me) |

<br/>

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║   malachihooper.json GITHUB                               ║
║                                                           ║
╚═══════════════════════════════════════════════════════════╝
____________________________________________________________
__________________________________________________________
```

<br/>

</div>

---

<sub><sup>

`▓▒░ signal.processing ░▒▓` `▓▒░ mesh.network ░▒▓` `▓▒░ swarm.intelligence ░▒▓`
`░▒▓ rf.fingerprinting ▓▒░` `░▒▓ geolocation ▓▒░` `░▒▓ spectrum.analysis ▓▒░`
`▓░▒ distributed.compute ▒░▓` `▓░▒ autonomous.agents ▒░▓` `▓░▒ neural.security ▒░▓`
░▒▓██████████████▓▒░ ░▒▓██████▓▒░░▒▓█▓▒░       ░▒▓██████▓▒░ ░▒▓██████▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░ ░▒▓██████▓▒░░▒▓███████▓▒░░▒▓████████▓▒░▒▓███████▓▒░  
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓████████▓▒░▒▓█▓▒░      ░▒▓████████▓▒░▒▓█▓▒░      ░▒▓████████▓▒░▒▓█▓▒░      ░▒▓████████▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓███████▓▒░░▒▓██████▓▒░ ░▒▓███████▓▒░  
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░ 
░▒▓█▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░░▒▓█▓▒░▒▓████████▓▒░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░░▒▓█▓▒░░▒▓█▓▒░▒▓█▓▒░      ░▒▓█▓▒░░▒▓█▓▒░░▒▓██████▓▒░ ░▒▓██████▓▒░░▒▓█▓▒░      ░▒▓████████▓▒░▒▓█▓▒░░▒▓█▓▒░                                                                                                                                                                 
</sup></sub>

<!--
╔══════════════════════════════════════════════════════════════════════════════╗
║ SIGINT signals-intelligence ELINT electronic-intelligence COMINT            ║
║ communications-intelligence MASINT measurement-signature-intelligence       ║
║ GEOINT geospatial-intelligence OSINT open-source-intelligence              ║
║ HUMINT human-intelligence IMINT imagery-intelligence TECHINT               ║
║ autonomous-systems swarm-robotics mesh-networking distributed-computing     ║
║ neural-network-security adversarial-machine-learning rf-fingerprinting     ║
║ spectrum-analysis signal-processing cognitive-radio software-defined-radio ║
║ peer-to-peer-protocols distributed-ledger zero-trust-architecture          ║
║ edge-computing fog-computing autonomous-navigation path-planning           ║
║ sensor-fusion multi-agent-systems reinforcement-learning transfer-learning ║
║ federated-learning privacy-preserving-ml secure-multiparty-computation     ║
║ homomorphic-encryption post-quantum-cryptography lattice-cryptography      ║
║ DARPA IARPA ARPA-E defense-research advanced-research military-ai         ║
║ tactical-communications battlefield-networks mobile-ad-hoc-networks MANET ║
║ delay-tolerant-networking DTN store-and-forward opportunistic-routing     ║
║ cognitive-electronic-warfare spectrum-dominance electronic-countermeasures║
║ radar-cross-section stealth-technology metamaterials antenna-design       ║
║ phased-array beamforming MIMO massive-MIMO millimeter-wave 5G-NR 6G       ║
║ satellite-communications LEO-constellations inter-satellite-links ISL    ║
║ drone-swarm UAV UAS unmanned-systems autonomous-vehicles robotics        ║
║ computer-vision object-detection tracking-algorithms SLAM localization   ║
║ inertial-navigation GPS-denied-navigation terrain-matching TERCOM        ║
║ cryptanalysis side-channel-attacks fault-injection hardware-security     ║
║ trusted-execution-environment secure-enclave ARM-TrustZone Intel-SGX     ║
║ reverse-engineering malware-analysis binary-exploitation vulnerability   ║
║ penetration-testing red-team blue-team purple-team threat-intelligence   ║
║ cyber-physical-systems SCADA ICS critical-infrastructure industrial-IoT  ║
║ quantum-computing quantum-sensing quantum-communication QKD entanglement ║
║ neuromorphic-computing spiking-neural-networks brain-inspired-computing  ║
║ hypersonic aerodynamics propulsion materials-science high-temperature    ║
║ directed-energy laser-weapons microwave-weapons electromagnetic-pulse EMP║
║ synthetic-aperture-radar SAR inverse-SAR ground-penetrating-radar GPR    ║
║ acoustic-sensing sonar underwater-communications submarine-detection     ║
║ biometric-identification facial-recognition gait-analysis behavioral-bio ║
║ natural-language-processing sentiment-analysis named-entity-recognition  ║
║ knowledge-graphs semantic-web ontology-engineering information-extraction║
╚══════════════════════════════════════════════════════════════════════════════╝

research: arxiv ieee acm springer nature science proceedings conference journal
publications: preprint peer-reviewed citations h-index impact-factor scholarly
institutions: MIT Stanford Berkeley CMU Caltech Georgia-Tech Princeton
laboratories: Lincoln-Lab APL Sandia Los-Alamos Oak-Ridge PNNL Argonne
agencies: NSF DOE DOD NIST NASA NRL ONR AFRL AFOSR ARO DARPA IARPA
programs: SBIR STTR BAA RFI RFP contract grant fellowship research-award

keywords: machine-learning deep-learning artificial-intelligence AI ML DL NN
frameworks: TensorFlow PyTorch JAX Keras MXNet Caffe ONNX TensorRT OpenVINO
languages: Python C++ Rust Julia CUDA OpenCL SYCL HIP ROCm MLIR XLA
hardware: GPU TPU NPU FPGA ASIC neuromorphic edge-accelerator inference-chip
-->

<sub><sup>

`⠀⠀⠀⠋⠁⠉⠓⠊⠝⠑⠀⠇⠑⠁⠗⠝⠊⠝⠛⠀⠀⠀` `⠀⠀⠙⠑⠑⠏⠀⠇⠑⠁⠗⠝⠊⠝⠛⠀⠀⠀` `⠀⠀⠝⠑⠥⠗⠁⠇⠀⠝⠑⠞⠺⠕⠗⠅⠎⠀⠀⠀`
`⠎⠊⠛⠝⠁⠇⠎⠀⠊⠝⠞⠑⠇⠇⠊⠛⠑⠝⠉⠑` `⠉⠕⠍⠏⠥⠞⠑⠗⠀⠧⠊⠎⠊⠕⠝` `⠁⠥⠞⠕⠝⠕⠍⠕⠥⠎⠀⠎⠽⠎⠞⠑⠍⠎`

</sup></sub>

<!-- 
p2p mesh swarm distributed autonomous self-organizing emergent behavior
tactical edge computing fog nodes gateway relay bridge router switch
spectrum sensing cognitive radio dynamic spectrum access frequency hopping
spread spectrum FHSS DSSS OFDM modulation demodulation encoding decoding
encryption authentication authorization access control identity management
-->



















