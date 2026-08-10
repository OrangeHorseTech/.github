<p align="center">
  <img src="https://github.com/OrangeHorseTech/.github/blob/main/logo.png" alt="OrangeHorseTech Logo" width="200"/>
</p>

# OrangeHorseTech

Industrial sensors, edge gateways, and high-performance field software. We develop reliable hardware devices, open-source protocol stacks, and diagnostic tools for industrial automation and edge computing.

---

### 🛠️ Open Source Ecosystem

### [OMS Modbus](https://github.com/OrangeHorseTech/oms-modbus) — v0.2.0 Preview

[![Rust](https://img.shields.io/badge/rust-1.80%2B-orange?logo=rust)](https://www.rust-lang.org)
[![License](https://img.shields.io/badge/license-MIT%2FApache--2.0-blue)](https://github.com/OrangeHorseTech/oms-modbus/blob/main/LICENSE-MIT)

High-performance, transport-generic Modbus library for Rust. Full Master/Slave
for TCP, RTU, and ASCII with passive bus monitoring, spec-compliant RS-485
timing, and auto-reconnect. Zero panics. Zero unsafe.

```rust
// One API, every transport
let client = tcp::TcpClient::connect_with_timeout(addr, timeout).await?;
let regs = client.read_holding_registers(1, 0, 10).await?;
```

* *More open-source protocol stacks, diagnostic libraries, and automation utilities will be published here as they pass site verification.*

---

### 🏭 Products & Capabilities

* **Industrial Sensors** — Noise-resistant, high-precision sensing units for field deployments.
* **Edge Gateways** — Multi-protocol communication hardware engineered for demanding factory environments.
* **Field Software & Diagnostics** — High-performance software tools for real-time observability, data routing, and commissioning.

---

### 📬 Contact & Links

* **Official Website:** [orangehorsetech.com](https://orangehorsetech.com)
* **LinkedIn:** [OrangeHorseTech](https://linkedin.com/company/orangehorsetech)
* **Email:** github@orangehorsetech.com
