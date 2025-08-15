# Integrated Telecommunication in (Mobile Wireless Communication, Optical Fiber Transmission, Microwave Transmission, and RF-Planning)

## Introduction
<p align="justify"> This repository contains a <b>proof-of-concept project</b> completed during my participation in the <b>Integrated Telecommunication Engineering Program</b>. The goal of this project was to demonstrate my capability to <b>design and implement telecommunication networks</b> based on specific <b>Key Performance Indicators (KPIs)</b> and technical requirements provided by my instructor. </p>

The work covers <b>three core domains</b> of telecommunications:
<ul>
  <li><b>Mobile Wireless Communication</b> – Equipment selection, RF planning and network simulation using Forsk Atoll software.</li>
  <li><b>Optical Fiber Transmission</b> – Selection and documentation of suitable equipment for high-capacity links.</li>
  <li><b>Microwave Transmission</b> – Simulation and planning using Forsk Atoll software of point-to-point connections for reliable backhaul.</li>
</ul>
<p align="justify"> Using <b>Huawei components</b> as the reference hardware, I evaluated technical options, selected optimal equipment, and prepared detailed documentation. The mobile wireless and microwave segments were further validated through simulation to ensure alignment with the project’s KPIs and operational requirements. </p>
<p align="justify"> This project serves as evidence of my skills in <b>network design, equipment specification, documentation, and simulation-based planning</b> across multiple telecommunication domains. </p>

## <h2>Project Plan</h2>
<p align="justify">The project is organized into four phases, each addressing a key domain of the telecommunication network: </p>
<ol>
  <li><b><a href="#mobile-wireless">Mobile Wireless Communication</a></b></li>
  <li><b><a href="#optical-fiber">Optical Fiber Transmission</a></b></li>
  <li><b><a href="#microwave">Microwave Transmission</a></b></li>
  <li><b><a href="#atoll-forsk">Atoll Forsk Simulation</a></b></li>
</ol>

The general workflow for each phase follows these steps:
<p align="center"><b>Collecting Requirements → Studying Technical Aspects → Choosing Components → Implementation & Connection → Deliverables</b></p>

<ol>
  <li><b>Collecting Requirements</b></li>
  This step is based on <b>Key Performance Indicators (KPIs)</b> and <b>strategic goals</b> of the intended telecom network. In this project, the requirements were provided by the instructor to simulate a real-world scenario.
  <li><b>Studying Technical Aspects</b></li>
  This phase involves reviewing relevant technical information, network standards, and design considerations. The goal is to ensure a solid technical foundation before moving to the design stage.
  <li><b>Choosing Components</b></li>
  Based on the requirements, appropriate <b>Huawei components</b> and other network elements are selected. This stage relies heavily on <b>datasheets</b> to evaluate technical specifications, compatibility, and performance.
  <li><b>Implementation & Connection</b></li>
  This includes <b>schematic designs, topology diagrams</b>, and establishing connections between components. For mobile wireless and microwave phases, simulations are carried out in <b>Forsk Atoll</b> to validate network performance.
  <li><b>Deliverables</b></li>
  <b>Final outcomes</b> prepared for handover to other engineering or operations teams including <b>Bill of Quantities (BOQs)</b>.
</ol>

## Project Phases
### <h3 id="mobile-wireless">Phase 1: Mobile Wireless Communication</h3>
<p align="justify">In this phase, we focused on designing mobile networks for <b>2G (GSM)</b>, <b>3G (UMTS)</b>, <b>4G (LTE)</b>, and <b>5G (NR)</b> technologies using the <b>Huawei BBU 5900</b> as the central baseband unit. We began by performing <b>power calculations</b> for GSM, UMTS, and LTE to determine the expected coverage areas based on link budget analysis. After validating the design parameters, we proceeded with the network layout and concluded the phase with a site survey to assess real-world deployment feasibility. </p>

### <ins>Power Calculations</ins>

##### <ins><i>Requirements</i></ins>
<p align="center">
  <img src="Images/Power_Calculation_Requirements.jpg" alt="Power Calculation Requirements" width="600">
</p>

##### <ins><i>Calculations & Results</i></ins>
<p align="center">
  <img src="Images/GSM_900_Power_Calculation.jpg" alt="GSM 900 Power Calculation" width="1000">
</p>
<p align="center">
  <img src="Images/UMTS_2100_Power_Calculation.jpg" alt="UMTS 2100 Power Calculation" width="1000">
</p>
<p align="center">
  <img src="Images/LTE_1800_Power_Calculation.jpg" alt="LTE 1800 Power Calculation" width="1000">
</p>

##### <ins><i>Coverage Area</i></ins>
<p align="center">
  <img src="Images/Coverage_Area.jpg" alt="Coverage Area" width="600">
</p>

### <ins>Project Design</ins>
##### <ins><i>Requirements</i></ins>
<p align="center">
  <img src="Images/Mobile_Wireless_Requirements.jpg" alt="Mobile Wireless Requirements" width="700">
</p>

##### <ins><i>Technical Aspects</i></ins>
To prepare for the mobile network design, I studied relevant <b>Huawei documentation</b> and key mobile communication concepts, focusing on:
<ul>
  <li><b>Huawei BBU 5900 Documentation</b> – Specifications, configuration, and integration for multi-technology deployments.</li>
  <li><b>MIMO (Multiple Input Multiple Output)</b> – Principles, configurations, and benefits in LTE and 5G.</li>
  <li><b>Spatial Diversity</b> – Techniques to improve signal robustness and minimize fading.</li>
  <li><b>Mobile Technologies Overview</b> – GSM, UMTS, LTE, and NR (5G) standards, supported bands, and spectrum allocation.</li>
  <li><b>Multiple Access Techniques</b> – FDMA (GSM), WCDMA (UMTS), OFDMA (LTE/5G), SC-FDMA (LTE uplink).</li>
  <li><b>Link Budget Analysis</b> – Power calculations for GSM, UMTS, and LTE to estimate coverage areas.</li>
  <li><b>Antenna Types & Configurations</b> – Sectorized antennas, omnidirectional antennas, and beamforming in LTE/5G.</li>
  <li><b>Propagation Considerations</b> – Path loss models applicable to urban, suburban, and rural environments.</li>
  <li><b>KPI-Driven Design</b> – Coverage, capacity, throughput, and mobility performance as per project requirements.</li>
</ul>
This technical background ensured the mobile wireless design met the <b>coverage and performance KPIs</b> while optimizing component selection and configuration.

##### <ins><i>Components</i></ins>
<p align="center">
  <img src="Images/Passive_Antenna_Specifications.jpg" alt="Passive Antenna Specifications" width="900">
</p>
<p align="center">
  <img src="Images/Active_Antenna_Specifications.jpg" alt="Active Antenna Specifications" width="900">
</p>
<p align="center">
  <img src="Images/RF_Jumper.jpg" alt="RF Jumper" width="600">
</p>
<p align="center">
  <img src="Images/Wireless_Optical_Module.jpg" alt="Wireless Optical Module" width="600">
</p>
<p align="center">
  <img src="Images/CPRI_Cable.jpg" alt="CPRI Cable" width="600">
</p>
<p align="center">
  <img src="Images/RF_Module.jpg" alt="RF Module" width="1000">
</p>
<p align="center">
  <img src="Images/BBU.jpg" alt="BBU 5900" width="1000">
</p>
<p align="center">
  <img src="Images/MPT_Boards.jpg" alt="MPT Boards" width="1000">
</p>
<p align="center">
  <img src="Images/BBP_Boards.jpg" alt="BBP Boards" width="1000">
</p>

##### <ins><i>Implementation & Connection</i></ins>
<p align="center">
  <img src="Images/Mobile_Wireless_Design.jpg" alt="Mobile Wireless Design" width="1000">
</p>
<p align="center">
  <img src="Images/BBU_Boards_Configuration.jpg" alt="BBU Boards Configuration" width="1000">
</p>

##### <ins><i>Deliverables</i></ins>
<p align="center">
  <img src="Images/Mobile_Wireless_BOQ.jpg" alt="Mobile Wireless BOQ" width="650">
</p>
<p align="justify">Design is ready to be handed over. </p>

### <h3 id="optical-fiber">Phase 2: Optical Fiber Transmission</h3>
<p align="justify">In this phase, we designed a <b>DWDM OTN (Dense Wavelength Division Multiplexing – Optical Transport Network)</b> to interconnect two countries, ensuring high-capacity and long-distance transmission. The solution was implemented using <b>Huawei OSN 9800</b> equipment, selected for its scalability and performance. In addition to meeting current capacity requirements, the design also incorporated a <b>future growth</b> plan to enable seamless capacity upgrades if traffic demand increases, ensuring long-term network reliability and flexibility. </p>

### <ins>Project Design</ins>
##### <ins><i>Requirements</i></ins>
<p align="center">
  <img src="Images/Optical_Fiber_Requirements.jpg" alt="Optical Fiber Requirements" width="650">
</p>

##### <ins><i>Technical Aspects</i></ins>
To prepare for the optical fiber network design, I studied <b>Huawei documentation</b> related to the <b>OSN 9800</b> platform and key optical transmission principles, including:
<ul>
  <li><b>Huawei OSN 9800 Documentation</b> – Equipment specifications, configuration guidelines, and scalability features for DWDM/OTN deployments.</li>
  <li><b>Optical Transport Network (OTN)</b> – Concepts, architecture, and standard framing structure.</li>
  <li><b>MS-OTN (Multi-Service OTN)</b> – Integration of multiple service types (Ethernet, SDH, etc.) over a single optical infrastructure.</li>
  <li><b>Liquid OTN</b> – Flexible OTN architecture for dynamic service provisioning and network optimization.</li>
  <li><b>Optical Fiber Bands</b> – Characteristics and applications of <b>C-band</b>, <b>S-band</b>, and <b>L-band</b> in DWDM systems.</li>
  <li><b>ROADM (Reconfigurable Optical Add-Drop Multiplexer)</b> – Operating principles, fixed-grid vs. flex-grid, and colorless/directionless/contentionless (CDC) configurations.</li>
  <li><b>Fiber Optic Network Protection Schemes</b> – 
    <ul>
  <li>Line-side protection (1+1, 1:1)</li>
  <li>Client-side protection</li>
  <li>Intra-board protection</li>
    </ul>
  </li>
  <li><b>Fiber Loss Calculation</b> – Attenuation, splice loss, connector loss, and system margin calculations.</li>
  <li><b>Dispersion Management</b> – Chromatic and polarization mode dispersion control in long-haul transmission.</li>
  <li><b>Amplification Techniques</b> – Use of EDFAs (Erbium-Doped Fiber Amplifiers) and Raman amplification in DWDM.</li>
  <li><b>KPI Considerations for Optical Networks</b> – Latency, BER (Bit Error Rate), and availability targets.</li>
</ul>
This technical preparation ensured the DWDM OTN design was <b>high-capacity, resilient, and future-proof</b>, meeting current requirements and allowing for seamless upgrades.

##### <ins><i>Components</i></ins>
<p align="center">
  <img src="Images/OSN.jpg" alt="OSN 9800" width="700">
</p>
<p align="center">
  <img src="Images/M520SM+DCP.jpg" alt="M520SM & DCP" width="1000">
</p>
<p align="center">
  <img src="Images/TMD20+WSMD9.jpg" alt="TMD20 & WSMD9" width="1000">
</p>
<p align="center">
  <img src="Images/DAP+DAPXF.jpg" alt="DAP & DAPXF" width="1000">
</p>
<p align="center">
  <img src="Images/AST+OPM.jpg" alt="AST & OPM" width="1000">
</p>
<p align="center">
  <img src="Images/Others1.jpg" alt="Auxiliary Board" width="1000">
</p>
<p align="center">
  <img src="Images/PIU.jpg" alt="PIU" width="650">
</p>
<p align="center">
  <img src="Images/Fiber_Optical_Module.jpg" alt="Fiber Optical Module" width="650">
</p>
<p align="center">
  <img src="Images/Fiber_Cable.jpg" alt="Fiber Cable" width="650">
</p>

##### <ins><i>Implementation & Connection</i></ins>
<p align="center">
  <img src="Images/HLD_Optical.jpg" alt="High Level Design Optical" width="1000">
</p>
<p align="center">
  <img src="Images/HLD_Electrical.jpg" alt="High Level Design Electrical" width="1000">
</p>

##### <ins><i>Deliverables</i></ins>
<p align="center">
  <img src="Images/Optical_Fiber_BOQ.jpg" alt="Optical Fiber BOQ" width="650">
</p>
<p align="justify">Design is ready to be handed over. </p>


### <h3 id="microwave">Phase 3: Microwave Transmission</h3>
### <h3 id="atoll-forsk">Phase 4: Atoll Forsk Simulation</h3>
