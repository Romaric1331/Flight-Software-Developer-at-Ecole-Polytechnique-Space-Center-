# 🛰️ IONSAT CubeSat CAN Communication with ADCS

Welcome to the IONSAT project, a collaborative effort by ONERA, CNES, ThrustMe, and École Polytechnique aimed at developing and maintaining a powered nanosatellite in a very low orbit. This project focuses on leveraging the advantages of low orbits, such as reduced communication latency, enhanced resolution, and cost-effective launches.

## 🌌 Mission Overview
The satellite will launch from the ISS and utilize aerobreaking techniques to descend to an altitude of 300 km, harnessing atmospheric drag by orienting its largest surface perpendicular to its trajectory.

Upon reaching 300 km altitude, the station-keeping mission commences. The nanosatellite will undergo periodic descents to achieve a lower altitude of 10 km, marking a phased flight operation spanning a desired duration of six months, with potential extensions upon successful mission milestones.

### 🚀 Stage 1: CAN Communication with Arduino
Establishing effective communication between systems is pivotal. In this initial stage, the MCP2515 CAN bus stand-alone module is deployed to facilitate seamless data exchange between systems via CANH and CAN L bus connectors. This setup ensures inter-system coordination without reliance on a host computer.

### 🔗 Resources
Find all necessary resources and documentation within the enclosed "CAN_arduino communication" folder. To better comprehend the implementation process, refer to the comprehensive tutorial available at [MCP2515 CAN Module Arduino Tutorial](https://lastminuteengineers.com/mcp2515-can-module-arduino-tutorial/).

Feel free to explore the resources provided in the CAN_arduino communication folder for detailed setup instructions and further insights into this stage.
