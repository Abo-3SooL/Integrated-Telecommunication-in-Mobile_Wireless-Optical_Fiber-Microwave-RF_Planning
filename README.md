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

#### <ins>Power Calculations</ins>

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

#### <ins>Network Design</ins>
##### <ins><i>Requirements</i></ins>
<p align="center">
  <img src="Images/Mobile_Wireless_Requirements.jpg" alt="Mobile Wireless Requirements" width="600">
</p>

##### <ins><i>Technical Aspects</i></ins>

##### <ins><i>Components</i></ins>
<p align="center">
  <img src="Images/Passive_Antenna_Specifications.jpg" alt="Passive Antenna Specifications" width="600">
</p>
<p align="center">
  <img src="Images/Active_Antenna_Specifications.jpg" alt="Active Antenna Specifications" width="600">
</p>
<p align="center">
  <img src="Images/RF_Jumper.jpg" alt="RF Jumper" width="600">
</p>
<p align="center">
  <img src="Images/RF_Module.jpg" alt="RF Module" width="600">
</p>
<p align="center">
  <img src="Images/Wireless_Optical_Module.jpg" alt="Wireless Optical Module" width="600">
</p>
<p align="center">
  <img src="Images/CPRI_Cable.jpg" alt="CPRI Cable" width="600">
</p>
<p align="center">
  <img src="Images/BBU.jpg" alt="BBU 5900" width="600">
</p>
<p align="center">
  <img src="Images/MPT_Boards.jpg" alt="MPT Boards" width="600">
</p>
<p align="center">
  <img src="Images/BBP_Boards.jpg" alt="BBP Boards" width="600">
</p>

##### <ins><i>Implementation & Connection</i></ins>
<p align="center">
  <img src="Images/Mobile_Wireless_Design.jpg" alt="Mobile Wireless Design" width="600">
</p>
<p align="center">
  <img src="Images/BBU_Boards_Configuration.jpg" alt="BBU Boards Configuration" width="600">
</p>

##### <ins><i>Deliverables</i></ins>
<p align="center">
  <img src="Images/Mobile_Wireless_BOQs.jpg" alt="Mobile Wireless BOQ" width="600">
</p>
<p align="justify">Design is ready to be handed over. </p>

### <h3 id="optical-fiber">Phase 2: Optical Fiber Transmission</h3>
### <h3 id="microwave">Phase 3: Microwave Transmission</h3>
### <h3 id="atoll-forsk">Phase 4: Atoll Forsk Simulation</h3>
