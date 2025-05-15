
# Portable Line Boring & Bore Welding Digital Twin

This repository presents a full Digital Twin prototype for an **integrated portable line boring and bore welding machine**. This unique machine combines in-situ machining precision with bore welding capability, making it ideal for on-site industrial maintenance and structural restoration. The Digital Twin leverages low-cost sensors, edge computing, and open-source tools for real-time monitoring, process optimization, and predictive maintenance.

## 🛠 Project Features

- **Portable Line Boring + Bore Welding Integration**
- Real-time sensor feedback (vibration, strain, temperature, flow)
- Predictive maintenance via ML-based tool/weld condition monitoring
- Feedback control with Arduino + CompactRIO + LabVIEW options
- Visualization using Grafana dashboards and Power BI
- Simulations using OpenModelica and Python

## 📦 Repository Structure

```
Portable-LineBoring-BoreWeld-DigitalTwin/
├── README.md
├── index.html
├── docs/
│   ├── Digital_Twin_Architecture.png
│   ├── Case_Study_Report.docx
│   ├── Presentation_Deck.pptx
├── bom/
│   └── Digital_Twin_BOM.xlsx
```

## 🔍 Use Case

Designed for field applications where both line boring and weld restoration are performed with minimal setup, this system offers:
- Visual monitoring of bore/weld process health
- Deflection and temperature-based feedback for weld tuning
- Process optimization and historical analytics

## 🌐 GitHub Pages

Visit the live project website:  
**https://yourusername.github.io/Portable-LineBoring-BoreWeld-DigitalTwin/**

## 🧠 References

- Siemens MindSphere + OPC UA for industrial edge connectivity
- Arduino, Raspberry Pi 4, CompactRIO as DAQ controllers
- ANSYS, OpenModelica for modeling boring & weld distortion
- MQTT + Node-RED for IoT messaging and dashboard linkage

## 📜 License

MIT License
